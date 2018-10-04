# Folders
+----step1 -> contains simple example of elasticstack with a logstash configuration based on PlayerProfile use case  
|   +---elasticsearch  
|   |   +---data  
|   |   +---settings  
|   +---kibana  
|   +---logstash  
|       +---logs  
|       +---pipeline  
|       +---settings  
+---step2  -> contains simple example of elasticstack with filebeats  
|   +---elasticsearch  
|   |   +---data  
|   |   +---settings  
|   +---filebeat  
|   +---kibana  
|   +---log  
|   +---logstash_server  
|   |   +---pipeline  
|   |   +---settings  
|   +---tomcat  
|       +---war  
+---step3 -> contains a complex example based on the PROD infrastucture  
    +---elasticsearch  
    |   +---data  
    |   +---settings  
    +---kibana  
    +---logstash_client  
    |   +---logs  
    |   +---pipeline  
    |   +---pipeline  
    |   +---settings  
    +---logstash_server  
    |   +---pipeline  
    |   +---settings  
    +---tomcat  
        +---war  
# How To Start Docker Containers  

enter one folder (e.g. step1) then issue the command   
```
docker-compose up -d
```
docker will download images and start up containers with the given configuration. 

# Ports
* ELASTICSEARCH: 9200  
* KIBANA: 5601  
* TOMCAT: 8080   
