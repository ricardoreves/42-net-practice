# 42-net-practice

## 🪧 Overview
🌐 NetPractice aims to introduce you to the network through practical cases.

## 🚀 Getting Started
1. Click [here](https://ricardoreves.github.io/42-net-practice/) to start the exercices
2. Complete the empty fields and press `Check again` to check if the network is working
3. Once the exercise is successful, click on `Get my config` to download a network config file

## 🧠 Understanding IP Addressing
### Easy-to-understand binary values
```
Address:   192.168.0.1           11000000.10101000.00000000 .00000001
Netmask:   255.255.255.0 = 24    11111111.11111111.11111111 .00000000
Wildcard:  0.0.0.255             00000000.00000000.00000000 .11111111
=>
Network:   192.168.0.0/24        11000000.10101000.00000000 .00000000 (Class C)
Broadcast: 192.168.0.255         11000000.10101000.00000000 .11111111
HostMin:   192.168.0.1           11000000.10101000.00000000 .00000001
HostMax:   192.168.0.254         11000000.10101000.00000000 .11111110
Hosts/Net: 254                   (Private Internet)
```
## 🧰 Tools
[IP Calculator](https://jodies.de/ipcalc) - ipcalc takes an IP address and netmask and calculates the resulting broadcast, network, Cisco wildcard mask, and host range.

## 📚 References
https://www.techtarget.com/searchnetworking/tip/IP-addressing-and-subnetting-Calculate-a-subnet-mask-using-the-hosts-formula
https://www.softwaretestinghelp.com/subnet-mask-and-network-classes/
