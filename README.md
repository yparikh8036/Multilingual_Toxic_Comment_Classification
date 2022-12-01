# Multilingual_Toxic_Comment_Classification
        Yashkumar Parikh
        Lakehead University - Computer Science
        Email: parikhy@lakeheadu.ca
        
 ## Table of Contents

1. [Project Description](#project-description)
2. [This project includes the following things](#this-project-includes-the-following-things)
3. [Architecture followed](#architecture-followed)
4. [Project Related Terminologies](#project-related-terminologies)
5. [Install](#install)
6. [Swagger URL](#swagger-url)
7. [Project Status](#project-status)
8. [Road-map](#road-map)
9. [Contributors](#contributors)
10. [Contact Details](#contact-details)

## Project Description

This website is designed for selling products online. Users can register them selfs into the website, filter and search for different products category-wise, add products to the cart and order the item. 

## This project includes the following things
1. Spring Security Configured.
2. MySQL Configured.
3. Liquibase Configured.
4. Ehcache Configured.
5. Two different env Configured (Dev and Prod).
6. Spring actuator Configured.
7. Logging Configured (Through AOP).
8. Pre-made User and Authority Class with CRUD Rest endpoints ready.
9. Swagger Configured.

## Install

To run on local follow the given steps:

    1. git clone repo_link.
    2. Import as Gradle project in IntelliJ.
    3. Create a schema in the DB server with the name mentioned in 
       the application-dev.yml file in the data source URL.
    4. if Linux user run ./gradlew clean and then ./gradlew -Plocal.
    5. if windows user run gradlew  clean and then gradlew -Plocal.
    
## Contributors

[Yash Parikh](https://github.com/yparikh8036)  ![twitter](https://img.shields.io/twitter/follow/parikh_y?style=social)

## Contact Details

Anyone has any questions or wants to contribute to the project then write an email at parikhy@lakeheadu.ca.

## Licence

Copyright 2021 Province of Ontario, Canada

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at 

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
