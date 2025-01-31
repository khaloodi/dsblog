---
layout: post
title: Securing your VPC using Public and Private Subnets
subtitle: "VPC with public and private subnets"
---
### 📅 Schedule A Meeting:
- [Consultation & Project Scoping](https://calendly.com/kadad1312/1-on-1?back=1&month=2024-01)

In the associated lab we will step through how to secure your VPC using public and private subnets. The goal of this lab is to become more familiar with VPC and general networking concepts in AWS.
### Video Explanation:

[![IMAGE_ALT](/img/vpc_with_pub_priv_subnets.png)](https://www.youtube.com/watch?v=ODg9o7B_TFw&t=3s)

A Virtual Private Cloud (VPC) in Amazon Web Services (AWS) allows users to create a virtual network in the cloud, isolated from the rest of the internet. One way to increase the security of a VPC is by using both public and private subnets.

A public subnet is a subnet that has a direct connection to the internet, typically through an Internet Gateway (IGW). This subnet is used for resources that need to be accessible from the internet, such as a web server.

A private subnet, on the other hand, does not have a direct connection to the internet and is used for resources that do not need to be publicly accessible, such as a database.

By using both public and private subnets, the risk of a security breach is greatly reduced. For example, if a hacker were to gain access to a resource in a public subnet, they would not have access to the resources in the private subnet.

Additionally, it is a best practice to use a Network Address Translation (NAT) gateway or a NAT instance in the public subnet to allow outbound internet access for resources in the private subnet. This way, resources in the private subnet can access the internet for updates and patches, but incoming traffic from the internet is blocked.

In summary, using both public and private subnets in a VPC can greatly increase the security of your resources in AWS. By isolating internet-facing resources from those that do not need to be publicly accessible, and by using a NAT gateway or NAT instance, the risk of a security breach is greatly reduced.

### Make 💰 By Learning Programming:
- [Tesla](https://ts.la/khaled835973)
- [Liquid I.V. Hydration Multiplier 30 Stick, 16.93 Ounce](https://amzn.to/3ZFDjDq)
- [Xeela Pre workout](https://amzn.to/3NXWwMD)
- [Sour Strips](https://amzn.to/3EDWUM7)
- [Impractical Python Projects](https://amzn.to/3JpCpWH)
- [Designing Data-Intensive Applications](https://amzn.to/3Hgh5Sj)
- [Python for Data Analysis](https://amzn.to/3D0C8pl)
- [Python for Data Science Handbook](https://amzn.to/3XnZ1ez)
- [Hands-On Machine Learning w/Scikit-Learn & Tensorflow](https://amzn.to/3QTWoyt)

<br>