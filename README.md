# AWS Custom VPC Network

## Project Overview

This project demonstrates the design and configuration of a custom Virtual Private Cloud (VPC) using Amazon Web Services (AWS).

## Architecture

Internet
   |
Internet Gateway
   |
Public Subnet
   |
Public Route Table

VPC: 10.0.0.0/16
|
|-- Public Subnet
|
|-- Private Subnet
|
|-- Public Subnet (Second Availability Zone)

## Configuration

- VPC CIDR: 10.0.0.0/16
- Cloud Platform: AWS
- Region: US West (Oregon) - us-west-2
- Public Subnets: 2
- Private Subnets: 1
- Internet Gateway: Configured
- NAT Gateway: Not configured
- Public Route Table: Configured
- Private Route Table: Configured

## Key Concepts

- Amazon VPC
- CIDR Blocks
- Subnets
- Availability Zones
- Internet Gateway
- Route Tables
- Public and Private Networking
- Network ACLs
- Cloud Network Security

## Project Outcome

Successfully created and verified a custom AWS VPC with separate public and private network segments. The AWS Skill Builder assessment was also successfully completed with a score of 83%.

## Tools Used

- Amazon Web Services (AWS)
- AWS Skill Builder
- Amazon VPC Console
