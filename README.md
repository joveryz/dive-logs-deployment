# Dive Logs Deployment

Deployment of the dive logs web application to Github Pages.

## Github Actions Workflow

1. Download the dive logs exporter to generate the CSV file from the dive computer data files. 

2. Build the dive logs web application using the generated CSV file.

3. Deploy the generated web application to Github Pages.

## Related Repositories

- [dive-logs-exporter](https://github.com/joveryz/dive-logs-exporter): Export dive logs from dive computers' data files to CSV.
- [dive-logs-web](https://github.com/joveryz/dive-logs-web): Dive log viewer and analyzer web application.
- [dive-logs](https://github.com/joveryz/dive-logs): Dive logs data files from dive computers.

Any changes to these repositories will trigger this Github Actions workflow to regenerate and redeploy the dive logs web application.
