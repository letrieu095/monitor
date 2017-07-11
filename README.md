
### Cài Telegraf

    ansible-playbook -i hosts site.yml --tags "telegraf"

### Cài trên một máy trong cụm kafka

Cài InfluxDB

        ansible-playbook -i hosts site.yml --tags "influxdb" --limit=192.168.188.149  

Cài Grafana

        ansible-playbook -i hosts site.yml --tags "grafana" --limit=192.168.188.149

Cài Kapacitor

        ansible-playbook -i hosts site.yml --tags "kapacitor" --limit=192.168.188.149





