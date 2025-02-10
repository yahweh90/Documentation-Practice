# Sun Wu Kong Gattsu

A honeypot is a security mechanism used in cybersecurity to detect, deflect, or counteract attempts at unauthorized use of information systems. 
It typically consists of a computer, data, or network site that appears to be part of a legitimate network but is actually isolated and monitored, 
with the intention of attracting and observing malicious activity.



## Prerequisites
- An AWS account
- Basic understanding of the [Agile Manifesto](https://agilemanifesto.org/iso/en/principles.html)
- Basic understanding of Github and git
- LoneWolfXiaolin [Here](https://www.youtube.com/@LoneWolfXiaolin)



## Step 1: Create an instance; choose an Amazon Machine Image (AMI)
1. Open the [AWS Management Console](https://aws.amazon.com/console/) and navigate to the EC2 service.
2. Click on **Launch Instance**. Name it. I will call mine “honey_im_home”.
3. Select an AMI from the list based on your requirements. For this guide, we'll use the [Debian 11 AMI]( https://aws.amazon.com/marketplace/pp/prodview-l5gv52ndg5q6i#pdp-overview).


<img src= "https://github.com/yahweh90/Documentation-Practice/blob/main/ab67616d0000b2738ade51c44964e23068d8fd2c.jpg" style="width:500px;">


## Step 5: Update and upgrade OS
We want to ensure that the proper patches are up to date on this instance, so we will run this command in the terminal first.
```bash
git clone https://github.com/telekom-security/tpotce.git
```
