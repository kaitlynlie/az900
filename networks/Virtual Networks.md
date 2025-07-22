# Virtual Networks

enable Azure resources to communicate

Isolation and segmentation: multi-isolated virtual networks

Service endpoints: connect to other Azure resource types

## On-premises resources:

- point-to-site virtual private network connections: from computer outside organization back to corporate network → client PC initiates encrypted VPN connection to connect to Azure virtual network
- site-to-site virtual private network links on-premises VPN to Azure VPN in virtual network
- Azure ExpressRoute: provides dedicated private connectivity to Azure, not over internet

## Route network traffic

- route tables: define rules about how traffic should be directed, create custom route tables to control how packets are routed between subnets
- Border Gateway Protocol (BGP): works with Azure VPN gateways, Azure Route Server, Azure ExpressRoute to propagate on-premises BGP routes to Azure virtual networks

## Filter network traffic

- Network security groups: Azure resources that contain multiple inbound/outbound security rules, can allow/block traffic based on factors like source, destination IP address, port, protocol

## Connect virtual networks

- peering: two virtual networks to connect directly to each other, private, travels on Microsoft backbone network, doesn’t leave public internet
- user-defined routes (UDR): control routing tables between subnets within virtual network or between virtual networks