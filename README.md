# Implementation of some best practice system design

Example:
+ Implement a Single Server System (centrialized achitecture) so that student understand about non-functional requirement like Performance, Scability, HA & fault tolerance
  
+ Implement a Distributed System (distributed-microservice achitecture) and some common chalenge with this architecture (Transaction, Data Consistency, Scability - Stateless & Statefull)
  - Load Balancer (Explain why LB is different with Web Server so that it can handle much more request simutenously than the Web Server)
  - API Gateway
  - Web Server 
  - Message Broker (loose coupling services & independent scalibility & event driven)
  - Database (How to choose right one ? Read-write frequency, Datastructe (Ex: json format), ACID, CAP theorem )
  - Cache
  - CDN

+ Implement a cordinator application for sharding
  - using normal hashing
  - using consisten hashing
