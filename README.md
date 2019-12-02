Ansible learning project



Task :

In a greenfield environment we need to implement network as code
we will be using git hub as the source of truth.
using ansibles to deploy the network.
using git and ansibles to make changes as and when such requirements may come up.


Steps :

1) Configure spoke 1 site.

- configure interfaces
- configure default route to ISP
- router on a stick -- vlan 1, 10, 100
- configure ip sla
- configure hsrp with track
- configure nat

2) add spoke two site.
