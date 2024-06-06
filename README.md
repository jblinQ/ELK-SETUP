# ELK-SETUP
ELK stack with NGINX

Running the command "docker compose up" will set it up. Then you can now access kibana on port 5601; the password is in the ".env file" where the password on first login is "elastic". The logs were ingested into Elasticsearch using Filebeat, Logstash, and Metricbeat; the filebeat ingested NGINX logs, the LOGSTASH ingested csv file, while METRICBEAT ingested the Docker logs, then the datas can now be visualized in KIBANA.
