
**Monolith Application**
-----------------------

  1. An application design.<br/>
  2. Any application is designed in such a way. <br/>
    1. it will be released once in every few months<br/>
    2. it will have wide range of features & functionalities<br/>
    3. more number of people working on it[50+]<br/>
    4. debugging and adopting new technology or process is challenging or almost impossible<br/>
    5. it will be huge more than 1M lines of code<br/>
    6. scalability challenges<br/>
    7. Innovative challenges<br/>
    
**Solution:**
--------

Microservice arch evolved as a solution of scalability and innovative challanges with monolith arch.<br/>

will have several indipendent appln that can run on their own <br/>
those can be created in different programming language & even platform<br/>
These programs are grouped to deliver all the functionalities of the big monolith appln<br/>

## Microservices ##
-----------------

  * Microservice arch is an approach to build a server application as a set of small services.
  * It is mainly oriented to the backend for building services but it is being used for front end as well which will be called Micro UI.
  * Each process will run on its own process and communicate with each other processes using protocals like http/https, websocket & AMQP.
  * Each microservice implements specific end to end domain or business capability.
  * Each microservice must be developed autonomously and deployed independently.
  * Each microservice should own its related domain  data model on different data storage technologies and different programming technologies.
  * It is important that each microservices should be loosely coupled services make them as small as possible.


## Why? ##
----------
  * It provides long term agility.
  * Monolith applns can be scalled out as a single unit, where as microservices arch, each microservices can be scalled out.
  * Each services are independently versioned, executed and scaled.
  * Cloud platform & microservices lend themselves to newer technologies like containerization.

## Best Prctices ##
-------------------

  * Seperate the data store for each microservice.
  * Seperate the build for each microservice.
  * Always treat server as stateless.
  * Its is a open source3 methodology.
  * SOA is a design pattern but microservice is an implementation methodology for SOA.

## Categories of Services ##
----------------------------

  - Platform as a Service => PaaS
  - Software as a Service => SaaS
  - Infrastructure as a Service => Iaas
  - Data as a Service => DaaS
  - Backend as a Service => BaaS

  => Each microservice has its own DB.<br/>
  => One Microservice can performs Create, Read, Update  & Delete operations on a data source.<br/>
  
  ## Microservice Architechture ##
  
  ![eshoponcontainers-development-architecture](https://user-images.githubusercontent.com/74425320/115436740-ef00ab00-a1d0-11eb-837d-d45397efdc13.png)


## Advantages ##

  * Autonomous/Independent developement
  * Independent deployment
  * Technology diversity
  * Fault isolation. Entire system will not be down even if one service is down.
  * Granular scaling.






