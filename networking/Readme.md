# Networking

A short writeup of networking on aws.

## Table of Contents
 - [Notes](#notes)
 - [VPC Endpoints](#vpc-endpoints)

## Notes
  - Architecture images for all entries in: [architecture-images](architecture-images/)

## VPC Endpoints
For our services, if we want to have internet access, we route the traffic via an internet gateway. 

However, there may be cases where we we don't want our network traffic to go through the public internet, we could utilise vpc endpoints, with vpc endpoints, we are able to access aws services via a private network.

>> 
    Supported services are:
    - AWS S3
    - DynamoDB

Below architecture diagram showcases the implementation: 
![vpc-endpints-architecture image](architecture-images/vpc-endpints.drawio.png)

