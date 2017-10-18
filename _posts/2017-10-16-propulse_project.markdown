---
title: Propulse Analytics
subtitle: Product recommendation engine for retailers
layout: default
modal-id: propulse_portefolio_1
date: 2017-10-16
img: propulse_banner1.png
thumbnail: propulse_banner-thumb.png
alt: Propulse Analytics
project-date: 2017
client: Stradigi / Propulse Analytics
category: portefolio
client_url: https://www.stradigi.ca/services-2/propulse/
banner_url: http://www.propulseanalytics.com/en/
---

Propulse Analytics offers a recommendation engine for e-commerce retailers.
It uses Machine learning to analyse product's images and customer purchases history in order to determine what the shopper is looking for
and what other products they might want to purchase.

My work in this project is to design and develop the backend service and the recommendation engine that powers this application.
The project can be divided in different sections which are

- The Offline data processing processes.
- The REST Service to the recommendation Engine.
- The Event Processing, that tracks e-commerce events and provides data analytics

The Technologies that I used in this project are:

- **Language**: Python
- **Libraries**: Falcon (WSGI), AWS Boto3, Zappa (for AWS Serverless), Scypy,  NeoModel (Neo4J Model), Celery (Task Queue), Circus (Process and Socket Manager), and more
- **Databases**: Neo4J (GraphDB), ElasticSearch, DynamoDB
- **AWS Services**: API Gateway and Lambda, EC2, S3, IAM, ElasticSearch, Elastic Cache, CloudWatch, VPC, DynamoDB, Cognito, Kinesis FireHose
