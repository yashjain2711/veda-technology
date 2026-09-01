# Internship Task 1 - Deploy Virtual Machine in Cloud

## Objective

Deploy a virtual machine on AWS EC2, install Nginx
and make the web server accessible through the Internet.

## Cloud Provider

AWS

## Services Used

- Amazon EC2
- Security Groups
- Public IPv4
- SSH
- Nginx

## Architecture

Internet
   |
   | HTTP :80
   |
AWS EC2
   |
Nginx
   |
Web Page

## EC2 Configuration

OS: Ubuntu 24.04 LTS
Web Server: Nginx

## Security Group

| Protocol | Port | Source |
|----------|------|--------|
| SSH      | 22   | My IP  |
| HTTP     | 80   | 0.0.0.0/0 |

## Deployment Steps

1. Created EC2 instance
2. Configured security group
3. Connected using SSH
4. Installed Nginx
5. Created custom web page
6. Tested using public IP

## Rollback

The EC2 instance can be stopped when not required.
For complete cleanup, the instance can be terminated.

## Interview Questions

### Public vs Private IP

...

### SSH Security

...

### Stop vs Terminate

...