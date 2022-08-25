# ZabbixDockerCompose

Criar 5 containers: zabbix-server, zabbix-agent2, zabbix-frontend, grafana e mysql.
IMAGES:
- mysql:5.7
- zabbix/zabbix-server-mysql:ubuntu-5.0.1
- zabbix/zabbix-web-apache-mysql:ubuntu-5.0.1
- grafana/grafana
- zabbix/zabbix-agent2:alpine-5.0.1

Zabbix já estará conectado ao banco de dados MySQL e o Grafana já estará com o plugin do Zabbix instalado.

# Comando

docker-compose up -d
