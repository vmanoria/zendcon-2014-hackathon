#On this page you will find the sample code for the IBM Hackathon at ZendCon 2014. 

To clone the code, use your favorite git client to perform

```
git clone https://github.com/IBM-Bluemix/zendcon-2014-hackathon.git
```

The top level directory contains subdirectories for various services you may find useful as you are hacking your code. Remember, you are free to use any service you would like but we encourage you to consider the services listed below.

##Cloudant

Cloudant is a JSON data store, a type of a NoSQL database that is an excellent fit for multi-structured data, unstructured data and fast-changing data models. With 

```
cf login
cf push
cf create-service cloudantNoSQLDB Shared myCloudant
cf bind-service cloudant-php-12345 myCloudant
cf push
```

##Sendgrid

Sendgrid is the world's largest email infrastructure as a service provider focused on deliverability, scalability, and reliability. 

```
cf login
cf push
cf create-service sendgrid free mySendgrid
cf bind-service sendgrid-php-12345 mySendgrid
cf push
```
