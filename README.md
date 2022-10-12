# db-postgres-using-SQLgateway #  
An example repository using PostgreSQL SQLgateway to demonstrate exporting and importing instances of the %Library.SQLConnection class with copying jdbc drivers.
This is especially useful when you want to copy items to another iris server through the package manager's private registry while keeping your private settings.

[![Demo](https://img.shields.io/badge/Demo%20on-Cloud%20Run%20Deploy-F4A460)](https://apptools-gateway.demo.community.intersystems.com/csp/sys/mgr/UtilSqlGateways.csp)

## Credits ##
0. OEX package [migration-pg-iris-dataset](https://openexchange.intersystems.com/package/migration-pg-iris-dataset) 
provided by [YURI MARX PEREIRA GOMES](https://openexchange.intersystems.com/user/YURI%20MARX%20PEREIRA%20GOMES/QKGV1uPuZml09uNsC8bNKcRQj8)   
    - Special thanks as this was an excellent base to start off.  
    
1. Article about PostgreSQL into Docker: 
    - https://levelup.gitconnected.com/creating-and-filling-a-postgres-db-with-docker-compose-e1607f6f882f
2. Git project created from: 
    - https://github.com/jdaarevalo/docker_postgres_with_data
    - https://github.com/intersystems-community/iris-docker-zpm-usage-template

3. OEX package [db-migration-using-SQLgateway](https://openexchange.intersystems.com/package/db-migration-using-SQLgateway) 
provided by [Robert Cemper](https://openexchange.intersystems.com/user/Robert%20Cemper/v2WPTpUS8nGmGLNs612I7IeKRzc)   
    - Thank you so much as this is a great project to learn and practice new skills.  
    

## Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.

## Installation 
Clone/git pull the repo into any local directory
```
git https://github.com/SergeyMi37/db-postgres-using-SQLgateway.git
```
1. Build
```
docker-compose build
```
2. Run it in foreground. Sometimes container start is slower than estimated.  
```
docker-compose up
```
