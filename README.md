# A real-time analytic system using storm, kafka, zookeeper and flume based on docker container.
----------

## 1. Overview ##
[![][ButlerImage]][website] 

## 2. How to use?  ##

**1. The prerequisite is you must have docker engine and docker compose installed.**
	
	docker -v
	docker-compose -v
**2. Update configuration file**
   
	docker-compose.yml

**3. Start Services**
   
	docker-compose up -d

**4. View services**
   
	docker-compose ps

**5. View logs**
   
	docker-compose logs

**6. scale services**
   
	docker-compose scale kafka=4
   	docker-compose scale kafka=2

**7. stop services**
   
	docker-compose stop

**8. Remove Containers**
   
	docker-compose rm


## 3. Running effect ##
[![][nodesStatus]][website] 
[![][kafkaUi]][website] 
[![][stormUi]][website] 



## 4. TODO ##

	Support multiple nimbus nodes.



[ButlerImage]: https://github.com/weixuan2008/storm-kafka-zookeeper-flume/blob/master/storm-kafka-zookeeper-flume-master/images/arch.png
[nodesStatus]: https://github.com/weixuan2008/storm-kafka-zookeeper-flume/blob/master/storm-kafka-zookeeper-flume-master/images/nodes%20run%20status.PNG
[kafkaUi]: https://github.com/weixuan2008/storm-kafka-zookeeper-flume/blob/master/storm-kafka-zookeeper-flume-master/images/kafka%20ui.PNG
[stormUi]: https://github.com/weixuan2008/storm-kafka-zookeeper-flume/blob/master/storm-kafka-zookeeper-flume-master/images/storm%20ui.PNG
[website]: https://github.com/weixuan2008/storm-kafka-zookeeper-flume
