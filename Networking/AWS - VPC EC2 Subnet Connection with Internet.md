![[Pasted image 20231012175606.png]]

- EC2 have security Groups
- Subnets have Network ACL (NACL)
- VPC needs an internet gateway to connect with the internet
- Subnets also have a route table

[Refer Route Table vs NACL](https://stackoverflow.com/questions/60211533/what-is-the-diference-between-network-acl-and-route-tables-in-aws)


- Private subnets are connected to the internet using ==NAT Gateway==


## Security Groups

- Inbound rules control ==who can access the EC2 instance from OUTSIDE==
- Outbound rules control who can the ec2 instance access.
  
  An inbound rule at port 22 and NO outbound rules, allows an SSH connection with the EC2 instance. 
