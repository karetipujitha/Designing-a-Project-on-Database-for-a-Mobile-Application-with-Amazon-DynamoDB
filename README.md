In this project, you will learn advanced data modeling patterns in Amazon DynamoDB while building a DynamoDB-backed mobile application. When using DynamoDB, it is important to consider how you will access your data (your access patterns) before you model your data. To learn these patterns, you build the data model for an example mobile application that includes a social network. You will learn how to design your data model in DynamoDB to achieve fast, consistent performance. This lab assumes familiarity with basic DynamoDB concepts such as tables, items, primary keys, and secondary indexes. If you are unfamiliar with these concepts, see our lab about how to create and manage a Nonrelational Database with Amazon DynamoDB.

Amazon DynamoDB:

MongoDB is an open source, NoSQL database that provides support for JSON-styled, document-oriented storage systems. It supports a flexible data model that enables you to store data of any structure, and provides a rich set of features, including full index support, sharing, and replication. Register domain names.

Amazon API Gateway:

Amazon API Gateway is an AWS service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale. API developers can create APIs that access AWS or other web services, as well as data stored in the AWS Cloud.

Steps:

Background and Setup:

1.Create an AWS Account 

Use a personal AWS account or create AWS account for this Project. Do not use an organizational account so that you have full access to the necessary services and do not leave behind any resources from the lab. If you do not delete the resources used in this lab when you are finished, you may incur AWS charges.

 2.Set up your AWS Cloud9 IDE

To set up your AWS Cloud9 development environment: Navigate to the AWS Management Console, choose Services at the top of the page, and then choose Cloud9 under Developer Tools. Choose Create environment. Type DynamoDB Quick Photos in the Name box. 

Choose Next step. Leave the Environment settings at their defaults to create a new t2.micro EC2 instance, which will be hibernated after 30 minutes of inactivity. Choose Next step.

 Review the environment name and settings, and choose Create environment. Your environment will be provisioned and prepared after several minutes. 

Once ready, your IDE should open with a welcome note. You should now see your AWS Cloud9 environment. 

There are three areas of the AWS Cloud9 screen to know, as illustrated in the following screenshot:

File explorer: On the left side of the screen, this shows a list of the files in your directory. 

File editor: On the upper right portion of your screen, this is where you view and edit files that you’ve selected in the file explorer. 

Terminal: On the lower right portion of the IDE, this is where you run commands to execute code samples.

Plan your model: 

1. Focus on access patterns

 2. Optimize for number of requests to DynamoDB

 3. Don’t fake a relational model

 CleanUp:

 To delete the AWS Cloud9 environment that you used in this lab: Navigate to the AWS Cloud9 console. Choose the DynamoDB Quick Photos environment and choose Delete In the dialog box, type Delete in the box, and choose Delete.
