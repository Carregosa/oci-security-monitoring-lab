# Step-by-Step Guide

## 1. Create OCI Compartment

A dedicated compartment was created to organize all resources used in this lab.

Compartment name: ACE-OCI-LAB

## 2. Create Virtual Cloud Network

A Virtual Cloud Network was created to provide the network foundation for the lab.

VCN name: ace-oci-vcn

## 3. Configure Public Subnet and Internet Gateway

A public subnet and internet gateway were configured to allow controlled internet connectivity.

Public subnet: public-subnet  
CIDR block: 10.0.1.0/24

Private subnet: private-subnet  
CIDR block: 10.0.2.0/24

## 4. Review Security Rules

Security rules were reviewed to allow only the required traffic for the lab environment.

Recommended ports:

- TCP 22 SSH
- TCP 80 HTTP
- TCP 443 HTTPS

## 5. Create Compute Instance

An Oracle Linux Compute instance was created to demonstrate basic compute usage in OCI.

Instance name: ace-oci-compute-lab

## 6. Create Object Storage Bucket

An Object Storage bucket was created to demonstrate basic storage usage.

Bucket name: ace-oci-lab-bucket

## 7. Review Monitoring Metrics

Compute metrics were reviewed to observe CPU, network and resource activity.

Metrics reviewed:

- CPU Utilization
- Network Bytes In
- Network Bytes Out
- Disk Activity

## 8. Review Logging

OCI Logging and observability resources were reviewed as part of the operational visibility process.

## 9. Capture Evidence

Screenshots were captured from the OCI Console and uploaded to this repository.

Evidence folder: /images

## 10. Community Value

This lab provides a simple and practical learning path for professionals starting with Oracle Cloud Infrastructure.
