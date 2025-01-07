# Running-a-Continuous-Deploy-With-AWS-Elastic-Beanstalk

# Lab Overview
One of the highest risk parts of running a software company, in terms of availability concerns, is the risk of a faulty deployment. During deployments, complex systems with multiple parts are actively moving around the delicate parts of many other systems. Deployment risk can be minimized by studying a couple of common approaches to deploying code to running machines. 
In this lab, you will deploy multiple version updates of an application in a load-balanced and auto-scaled environment. The first update is deployed using a simple, low-friction rolling deployment. The second update is deployed using a blue-green deployment where a separate environment is created to run the new version of the application and a DNS cutover switches incoming traffic to the new environment.

# Lab Objectives
Upon completion of this lab, you will be able to: 

Build Elastic Beanstalk applications and environments

Perform rolling deployments on underlying EC2 resources

Perform blue-green deployments with Elastic Beanstalk for zero-downtime updates

Minimize costs by cleaning up after blue-green deploys

# Lab Prerequisites

You should be familiar with:

Basic Amazon EC2 and Virtual Private Cloud (VPC) concepts

The topics covered in the Advanced Deployment Techniques on AWS course are beneficial, but not required

# Lab Environment

Before completing the lab instructions, the environment will look as follows:

![blobid1-fdcfc4fd-56de-411f-aa27-f73a76aa71ce](https://github.com/user-attachments/assets/a38e9370-19ed-4579-b06c-9e339322d9ca)


After completing the lab instructions, the environment should look similar to:

![blobid0-b8f458d9-aee2-4f1a-994c-526ed03c6eff](https://github.com/user-attachments/assets/0fecec19-580c-4e47-be1b-8580f80d84fa)


