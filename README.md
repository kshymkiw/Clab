# Container Lab Topologies
A place to keep Container Lab topologies for historical purposes and sharing with others

## Installing Containerlab and cloning the repo[^2]
Containerlab has a simple one line command to install it on your system:

    curl -sL https://containerlab.dev/setup | sudo bash -s "all"

Once the setup has been completed you will want to clone the repository

    git clone https://github.com/kshymkiw/clabs.git

Now you can run your topology with containerlab

    sudo containerlab deploy /path/to/.clab.yml file

## Topology Specific Notes

### Arista DataCenter Topology
This is a simple toplogy that can be used as a common base across multiple people and groups.

Some Notes about this toplogy:
1.  The ceos image used for this topology is 4.32.1F[^1].  If you have a different image already imported via Docker, you can change the `image` under each node config in the .clab.yml file
2.  Default ssh login is `admin/admin`
3.  This topology **has** EVPN enabled and configured

[^1]:  ceos image is not provided, you will need to download it from [Arista](https://www.arista.com/en/support/software-download)
[^2]:  More information on [Containerlab](https://containerlab.dev/)
