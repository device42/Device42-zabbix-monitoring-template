## Device42 appliance health monitoring zabbix template 

- Place `check_d42` script to zabbix server external scripts path(/usr/lib/zabbix/externalscripts);
- Import template to zabbix server;
- Add your device42 appliance host to zabbix server, link the template to it;
- Assign `$D42_URL, $D42_USER, $D42_PWD` as per your environment on either template or host level;
- Enjoy :-)
