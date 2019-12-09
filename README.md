Ansible learning project

![Topology Diagram]

(https://github.com/htulshan/ansible_learing_curve/blob/master/topology_diagram.png)
ignore the cloud in the middle and all connections going to it, it is for management access of the devices.

Task :

In a greenfield environment we need to implement network as code
we will be using git hub as the source of truth.
using ansibles to deploy the network.
using git and ansibles to make changes as and when such requirements may come up.


Steps :

1) Configure spoke 1 site.

- configure interfaces
- configure default route to ISP
- configure ip sla and track
- configure hsrp with track

2) add spoke two site.

3) configure hub site.
- configure bgp to ISP.
- configure dmvpn phase 2 without ipsec.
- configure EIGRP over the tunnel to spoke.

4) Configure NAT on all the CE routers.


Project complete.
