# AWS-Elasticbeanstalk-Application

In this project, I created a flask application using Python, HTML, and CSS. The application takes the information that a user puts into the field and pushes it to my DynamoDB table in AWS. Once the information is stored, I am sent a SNS notification via email that new user signed up. The application was deployed on to Elastic Beanstalk and the custom domain was created using Route 53.

Link to Website: https://rjcloud.reggiestestdomain.com/



## Application Breakdown

The application is broken down into the architecture below:

![ebsapp]()



### Frontend

- HTML
- CSS
- [Bootstrap via Bootswatch](https://bootswatch.com/)


### Backend 

- [Python](https://www.python.org/) 
- [Flask (Python Framework)](https://flask.palletsprojects.com/en/1.1.x/)



### DNS

- [Route 53](https://aws.amazon.com/route53/)


### Deployment Platform

- [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)


### Database 

- [DynamoDB](https://aws.amazon.com/dynamodb/)

### Notification Service

- [SNS](https://aws.amazon.com/sns/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc)

