# ELK-Example
Talking about ELK stack which includes Elasticsearch, Logstash and kibana.  
Here you can find two sample log files  
1. apache logs
2. calculator logs of [calculator-devops](https://github.com/shubhamaggarwal890/calculator-devops)  

For each log file a sample logstash configuration file is also attached which will help parse the log files and visualize it on kibana.  

## Running using ELK Stack
Download ELK Stack  
1. [Elasticsearch](https://www.elastic.co/downloads/elasticsearch)
2. [Logstash](https://www.elastic.co/downloads/logstash)
3. [Kibana](https://www.elastic.co/downloads/kibana)

Running Elasticsearch
```
./path/to/Elasticsearch-folder/bin/elasticsearch
```
Running Logstash
```
./path/to/logstash-folder/bin/logstash -f /path/to/conf/file
```
Running Kibana
```
./path/to/kibana-folder/bin/kibana
```