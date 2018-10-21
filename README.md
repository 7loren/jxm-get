# jxm-get
zabbix jmx get like zabbix-get


```
shell# chmod 755  /usr/sbin/jmx_get  #使脚本具有执行权限
shell# jmx_get 10.211.55.10 10052 10.211.55.9 10053 'jmx[\"java.lang:type=Memory\",HeapMemoryUsage.used]'
{"data":[{"value":"8701688"}],"response":"success"}
```
