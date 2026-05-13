# AWS Custom VPC Project

## Overview

This project demonstrates the creation of a custom Virtual Private Cloud (VPC) on AWS with public and private subnets. It includes EC2 instances, Internet Gateway, NAT Gateway, Route Tables, Security Groups, and NGINX web server deployment.

---

## Architecture

* Public Subnet
* Private Subnet
* Internet Gateway
* NAT Gateway
* Route Tables
* Security Groups
* EC2 Instances

---

## Technologies Used

* AWS VPC
* Amazon EC2
* Ubuntu Linux
* NGINX
* NAT Gateway
* Internet Gateway

---

## Project Steps

1. Created custom VPC
2. Created public and private subnets
3. Configured Internet Gateway
4. Configured Route Tables
5. Created NAT Gateway
6. Launched EC2 instances
7. Installed and configured NGINX
8. Verified private subnet internet access using NAT Gateway
---

## Commands Used

### Connect to EC2

```bash
ssh -i key.pem ubuntu@PUBLIC-IP
```

### Install NGINX

```bash
sudo apt update
sudo apt install nginx -y
```

### Start NGINX

```bash
sudo systemctl start nginx
sudo systemctl enable nginx
```

---

## Key Learnings

* AWS Networking Basics
* Public vs Private Subnets
* Secure Cloud Architecture
* EC2 Management
* Linux Administration
* Internet Routing with NAT Gateway

---

## Outcome

Successfully built and tested a secure AWS VPC environment with internet-enabled private subnet architecture.
