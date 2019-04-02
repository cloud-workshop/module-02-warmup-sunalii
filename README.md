# Building a Simple Network on AWS

This is a warmup exercise for module 02 which can be found here.
https://github.com/aws-samples/aws-modern-application-workshop/tree/python/module-2

It requires you to know the basics of AWS networking. 

## Your Assignment
1. Create a VPC
2. Create a Public Subnet with an Internet Gateway attached
3. Create a Private Subnet with an NAT gateway attached
4. Spin up a server in the public subnet that outputs "Hello World"
5. Visit the server using the IP/DNS to see "Hello World" message
6. Spin up another server in the Private subnet
7. SSH into it using SSH port forwarding
8. Run "yum update -y" and download updates in the server 

## Deliveries
1. Public IP of the Web Server
2. Screenshot of the "Hello World" message with the public ip on the address bar
3. Private IP of the Web Server

## Cleanup - Do this to avoid unwanted bills from AWS
1. Stop the EC2 instances
2. Delete the NatGateway
3. Delete the Internet Gateway
4. Release Elastic IP associated with the Internet Gateway

## References 
1. AWS VPC - https://www.youtube.com/watch?v=kdkulaBWyXw
2. Security Groups and NACL in VPC - https://www.youtube.com/watch?v=pac2SZfSfzk
3. Creating a VPC - https://youtu.be/iZonf_XhMpY
4. Security Groups and Launching Instances - https://youtu.be/85COkRLRw98
5. SSH Agent Forwarding - https://youtu.be/cHg6LWOzH98
6. NAT Gateways vs NAT Instaces -https://youtu.be/un4vD6WCEJM

Create an Issue with the Deliveries. 
Deadline - 9th April 2019
