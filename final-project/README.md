## Описание стенда

Виртуальные машины:
1. otus-redmine.lab.sz с адресом 10.0.0.174.
На ВМ расположен сервис redmine, который включает в себя СУБД MaridDB и веб-сервер Apache.
Для мониторинга используется:
- Страница статуса apache2
- node_exporter 
- filebeat
- metricbeat
- auditbeat
- rsyslog

2. otus-logserver.lab.sz с адресом 10.0.0.173.
Для мониторинга используется:
- Страница статуса nginx
- node_exporter 
- filebeat
- metricbeat
- auditbeat
- heartbeat
- rsyslog
- nginx-exporter
- apache-exporter
- blackbox-exporter
- mysqld-exporter
- cadvisor

На ВМ расположены все сервисы мониторинга, а именно:
- rsyslog
- prometheus
- grafana
- alertmanager
- logstash
- elasticsearch
- kibana
