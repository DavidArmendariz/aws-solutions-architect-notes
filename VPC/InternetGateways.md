# Internet Gateways

* Internet gateways helps our VPC instances connect with the internet
* It scales horizontally and is HA and redundant
* Must be created separately from VPC
* One VPC can only be attached to one IGW and viceversa
* Internet Gateway is also a NAT for the instances that have a public IPv4
* Internet Gateways on their own do not allow internet access
* Route tables must also be edited!

![IG](images/IG.png)
![Router](images/Router.png)
