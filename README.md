# Prometheus_GUI
holds the docker config files for a flask python app, prometheus monitering system, and the grafana visualization software.

Commands:
 1. install docker and docker compose
 2. pull repo
 3. docker compose build
 4. docker compose up 
 5. docker compose down(to shut down)


Grafana data source URL: http://prometheus:9090
Grafana Username/Password: admin/admin

TODO:
- Add to flask app so we can read from Rocket Network, then send it to Prometheus/metrics
- 
- write and save a Grafana dashboard
