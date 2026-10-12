# networkcreep

This is a python script that looks for local devices to the network your connected to
It works only in Linux and depends on netifices to get the IP and network subnet 
Have to install with pip install netifices

## How it works
The script first finds your network's IP subnet, which act as a list of possible IP addresses on the network.
It then pings every IP to check if there's a device on the other end.
After confirming devices on the network, the script fetches the MAC addresses of the found devices from the ARP cache.
