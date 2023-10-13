![[Pasted image 20231012175606.png]]

- EC2 have security Groups
- Subnets have Network ACL (NACL)
- VPC needs an internet gateway to connect with the internet
- Subnets also have a route table

[Refer Route Table vs NACL](https://stackoverflow.com/questions/60211533/what-is-the-diference-between-network-acl-and-route-tables-in-aws)


- Private subnets are connected to the internet using ==NAT Gateway==
