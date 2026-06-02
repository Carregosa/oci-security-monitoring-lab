# Lab Architecture

## Overview

This lab uses a simple Oracle Cloud Infrastructure architecture focused on cloud fundamentals, security awareness and operational visibility.

## Components

The architecture includes the following OCI components:

- OCI Compartment
- Virtual Cloud Network
- Public Subnet
- Private Subnet
- Internet Gateway
- Security Rules
- Compute Instance
- Object Storage Bucket
- Monitoring Metrics
- Logging Resources

## Logical Architecture

User  
↓  
Internet  
↓  
Internet Gateway  
↓  
Public Subnet  
↓  
OCI Compute Instance  
↓  
Monitoring and Logging  
↓  
Object Storage Bucket

## Network Design

The network foundation is based on a Virtual Cloud Network with the following CIDR block:

- VCN: 10.0.0.0/16
- Public Subnet: 10.0.1.0/24
- Private Subnet: 10.0.2.0/24

The public subnet provides controlled internet connectivity through the Internet Gateway.

## Security Approach

The lab applies basic security principles:

- Resource organization through a dedicated compartment.
- Controlled network exposure.
- Review of ingress and egress rules.
- Administrative access restricted whenever possible.
- No sensitive information exposed in screenshots.
- Monitoring and logging enabled for operational visibility.

## Oracle Cloud Services Used

- Oracle Cloud Infrastructure
- OCI Networking
- OCI Compute
- OCI Object Storage
- OCI Monitoring
- OCI Logging

## Purpose

The purpose of this architecture is to demonstrate practical Oracle Cloud Infrastructure product usage in a simple, secure and educational way.

This architecture supports the Oracle ACE Apprentice Product Usage milestone by showing a documented and repeatable OCI lab environment.
