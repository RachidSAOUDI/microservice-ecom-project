# microservice-ecom-project

## Dependencies 
1. Config-Service
   Config Server
   Spring Boot Actuator
   Consul Discovery
2. Customer-service
   Spring Web
   Spring Data JPA
   H2 Database
   Lombok
   Rest Repositories
   Consul Discovery
   Config Client
   Spring Boot Actuator
3. inventory-service
   Spring Web
   Spring Data JPA
   H2 Database
   Lombok
   Rest Repositories
   Consul Discovery
   Config Client
   Spring Boot Actuator
4. Order-service
   Spring Web
   Spring Data JPA
   H2 Database
   Lombok
   Rest Repositories
   Consul Discovery
   Config Client
   Spring Boot Actuator
5. Gateway-service
   Gateway
   Spring Boot Actuator
   Consul Discovery

#download tools
## download consul
    https://developer.hashicorp.com/consul/downloads?host=www.consul.io
## execute commande consul installation folder
    consul agent  -server  -bootstrap -expect=1  -data-dir=consul-data  -ui  -bind=192.168.1.4
## test consul in localhost
http://localhost:8500

