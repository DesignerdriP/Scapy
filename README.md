
Simpliest and easiest way to send a packet throught local or global network.
Open up python and install scapy with pip or sudo. 

pip install https://github.com/secdev/scapy 

sudo clone https://github.com/secdev/scapy

Open up Wireshark - https://www.wireshark.org/download.html and start scanning the network 

ex: source=192.168.1.1 //destination=192.168.1.73 above to see indicated word(s) displayed 

Once you got scapy isntalled just type in scapy in python, after that all you need to do is type in following code, filling in IP addresses source and destination

send(IP(src=""xxx.xxx.x.x",dst="xxx.xxx.x.x")/ICMP()/"The world is yours")

Run code 
