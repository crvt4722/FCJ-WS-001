---
title : "Preparation Steps"
date :  "`r Sys.Date()`" 
weight : 2
chapter : false
pre : " <b> 2. </b> "
---

#### Preparation Steps

1. Ensure Your AWS Account Has permission to access EC2, S3, RDS, Elasticache, ... resources.
2. Gen the AWS credentials of working user for access AWS resources with SDK.
3. Build simple source code to achive these goals: 
    - Static files of the website are stored on *AWS S3*
    - Data of the website are stored on *AWS RDS*
    - Cache of the website are stored on *AWS Elasticache*

4. Containerize the web application to *Docker image* and push it to *Docker hub*. 