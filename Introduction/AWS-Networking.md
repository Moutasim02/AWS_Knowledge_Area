## Connectivity to AWS
- To accesss Amazon Virtual Private Cloud (VPC) you need a virtual private gateway
- Before entering the virtual private gateway we use AWS Direct Connect
- AWS Direct Connect is a service that lets you to establish a dedicated private connection between your data center and a VPC.

## Subnets and Network Access Control Lists

- Public subnet have access to the internet gateway while private do not.
- Security group have default behviour of rejecting all traffic.
- Security group is stateful.

## Global Networking

- Route 53 is AWS own DNS service.