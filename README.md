# IoT Temperature Monitoring (MQTT)

## Description
This project demonstrates an IoT temperature monitoring pipeline using the MQTT protocol.
Temperature data is simulated from a CSV dataset, transmitted via MQTT, stored in an SQLite database,
and visualized using interactive dashboards.

## Technologies
- MQTT (Mosquitto, paho-mqtt)
- SQLite
- Python (Pandas)
- Plotly
- Google Colab

## Pipeline
CSV → MQTT Publisher → MQTT Subscriber → SQLite → Dashboard

## Outputs
- `iot.db` — SQLite database
- `dashboard_in_out.html` — Temperature over time (In vs Out)
- `dashboard_by_room.html` — Temperature over time by room
- `report.pdf` — Project report
