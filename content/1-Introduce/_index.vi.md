---
title : "Giới thiệu"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 1. </b> "
---

## Giới Thiệu Bài Lab: Triển Khai Pipeline CI/CD Sử Dụng Các Dịch Vụ AWS

 


### 1. Tổng Quan

Trong bài lab này, chúng ta sẽ đi qua quá trình thiết lập một Pipeline Continuous Integration/Continuous Deployment (CI/CD) để triển khai một máy chủ đơn giản bằng cách sử dụng các dịch vụ AWS bao gồm CodeCommit, CodeBuild, CodeDeploy, EC2, CodeDeploy Agent, ECR và Docker.


### 2. Mục Tiêu

Mục tiêu của bài lab này là tự động hóa quá trình triển khai của một ứng dụng máy chủ đơn giản lên một EC2 bằng cách triển khai một pipeline CI/CD. Chúng ta sẽ sử dụng các dịch vụ AWS để quản lý mã nguồn, tạo Docker images và triển khai ứng dụng một cách tự động.


1. [Introduction](1-introduce/)
2. [Preparation](2-prepare/)
3. [ELB](3-codecommit/)
4. [Auto Scaling Group](4-codebuild/)
5. [EC2](5-ec2/)
6. [RDS](6-codedeploy/)
7. [Elasticache](7-codepipeline/)
8. [S3](8-ecr/)
9. [Result](9-test/)
