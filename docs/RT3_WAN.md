# **simple Cisco IOS Router WAN**

## **Overview**
Simple WAN Network Configurations with 3 Cisco IOS Routers (CSR 1000v).

## **Features**
* IOS device facts
* Interface configuration (description, admin status)
* L3 IPv4 configuration
* BGP configuration (WAN)
* Testing, verification and rollbacks

## **Usage**
First create 
* ansible-playbook -i inventory/aws_rt3_wan.inv provision.yml 
* ansible-playbook -i lab.aws_ec2.yml post.yml 

## **Topology**

[WAN](RT3_WAN.jpg)

## **Prerequests**
* AWS Account 
* Subscription for IOS CSR 1000v BYOL 
* Subscription for RHEL BYOL
* Subscription for CentOS

pip:
* ansible > 2.9             
* ansible-tower-cli  
* boto3
* botocore

