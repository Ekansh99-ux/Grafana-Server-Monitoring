# Grafana Server Monitoring Dashboard

## Project Overview
An interactive server monitoring dashboard built using Grafana and the Infinity Data Source plugin. The project uses server access log data to visualize HTTP requests and monitor server activity.

## Features
- Server access logs displayed in a tabular format.
- Total request count visualization.
- HTTP status and request monitoring.
- IP address, endpoint, HTTP method and timestamp analysis.
- CSV data integration using Grafana Infinity Data Source.

## Tech Stack
- **Dashboard:** Grafana
- **Data Source:** Grafana Infinity Plugin
- **Data Format:** CSV
- **Language:** Python
- **Tools:** VS Code

## Dataset
The project uses sample web server access logs containing:
- IP addresses
- Timestamps
- HTTP methods (GET, POST)
- Endpoints
- HTTP protocols
- HTTP response status codes

## Project Structure
```text
Grafana Server Monitoring/
│
├── Data/
│   ├── cleaned_logs.csv
│   └── weblog.csv
│
├── Screenshots/
│   └── Dashboard screenshots
│
├── clean_logs.py
└── README.md
```

## Dashboard Panels
1. **Total Requests:** Displays the total number of records processed.
2. **Server Access Logs:** Displays server request details in a tabular format.

## How to Run
1. Install Grafana.
2. Install and configure the Infinity Data Source plugin.
3. Start the local HTTP server from the project directory:
   `python -m http.server 8000`
4. Configure the CSV URL in Grafana.
5. Create dashboard panels and connect them to the CSV data source.

## Objective
To demonstrate practical server log monitoring, data integration, and dashboard visualization using Grafana.

