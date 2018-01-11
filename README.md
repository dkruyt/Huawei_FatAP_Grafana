### Huawei_FatAP_Grafana 

A templated Dashboard for Huawei Fat WLAN AP in Grafana

Dependencies InfluxDB as the time-series database and Telegraf as the collector should be installed.

For all latest files, see [My GitHub page](https://github.com/dkruyt/Huawei_FatAP_Grafana)

### Quick Start

* Enable SNMP on your Huawei WLAN FAT Accespoint
* Put hw_stor.conf in your `/etc/telegraf/telegraf.d` directory
* Edit the community string as appropriate
* Edit the 'agents' list to include all of your monitored Fat WLAN Access points
* Put the files in the mibs dir `/usr/share/snmp/mibs`
* Import the Grafana dashboard json file

### Screenshot

After you setup all, you should have some dashboard like this

![Grafana screenshot Huawe FAT AP](https://raw.githubusercontent.com/dkruyt/Huawei_FatAP_Grafana/master/Huawei%20FAT%20AP%20templated.png)
