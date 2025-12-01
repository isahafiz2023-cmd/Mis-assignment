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
