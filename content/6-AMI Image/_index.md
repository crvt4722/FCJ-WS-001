---
title : " AMI"
date :  "`r Sys.Date()`" 
weight : 6
chapter : false
pre : " <b> 6. </b> "
---

An Amazon Machine Image (AMI) is a pre-configured template that contains the necessary information to launch a virtual machine, known as an instance, within Amazon Elastic Compute Cloud (EC2). An AMI includes details such as the operating system, application server, and applications that are required to launch and run an instance. Use AMIs to quickly deploy new instances with pre-configured environments for your applications.

### Create AMI Image 
In this part, I will create an AMI Image from EC2 instance run web server before. When we create AMI Image from web server successfully, we can use this image to create EC2 instance run web server back without setting up anymore.  