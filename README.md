# Template Active Microsoft IIS

Template for discovering IIS sites and application pool on hosts and monitoring the state after  (stopped or started ) automatically.

## Contribution
Contribute with PR.

## Installation
1. Import the "zbx_IIS8_templates.xml" to zabbix and link it to the zabbix IIS host.
2. Copy the userparameter_iis_monitoring.conf to /etc/zabbix/zabbix.agent.d/
3. Copy the powershell scripts (.ps1) to /etc/zabbix/zabbix.agent.d/
4. restart zabbix-agent to apply userparameters.


## References
- https://www.zabbix.com/documentation/4.4/manual/introduction
