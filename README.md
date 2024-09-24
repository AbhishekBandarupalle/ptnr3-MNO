# Siteconfig and Policygen templates for ptnr3-cluster

## Siteconfig
Siteconfig deploys a multinode cluster with 3 nodes,consisting of <br>
 - 3 Master nodes(ranworkers) and <br> 
 (- 2 Worker nodes(ceph02 and ceph03 nodes)to be added if needed) <br> 

The different interfaces used are:
* ens10f0:
	- IPv4 Subnet: `192.168.74.128/26`
	- VLAN 2310: Machine Network and used for OVN<br> 
