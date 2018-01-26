# zabbix-supervisor
Very simple monitoring of Supervisor with Zabbix Agent

# Instructions

- Place userparameter_supervisord.conf file into /etc/zabbix/zabbix_agentd.d/ directory and restart Zabbix Agent
- Place zabbix file into /etc/sudoers.d/ directory
- Import zabbix_supervisor_v3_template.xml template via Zabbix Web
- Add hosts to Template App Supervisor template

Tested with:
Zabbix Server 3.0.14
Supervisor 3.0
