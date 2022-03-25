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

### Quick Hits: IP Networking Chart
##### Class A IP Addresses

| Network Bits | Subnet Mask |	Number of Subnets |	Number of Hosts |
| -            | -           | -                  | -               |
|/8 |	255.0.0.0 |	 0 |	16777214 |
|/9 |255.128.0.0|  2 (0)| 	8388606|
|/10 |	255.192.0.0| 4 (2)| 	4194302|
|/11 |	255.224.0.0| 	8 (6)| 	2097150|
|/12 |	255.240.0.0| 	16 (14)| 	1048574|
|/13 |	255.248.0.0| 	32 (30)| 	524286|
|/14 |	255.252.0.0| 	64 (62)| 	262142|
|/15 |	255.254.0.0| 	128 (126)| 	131070|
|/16 |	255.255.0.0| 	256 (254)| 	65534|
|/17 |	255.255.128.0| 	512 (510)| 	32766|
|/18 |	255.255.192.0| 	1024 (1022)| 	16382|
|/19 |	255.255.224.0| 	2048 (2046)| 	8190|
|/20 |	255.255.240.0| 	4096 (4094)| 	4094|
|/21 |	255.255.248.0| 	8192 (8190)| 	2046|
|/22 |	255.255.252.0| 	16384 (16382)| 	1022|
|/23 |	255.255.254.0| 	32768 (32766)| 	510|
|/24 |	255.255.255.0| 	65536 (65534)| 	254|
|/25 |	255.255.255.128| 	131072 (131070)| 	126|
|/26 |	255.255.255.192| 	262144 (262142)| 	62|
|/27 |	255.255.255.224| 	524288 (524286)| 	30|
|/28 |	255.255.255.240| 	1048576 (1048574)| 	14|
|/29 |	255.255.255.248| 	2097152 (2097150)| 	6|
|/30 |	255.255.255.252| 	4194304 (4194302)| 	2|

##### Class B IP Addresses
| Network Bits | Subnet Mask |	Number of Subnets |	Number of Hosts |
| -            | -           | -                  | -               |
|/16| 	255.255.0.0| 	0 	65534
|/17| 	255.255.128.0| 	2 (0)| 	32766|
|/18| 	255.255.192.0| 	4 (2)| 	16382|
|/19| 	255.255.224.0| 	8 (6)| 	8190|
|/20| 	255.255.240.0| 	16 (14)| 	4094|
|/21| 	255.255.248.0| 	32 (30)| 	2046|
|/22| 	255.255.252.0| 	64 (62)| 	1022|
|/23| 	255.255.254.0| 	128 (126)| 	510|
|/24| 	255.255.255.0| 	256 (254)| 	254|
|/25| 	255.255.255.128| 	512 (510)| 	126|
|/26| 	255.255.255.192| 	1024 (1022)| 	62|
|/27| 	255.255.255.224| 	2048 (2046)| 	30|
|/28| 	255.255.255.240| 	4096 (4094)| 	14|
|/29| 	255.255.255.248| 	8192 (8190)| 	6|
|/30| 	255.255.255.252| 	16384 (16382)| 	2|

##### Class C IP Addresses
| Network Bits | Subnet Mask |	Number of Subnets |	Number of Hosts |
| -            | -           | -                  | -               |
|/14| 	255.252.0.0| 	1024| 	262144|
|/15| 	255.254.0.0| 	512| 	131072|
|/16| 	255.255.0.0| 	256| 	65536|
|/17| 	255.255.128.0| 	128| 	32768|
|/18| 	255.255.192.0| 	64| 	16384|
|/19| 	255.255.224.0| 	32| 	8192|
|/20| 	255.255.240.0| 	16| 	4096|
|/21| 	255.255.248.0| 	8| 	2048|
|/22| 	255.255.252.0| 	4| 	1024|
|/23| 	255.255.254.0| 	2| 	512|

## 🧰 Tools
[IP Calculator](https://jodies.de/ipcalc) - ipcalc takes an IP address and netmask and calculates the resulting broadcast, network, Cisco wildcard mask, and host range.

## 📚 References
https://www.techtarget.com/searchnetworking/tip/IP-addressing-and-subnetting-Calculate-a-subnet-mask-using-the-hosts-formula
https://www.softwaretestinghelp.com/subnet-mask-and-network-classes/
https://avinetworks.com/glossary/subnet-mask/
