# WordPress-on-AWS-EC2
My first project to go live that I did for my first client - my wife, lol.  This is for her website which is currently live and you can check it out on the link below:

https://www.laurian.co.za/

This guide walking through how I set up a secure and scalable WordPress web server on an Amazon EC2 instance running Amazon Linux 2023. It includes: 
~ Apache + PHP + MySQL setup  
~ SSL via Let's Encrypt  
~ Daily backups uploaded to S3   
~ Backup integrity check  
~ File permission hardening   
~ Health checks with optional AWS SNS alerts


Table of Contents
Provision EC2 Instance

Install MySQL Server

Set Up Apache + PHP + WordPress

MySQL Database and User Setup

Configure wp-config.php

Install SSL with Let's Encrypt

Secure File Permissions

Automate Backups & Upload to S3

Health Checks & Monitoring

Architecture Diagram
