# Setup an Aurora Database and Web Server
 OnlineNewsWebapplication

Amazon Aurora: is a fully managed relational database engine built for the cloud with full MySQL and PostgreSQL compatibility. Aurora gives you the performance and availability of commercial-grade databases at one-tenth the cost.

In this project, I:

✅ Created an EC2 instance to host a web application
✅ Created an Amazon Aurora database 
✅ Created a Multi-AZ deployment with a read replica for high availability 

I first created the web server (EC2 instance), that will host the web application. Then I created an Amazon Aurora database to store and display data for my very own Online News web application( I did not design the Online News web application). I made sure to deploy the database as a Multi-AZ deployment with a read replica for high availability . Any application that has a read intensive workload should have read replicas in multiple availability zones in the event of a failure. Lastly, I connected the Aurora database to the web server (EC2 instance) that will be hosting the Online News web application.