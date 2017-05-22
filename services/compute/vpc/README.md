# VPC

---

## Practical Notes

### *VPC Peering and CloudAMQP VPC*
- https://www.cloudamqp.com/blog/2014-11-14-amazon-vpc-peering.html

### *VPC Peering*
- http://blog.celingest.com/en/2014/05/09/introduction-aws-vpc-peering/

### *Security*
- http://cloudacademy.com/blog/aws-bastion-host-nat-instances-vpc-peering-security/



---

## Documentation Notes

### *Basics*
### *VPC and Subnets*
### *Default VPC and Subnets*
### *Security in VPC*
### *Networking in VPC*

#### *IP Addressing*
#### *Network Interfaces*
#### *Route Tables*
#### *Internet Gateways*
#### *NAT*
#### *DHCP Option Sets*
#### *DNS*
#### *VPC Peering*

A network connection between two VPCs that enables traffic routing in-between using private IP addresses allowing instances to communicate as if within the same network.

##### *Basics*

###### *Connection Lifecycle*

- Initiating-Request: request for VPC peering connection initiated; can _fail_ or _pending-acceptance_.
- Failed: request for VPC peering connection failed; cannot be accepted or rejected.
- Pending-Acceptance: VPC peering connection request awaiting acceptance from owner of peer VPC; owner can delete, accept or reject request.
- Expired: request expired and no action can be taken on it.
- Rejected: owner of VPC rejected _pending-acceptance_ connection request.
- Provisioning: request has been accepted moving into _active_ state.
- Active: VPC peering connection is active.
- Deleted: _active_ peering connection has been deleted by either owner or _pending-acceptance_ request has been deleted.

###### *Limitations*

- Cannot create a peering connection that have matching or overlapping IPv4 or IPv6 CIDR blocks.
- VPCs must be in same region.
- Number of active or pending connections limited per VPC.
- Transitive peering relationships not supported; one-to-one connections only.
- Only one peering connection between same two VPCs
- A placement group can span peered VPCs without full-bisection bandwidth between instances in peered VPCs.
- Unicast reverse path forwarding in VPC peering connections not supported.
- IPv6 communication between enabled resources on either side of connection not automatic.

##### *Working with VPC Peering Connections*

###### *Creation and Acceptance*
###### *Rejection*
###### *Update Route Tables*
###### *Reference VPC Security Groups*
###### *Modify Peering Options*
###### *Deletion*
###### *Controlling Access to VPC Peering Connections*

##### *VPC Peering Scenarios*
##### *VPC Peering Configurations*
##### *Invalid VPC Peering Connection Configurations*

#### *VPC Endpoints*

### *VPN Connections*
### *Dedicated Instances*
### *ClassicLink*
### *VPC Limits*

---

## Infrastructure as Code Examples

### *AWS CLI*

- http://docs.aws.amazon.com/cli/latest/reference/ec2/index.html

| Command        | Options      | Example  |
| :-------------:|------------- | :-----:  |
| accept-vpc-peering-connection | ---- | ---- |
| associate-vpc-cidr-block | ---- | ---- |
| attach-classic-link-vpc | ---- | ---- |
| create-vpc | ---- | ---- |
| create-vpc-endpoint | ---- | ---- |
| create-vpc-peering-connection | ---- | ---- |
| delete-vpc | ---- | ---- |
| delete-vpc-endpoints | ---- | ---- |
| delete-vpc-peering-connection | ---- | ---- |
| describe-vpc-attribute | ---- | ---- |
| describe-vpc-classic-link | ---- | ---- |
| describe-vpc-classic-link-dns-support | ---- | ---- |
| describe-vpc-endpoint-services | ---- | ---- |
| describe-vpc-endpoints | ---- | ---- |
| describe-vpc-peering-connections | ---- | ---- |
| describe-vpcs | ---- | ---- |
| detach-classic-link-vpc | ---- | ---- |
| disable-vpc-classic-link | ---- | ---- |
| disable-vpc-classic-link-dns-support | ---- | ---- |
| disassociate-vpc-cidr-block | ---- | ---- |
| enable-vpc-classic-link | ---- | ---- |
| enable-vpc-classic-link-dns-support | ---- | ---- |
| modify-vpc-attribute | ---- | ---- |
| modify-vpc-endpoint | ---- | ---- |
| modify-vpc-peering-connection-options | ---- | ---- |
| move-address-to-vpc | ---- | ---- |
| reject-vpc-peering-connection | ---- | ---- |

### *NodeJS*

### *Terraform*
