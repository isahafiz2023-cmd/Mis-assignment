git clone https://github.com/<isahafiz2023-cmd>/<Mis-assigment>.git \
&& cd <Mis-assignment> \
&& pip install -r requirements.txt
pandas
numpy
matplotlib
seaborn
sqlalchemy
ipython
jupyter
drawio-export
psycopg2-binary
ngrok
screenshots/
   backlog_plot.png
   weekly_ticket_volume.png
   resolution_distribution.png
### Weekly Ticket Volume
![Weekly Ticket Volume](screenshots/weekly_ticket_volume.png)

### Backlog Over Time
![Backlog](screenshots/backlog_plot.png)
![Process Map](data/process_map.png)
├── data/
│   ├── tickets.csv
│   ├── processed/
│   └── process_map.drawio
│
├── sql/
│   ├── schema.sql
│   ├── transforms.sql
│   └── queries.sql
│
├── notebooks/
│   └── ProjectMIS25.ipynb
│
├── src/
│   ├── load_data.py
│   ├── calculate_backlog.py
│   ├── visualize_metrics.py
│   └── utils.py
│
├── screenshots/
│   ├── backlog_plot.png
│   ├── weekly_volume.png
│   └── distribution_hist.png
│
├── requirements.txt
├── README.md
└── LICENSE
| Column name        | Type        | Description                                      |
| ------------------ | ----------- | ------------------------------------------------ |
| `ticket_id`        | string/int  | Unique ticket identifier                         |
| `created_at`       | datetime    | When the ticket was opened                       |
| `resolved_at`      | datetime    | When the ticket was marked resolved (nullable)   |
| `closed_at`        | datetime    | When the ticket was fully closed (nullable)      |
| `assigned_to`      | string      | Agent or team handling ticket                    |
| `priority`         | string      | Priority level (Low/Med/High)                    |
| `status`           | string      | Current status: open, assigned, resolved, closed |
| `category`         | string      | Ticket topic/type                                |
| `reopened`         | boolean/int | Whether the ticket has been reopened             |
| `sla_hours`        | float       | SLA limit for the ticket                         |
| `resolution_hours` | float       | Hours between create → resolve                   |
