# jhipster-monolithic-stock-demo
This project explains how to use Jhipster with simple monolithic application

### JHipster 
JHipster is a development platform to generate, develop and deploy Spring Boot + Angular/React Web applications and Spring microservices.

In this project, I have generated a simple monolithic springboot application.

### Install JHipster

Install Java 8 from the Oracle website.
Install Node.js from the Node.js website (please use an LTS 64-bit version, non-LTS versions are not supported)

***Through Yarn***

Install Yarn from the Yarn website
If you want to use the JHipster Marketplace, install Yeoman: yarn global add yo
Install JHipster: yarn global add generator-jhipster

***Through npm***

Instead of installing Yarn from above, update NPM: npm install -g npm
Use npm install -g instead of yarn global add, for example:
To install Yeoman, type: npm install -g yo
To install JHipster, type: npm install -g generator-jhipster

### Sample JHipster Application Generator ###
![jhip-1.png](jhip-1.png)

![jhip-2.png](jhip-2.png)

### Generate Entity through jhipster

![jhip-4.png](jhip-4.png)

### Start the application through the below command
```
From Springboot ./mvnw 

From Angular npm start
```

![jhip-5.png](jhip-5.png)

### Application Screenshots
![jhip-6.png](jhip-6.png)

![jhip-7.png](jhip-7.png)

![jhip-8.png](jhip-8.png)

![jhip-9.png](jhip-9.png)

![jhip-10.png](jhip-10.png)

![jhip-11.png](jhip-11.png)

### Create docker compose yml file for running the application in docker

***Step 1 :***  Create folder name as docker in root directory (you can create any name)
***Step 2 :***  Run this command *** jhipster docker-compose


![jhip-12.png](jhip-12.png)

***Step 3:*** Run the command in Stock Application
```
./mvnw verify -Pprod dockerfile:build
```
![jhip-13.png](jhip-13.png)

***Step 4:*** Run the command docker-compose up
![jhip-14.png](jhip-14.png)

The stock application is running in docker

![jhip-15.png](jhip-15.png)

### Happy Coding ###




