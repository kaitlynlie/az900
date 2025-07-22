# Virtual Private Network (VPN)

- encrypted tunnel within another network
- typically deployed to connect two or more private networks to one another over untrusted network
- enable networks to safely and securely share sensitive information

## VPN gateways

type of virtual network gateway

- connect on-premises datacenters to virtual networks through a site-to-site connection
- connect individual devices to virtual networks through a point-to-site connection
- connect virtual networks to other virtual networks through a network-to-network connection

## Types of VPNs

- policy-based VPN: specify statically the IP address of packets that should be encrypted through each tunnel, evaluates every data packet against sets of IP addresses to choose the tunnel where packet will be sent through
- route-based gateway: IPSec tunnels are modeled as network interface or virtual tunnel interface
preferred connection for on-premises devices
    - connections between virtual networks
    - point-to-site connections
    - multisite connections
    - coexistence with Azure ExpressRoute gateway

## High-availability scenarios

- active/standby: planned maintenance or unplanned disruption
- active/active: unique public IP address to each instance, create separate tunnels from on-premise device to each IP address
- ExpressRoute failover: configure VPN gateway as secure failover path for ExpressRoute connection
- zone-redundant gateway: VPN and ExpressRoute gateway can be deployed in zone-redundant configuration, requires different gateway stock keeping units (SKUs) and use standard public IP address over basic public IP address