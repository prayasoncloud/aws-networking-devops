
# Aws Networking Services For DevOps,

About 40 networking services are available on Amazon, but do I as a DevOps need to learn about them all?

You cannot master every service as soon as you begin learning DevOp. I have therefore prepared a list of the services by doing research and projects. you must study these because they will appear along your DevOps journey.

Aside from Network Administrator, a deep dig into AWS networking services is a waste of time because companies like AWS offer services where they are solely in charge of the back end, which is kind of nice. I also don’t believe that individuals start learning binary codes when it comes to AI.

Let’s get started; I’ll also give you an overview of each service in this single blog post. This is the list

1.  VPC Basics
2.  ELB/ CloudFront
3.  Route53
4.  VPC Endpoints
5.  Private Link
6.  VPC Peering
7.  Transit VPC
8.  Transit Gateway
9.  Site to Side VPN
10.  Client VPN

![A diagram to help you understand where each service is used.](https://miro.medium.com/v2/resize:fit:700/1*Q4deP4_vxBTURioUjZYW4A.png)

**VPC**

Users can logically create their personal network, designing and implementing a separate and independent network that would operate in the AWS Cloud.

The primary components are:

`_Subnets_`_,_ `_IP addresses_`_,_ `_NAT Devices (Instances & Gateways)_`_,_ `_Route Tables_`_,_ `_Internet & Virtual Private Gateways_`_,_ `_Access Control Lists_`_,_ `_Security groups_`_,_ `_VPC Endpoints_`

**ELB/ CloudFront**

Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets and virtual appliances in one or more Availability Zones (AZs).

Amazon CloudFront is a content delivery network (AWS CDN) that retrieves data stored in the Amazon S3 bucket and distributes it to numerous edge locations across the world. Edge locations are the network of data centers distributed worldwide through which content is delivered.

**Route53**

Amazon Route 53 is a DNS (Domain Name Server), which is high availability and can be scaled according to the requirements. DNS is a distributed service that is present all over the world, that helps people use the internet.

**VPC Endpoints**

VPC endpoint enables the creation of a private connection between VPC to supported AWS services and VPC endpoint services powered by PrivateLink using its private IP address. Traffic between VPC and AWS service does not leave the Amazon network.

There are two types of VPC endpoints:

-   _interface endpoints_
-   _gateway endpoints_

**Private Link**

AWS PrivateLink provides private connectivity between virtual private clouds (VPCs), supported AWS services, and your on-premises networks without exposing your traffic to the public internet

Please don’t get confused with VPC Endpoints and Private Link, VPC endpoint is the entry point in your VPC that enables you to connect privately to a service while AWS PrivateLink is a technology that provides private connectivity between VPCs and services.

**VPC Peering**

VPC Network Peering connects two VPC networks so that resources in each network can communicate with each other.

**Transit VPC**

To construct a worldwide network transit center, it is standard procedure to connect many, geographically scattered VPCs and remote networks using transit VPCs.
