# zabbix-asterisk
Zabbix agent template asterisk pjsip

cp zabbix-asterisk/asterisk.conf /etc/zabbix/zabbix_agentd.conf.d/
cp -r zabbix-asterisk/script /etc/zabbix/zabbix_agentd.conf.d/

with visudo add this line in file
%zabbix ALL=(asterisk) NOPASSWD:/usr/sbin/asterisk
