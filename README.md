<img src="https://github.com/NURULFARAHINirwanshah/Network-Monitoring-Dashboard-Using-Grafana-Open-Source/blob/master/Screenshots/logo.png" align="left" width="80px">

# Network Monitoring Dashboard Using Grafana Open Source
Network Monitoring Dashboard using Grafana Open Source is developed to monitor the network availability and server utilization as to track the RTO to fulfill the SLA to the business. The data is collected by Telegraf agent that has been  installed on the server. It works by scraping the metrics and the result will be sent to InfluxDB datasource. Next, all the data will be visualized in Grafana.

## System Specification
Grafana version     : Grafana v6.3.5  
Data source version : InfluxDB v1.7.9; Prometheus v2.12.0  
Agent version       : Telegraf v1.5.1; WMI Exporter v0.8.1  
User OS             : Windows 10  
Browser             : Chrome 79  
Grafana plugins     : Alert List, Boom Table, Dashboard List, Flowcharting, Gauge, Graph, InfluxDB, MySQL, Prometheus, SimpleJSON, Singlestat, Table, TestData DB, Text, Datasource, PDF Report

## System Architecture
<img src="https://github.com/NURULFARAHINirwanshah/Network-Monitoring-Dashboard-Using-Grafana-Open-Source/blob/master/Screenshots/architecture.png" width="70%">


## Screenshots

### Status
* Green indicates OK
* Orange indicates WARN
* Red indicates BREACHED

### Homepage (servers list)
![s1](https://github.com/NURULFARAHINirwanshah/Network-Monitoring-Dashboard-Using-Grafana-Open-Source/blob/master/Screenshots/server%20panel.png)

### Application server availability (ping)
![s5](https://github.com/NURULFARAHINirwanshah/Network-Monitoring-Dashboard-Using-Grafana-Open-Source/blob/master/Screenshots/servers%20performance.png)

### SDDC diagram
![s2](https://github.com/NURULFARAHINirwanshah/Network-Monitoring-Dashboard-Using-Grafana-Open-Source/blob/master/Screenshots/sddc%20panel.png)

### Campus server availability (pinging)
![s3](https://github.com/NURULFARAHINirwanshah/Network-Monitoring-Dashboard-Using-Grafana-Open-Source/blob/master/Screenshots/server%20performance.png)

### Report
![s4](https://github.com/NURULFARAHINirwanshah/Network-Monitoring-Dashboard-Using-Grafana-Open-Source/blob/master/Screenshots/pdf%20report.png)
