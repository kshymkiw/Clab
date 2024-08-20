# Container Lab Topologies
A place to keep Container Lab topologies for historical purposes and sharing with others

### Arista Common Topology
This is a simple toplogy that can be used as a common base across multiple people and groups.

Some Notes about this toplogy:
1.  The ceos image used for this topology is 4.32.1F[^1].  If you have a different image already imported via Docker, you can change the `image` under each node config in the .clab.yml file
2.  Default ssh login is `admin/admin`
3.  This topology **has** EVPN enabled and configured

### Clone Topologies
` git clone https://github.com/kshymkiw/clabs.git `

[^1]:  ceos image is not provided, you will need to download it from [Arista](https://www.arista.com/en/support/software-download)
