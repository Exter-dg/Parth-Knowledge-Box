***

## Private IP Address Classes

| Class | IP Address Range              | Default [[Subnet]] Mask | Available Bits (Addressable) | CIDR(Classless Inter-Domain Routing) Notation |
| ----- | ----------------------------- | ----------------------- | -------------- | -------------- |
| A     | 10.0.0.0 - 10.255.255.255     | 255.0.0.0               | 24             | 10.0.0.0/8     |
| B     | 172.16.0.0 - 172.31.255.255   | 255.240.0.0             | 20             | 172.16.0.0/12  |
| C     | 192.168.0.0 - 192.168.255.255 | 255.255.0.0           | 16              | 192.168.0.0/24               |


> [!note] The ==/8== in IP Address range is used to indicate the associated [[subnet]] mask
> It means that the first 8 bits in the 32-bit IP Address is used for network identification and the rest 24 bits are addressable (usable) addresses.
> 
  