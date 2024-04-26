# command to check iptable
## iptables is an application that allows a user to configure the firewall functionality built into the Linux kernel
iptables -t filter -L (filter table is used for packet filtering)
#command to check NAT table (The nat table is used for Network address translation.)
iptables -t nat -L
#https://linux-training.be/networking/ch14.html#:~:text=iptables%20tables,-By%20default%20there&text=The%20nat%20table%20is%20used%20for%20address%20translation.&text=The%20mangle%20table%20can%20be,table%20are%20called%20a%20chain.
