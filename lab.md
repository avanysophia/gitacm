mtech@programminglab:~/Desktop$ ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: enp1s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP group default qlen 1000
    link/ether d0:ad:08:55:ae:31 brd ff:ff:ff:ff:ff:ff
    inet 10.10.1.81/16 brd 10.10.255.255 scope global dynamic noprefixroute enp1s0
       valid_lft 25767sec preferred_lft 25767sec
    inet6 fe80::2f75:6593:32da:359c/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
mtech@programminglab:~/Desktop$ sudo nmap -A 127.0.0.1/8
[sudo] password for mtech: 
sudo: nmap: command not found
mtech@programminglab:~/Desktop$ sudo nmap -A 127.0.0
sudo: nmap: command not found
mtech@programminglab:~/Desktop$ sudo nmap -A 127.0.0.
sudo: nmap: command not found
mtech@programminglab:~/Desktop$ sudo nmap -A 
sudo: nmap: command not found
mtech@programminglab:~/Desktop$ sudo nmap -A 10.10.1.87
sudo: nmap: command not found
mtech@programminglab:~/Desktop$ sudo nmap -A 10.10.1.87
sudo: nmap: command not found
mtech@programminglab:~/Desktop$ sudo apt instal nmap
E: Invalid operation instal
mtech@programminglab:~/Desktop$ sudo apt install nmap
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages were automatically installed and are no longer required:
  amd64-microcode bpfcc-tools bpftrace ieee-data intel-microcode iucode-tool
  libbpfcc libclang-cpp18 libclang1-18 libllvm18 python3-bpfcc python3-netaddr
  thermald ubuntu-kernel-accessories
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  liblinear4 libssh2-1t64 nmap-common
Suggested packages:
  liblinear-tools liblinear-dev ncat ndiff zenmap
The following NEW packages will be installed:
  liblinear4 libssh2-1t64 nmap nmap-common
0 upgraded, 4 newly installed, 0 to remove and 254 not upgraded.
Need to get 6,049 kB of archives.
After this operation, 26.7 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu noble/universe amd64 liblinear4 amd64 2.3.0+dfsg-5build1 [42.3 kB]
Get:2 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 libssh2-1t64 amd64 1.11.0-4.1ubuntu0.24.04.2 [120 kB]
Get:3 http://archive.ubuntu.com/ubuntu noble/universe amd64 nmap-common all 7.94+git20230807.3be01efb1+dfsg-3build2 [4,192 kB]
Get:4 http://archive.ubuntu.com/ubuntu noble/universe amd64 nmap amd64 7.94+git20230807.3be01efb1+dfsg-3build2 [1,694 kB]
Fetched 6,049 kB in 1s (10.6 MB/s)
Selecting previously unselected package liblinear4:amd64.
(Reading database ... 229176 files and directories currently installed.)
Preparing to unpack .../liblinear4_2.3.0+dfsg-5build1_amd64.deb ...
Unpacking liblinear4:amd64 (2.3.0+dfsg-5build1) ...
Selecting previously unselected package libssh2-1t64:amd64.
Preparing to unpack .../libssh2-1t64_1.11.0-4.1ubuntu0.24.04.2_amd64.deb ...
Unpacking libssh2-1t64:amd64 (1.11.0-4.1ubuntu0.24.04.2) ...
Selecting previously unselected package nmap-common.
Preparing to unpack .../nmap-common_7.94+git20230807.3be01efb1+dfsg-3build2_all.
deb ...
Unpacking nmap-common (7.94+git20230807.3be01efb1+dfsg-3build2) ...
Selecting previously unselected package nmap.
Preparing to unpack .../nmap_7.94+git20230807.3be01efb1+dfsg-3build2_amd64.deb .
..
Unpacking nmap (7.94+git20230807.3be01efb1+dfsg-3build2) ...
Setting up liblinear4:amd64 (2.3.0+dfsg-5build1) ...
Setting up nmap-common (7.94+git20230807.3be01efb1+dfsg-3build2) ...
Setting up libssh2-1t64:amd64 (1.11.0-4.1ubuntu0.24.04.2) ...
Setting up nmap (7.94+git20230807.3be01efb1+dfsg-3build2) ...
Processing triggers for man-db (2.12.0-4build2) ...
Processing triggers for libc-bin (2.39-0ubuntu8.7) ...
mtech@programminglab:~/Desktop$ sudo nmap -A 10.10.1.87
Starting Nmap 7.94SVN ( https://nmap.org ) at 2026-07-08 14:54 IST
Nmap scan report for 10.10.1.87
Host is up (0.00034s latency).
All 1000 scanned ports on 10.10.1.87 are in ignored states.
Not shown: 1000 closed tcp ports (reset)
MAC Address: D0:AD:08:55:8D:A6 (Unknown)
Too many fingerprints match this host to give specific OS details
Network Distance: 1 hop

TRACEROUTE
HOP RTT     ADDRESS
1   0.34 ms 10.10.1.87

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 2.42 seconds
mtech@programminglab:~/Desktop$ man nmap
mtech@programminglab:~/Desktop$ sudo apt install tcpdump
[sudo] password for mtech: 
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages were automatically installed and are no longer required:
  amd64-microcode bpfcc-tools bpftrace ieee-data intel-microcode iucode-tool libbpfcc libclang-cpp18 libclang1-18 libllvm18 python3-bpfcc
  python3-netaddr thermald ubuntu-kernel-accessories
Use 'sudo apt autoremove' to remove them.
The following packages will be upgraded:
  tcpdump
1 upgraded, 0 newly installed, 0 to remove and 253 not upgraded.
Need to get 479 kB of archives.
After this operation, 0 B of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 tcpdump amd64 4.99.4-3ubuntu4.24.04.1 [479 kB]
Fetched 479 kB in 0s (1,397 kB/s)
(Reading database ... 230040 files and directories currently installed.)
Preparing to unpack .../tcpdump_4.99.4-3ubuntu4.24.04.1_amd64.deb ...
Unpacking tcpdump (4.99.4-3ubuntu4.24.04.1) over (4.99.4-3ubuntu4) ...
Setting up tcpdump (4.99.4-3ubuntu4.24.04.1) ...
Processing triggers for man-db (2.12.0-4build2) ...
mtech@programminglab:~/Desktop$ sudo tcpdump
tcpdump: verbose output suppressed, use -v[v]... for full protocol decode
listening on enp1s0, link-type EN10MB (Ethernet), snapshot length 262144 bytes
15:14:00.473955 STP 802.1w, Rapid STP, Flags [Learn, Forward, Agreement], bridge-id 8000.20:cf:ae:12:6f:31.800c, length 36
15:14:00.479456 ARP, Request who-has 10.10.65.168 tell 10.10.1.69, length 46
15:14:00.479471 ARP, Request who-has 10.10.66.168 tell 10.10.1.69, length 46
15:14:00.479472 ARP, Request who-has 10.10.67.168 tell 10.10.1.69, length 46
15:14:00.479473 ARP, Request who-has 10.10.68.168 tell 10.10.1.69, length 46
15:14:00.479473 ARP, Request who-has 10.10.69.168 tell 10.10.1.69, length 46
15:14:00.479474 ARP, Request who-has 10.10.70.168 tell 10.10.1.69, length 46
15:14:00.479475 ARP, Request who-has 10.10.71.168 tell 10.10.1.69, length 46
15:14:00.479475 ARP, Request who-has 10.10.72.168 tell 10.10.1.69, length 46
15:14:00.479480 ARP, Request who-has 10.10.73.168 tell 10.10.1.69, length 46
15:14:00.479481 ARP, Request who-has 10.10.74.168 tell 10.10.1.69, length 46
15:14:00.522337 IP programminglab.57895 > b.resolvers.level3.net.domain: 22350+ [1au] PTR? 168.65.10.10.in-addr.arpa. (54)
15:14:00.680306 ARP, Request who-has 10.10.65.168 tell 10.10.1.69, length 46
15:14:00.680320 ARP, Request who-has 10.10.66.168 tell 10.10.1.69, length 46
15:14:00.680321 ARP, Request who-has 10.10.67.168 tell 10.10.1.69, length 46
15:14:00.680322 ARP, Request who-has 10.10.68.168 tell 10.10.1.69, length 46
15:14:00.680322 ARP, Request who-has 10.10.69.168 tell 10.10.1.69, length 46
15:14:00.680323 ARP, Request who-has 10.10.70.168 tell 10.10.1.69, length 46
15:14:00.680324 ARP, Request who-has 10.10.71.168 tell 10.10.1.69, length 46
15:14:00.680324 ARP, Request who-has 10.10.72.168 tell 10.10.1.69, length 46
15:14:00.680332 ARP, Request who-has 10.10.73.168 tell 10.10.1.69, length 46
15:14:00.680332 ARP, Request who-has 10.10.74.168 tell 10.10.1.69, length 46
15:14:00.881103 ARP, Request who-has 10.10.79.168 tell 10.10.1.69, length 46
15:14:00.881117 ARP, Request who-has 10.10.64.169 tell 10.10.1.69, length 46
15:14:00.881118 ARP, Request who-has 10.10.65.169 tell 10.10.1.69, length 46
15:14:00.881118 ARP, Request who-has 10.10.66.169 tell 10.10.1.69, length 46
15:14:00.881119 ARP, Request who-has 10.10.67.169 tell 10.10.1.69, length 46
15:14:00.881120 ARP, Request who-has 10.10.68.169 tell 10.10.1.69, length 46
15:14:00.881121 ARP, Request who-has 10.10.69.169 tell 10.10.1.69, length 46
15:14:00.881121 ARP, Request who-has 10.10.70.169 tell 10.10.1.69, length 46
15:14:00.881129 ARP, Request who-has 10.10.71.169 tell 10.10.1.69, length 46
15:14:00.881130 ARP, Request who-has 10.10.72.169 tell 10.10.1.69, length 46
15:14:01.081705 ARP, Request who-has 10.10.79.168 tell 10.10.1.69, length 46
15:14:01.081715 ARP, Request who-has 10.10.64.169 tell 10.10.1.69, length 46
15:14:01.081716 ARP, Request who-has 10.10.65.169 tell 10.10.1.69, length 46
15:14:01.081717 ARP, Request who-has 10.10.66.169 tell 10.10.1.69, length 46
15:14:01.081718 ARP, Request who-has 10.10.67.169 tell 10.10.1.69, length 46
15:14:01.081719 ARP, Request who-has 10.10.68.169 tell 10.10.1.69, length 46
15:14:01.081720 ARP, Request who-has 10.10.69.169 tell 10.10.1.69, length 46
15:14:01.081721 ARP, Request who-has 10.10.70.169 tell 10.10.1.69, length 46
15:14:01.081730 ARP, Request who-has 10.10.71.169 tell 10.10.1.69, length 46
15:14:01.081731 ARP, Request who-has 10.10.72.169 tell 10.10.1.69, length 46
15:14:01.127736 ARP, Request who-has 10.10.1.5 tell _gateway, length 46
15:14:01.282523 ARP, Request who-has 10.10.77.169 tell 10.10.1.69, length 46
15:14:01.282534 ARP, Request who-has 10.10.78.169 tell 10.10.1.69, length 46
15:14:01.282535 ARP, Request who-has 10.10.79.169 tell 10.10.1.69, length 46
15:14:01.282536 ARP, Request who-has 10.10.64.170 tell 10.10.1.69, length 46
15:14:01.282536 ARP, Request who-has 10.10.65.170 tell 10.10.1.69, length 46
15:14:01.282537 ARP, Request who-has 10.10.66.170 tell 10.10.1.69, length 46
15:14:01.282538 ARP, Request who-has 10.10.67.170 tell 10.10.1.69, length 46
15:14:01.282539 ARP, Request who-has 10.10.68.170 tell 10.10.1.69, length 46
15:14:01.282548 ARP, Request who-has 10.10.69.170 tell 10.10.1.69, length 46
15:14:01.282549 ARP, Request who-has 10.10.70.170 tell 10.10.1.69, length 46
15:14:01.395141 IP 10.10.1.120.53760 > 255.255.255.255.29810: UDP, length 367
15:14:01.483398 ARP, Request who-has 10.10.77.169 tell 10.10.1.69, length 46
15:14:01.483410 ARP, Request who-has 10.10.78.169 tell 10.10.1.69, length 46
15:14:01.483411 ARP, Request who-has 10.10.79.169 tell 10.10.1.69, length 46
15:14:01.483412 ARP, Request who-has 10.10.64.170 tell 10.10.1.69, length 46
15:14:01.483413 ARP, Request who-has 10.10.65.170 tell 10.10.1.69, length 46
15:14:01.483414 ARP, Request who-has 10.10.66.170 tell 10.10.1.69, length 46
15:14:01.483415 ARP, Request who-has 10.10.67.170 tell 10.10.1.69, length 46
15:14:01.483416 ARP, Request who-has 10.10.68.170 tell 10.10.1.69, length 46
15:14:01.483427 ARP, Request who-has 10.10.69.170 tell 10.10.1.69, length 46
15:14:01.483428 ARP, Request who-has 10.10.70.170 tell 10.10.1.69, length 46
15:14:06.252536 IP programminglab.54293 > dns.google.domain: 13550+ [1au] PTR? 2.2.2.4.in-addr.arpa. (49)
15:14:06.301595 ARP, Request who-has 10.10.69.180 tell 10.10.1.69, length 46
15:14:06.301610 ARP, Request who-has 10.10.70.180 tell 10.10.1.69, length 46
15:14:06.301611 ARP, Request who-has 10.10.71.180 tell 10.10.1.69, length 46
15:14:06.301612 ARP, Request who-has 10.10.72.180 tell 10.10.1.69, length 46
15:14:06.301613 ARP, Request who-has 10.10.73.180 tell 10.10.1.69, length 46
15:14:06.301614 ARP, Request who-has 10.10.74.180 tell 10.10.1.69, length 46
15:14:06.301615 ARP, Request who-has 10.10.75.180 tell 10.10.1.69, length 46
15:14:06.301616 ARP, Request who-has 10.10.76.180 tell 10.10.1.69, length 46
15:14:06.301629 ARP, Request who-has 10.10.77.180 tell 10.10.1.69, length 46
15:14:06.301630 ARP, Request who-has 10.10.78.180 tell 10.10.1.69, length 46
15:14:06.305565 IP dns.google.domain > programminglab.54293: 13550 1/0/1 PTR b.resolvers.level3.net. (85)
15:14:06.306264 IP programminglab.58655 > dns.google.domain: 7270+ [1au] PTR? 81.1.10.10.in-addr.arpa. (52)
15:14:06.416571 IP programminglab.52133 > dns.google.domain: 36982+ [1au] PTR? 168.79.10.10.in-addr.arpa. (54)
15:14:06.438112 IP dns.google.domain > programminglab.52133: 36982 NXDomain 0/0/1 (54)
15:14:06.438871 IP programminglab.50672 > dns.google.domain: 38511+ [1au] PTR? 169.64.10.10.in-addr.arpa. (54)
15:14:06.444569 IP6 fe80::85c8:f417:10a:2c92.mdns > ff02::fb.mdns: 0 [2q] PTR (QM)? _ipps._tcp.local. PTR (QM)? _ipp._tcp.local. (45)
15:14:06.474441 STP 802.1w, Rapid STP, Flags [Learn, Forward, Agreement], bridge-id 8000.20:cf:ae:12:6f:31.800c, length 36
15:14:06.502544 ARP, Request who-has 10.10.67.181 tell 10.10.1.69, length 46
15:14:06.502556 ARP, Request who-has 10.10.68.181 tell 10.10.1.69, length 46
15:14:06.502557 ARP, Request who-has 10.10.69.181 tell 10.10.1.69, length 46
15:14:06.502558 ARP, Request who-has 10.10.70.181 tell 10.10.1.69, length 46
15:14:06.502559 ARP, Request who-has 10.10.71.181 tell 10.10.1.69, length 46
15:14:06.502560 ARP, Request who-has 10.10.72.181 tell 10.10.1.69, length 46
15:14:06.502560 ARP, Request who-has 10.10.73.181 tell 10.10.1.69, length 46
15:14:06.502561 ARP, Request who-has 10.10.74.181 tell 10.10.1.69, length 46
15:14:06.502576 ARP, Request who-has 10.10.75.181 tell 10.10.1.69, length 46
15:14:06.502577 ARP, Request who-has 10.10.76.181 tell 10.10.1.69, length 46
15:14:06.502578 IP dns.google.domain > programminglab.50672: 38511 NXDomain 0/0/1 (54)
15:14:06.503373 IP programminglab.49933 > dns.google.domain: 22634+ [1au] PTR? 169.65.10.10.in-addr.arpa. (54)
15:14:06.547971 IP dns.google.domain > programminglab.49933: 22634 NXDomain 0/0/1 (54)
15:14:06.548854 IP programminglab.42096 > dns.google.domain: 59495+ [1au] PTR? 169.66.10.10.in-addr.arpa. (54)
15:14:06.620561 ARP, Request who-has 10.10.1.92 tell 10.10.1.122, length 46
15:14:06.956863 IP programminglab.52809 > dns.google.domain: 40530+ [1au] PTR? 5.1.10.10.in-addr.arpa. (51)
15:14:06.984829 IP dns.google.domain > programminglab.52809: 40530 NXDomain 0/0/1 (51)
15:14:06.985575 IP programminglab.58838 > dns.google.domain: 26866+ [1au] PTR? 2.1.10.10.in-addr.arpa. (51)
15:14:07.011828 IP dns.google.domain > programminglab.58838: 26866 NXDomain 0/0/1 (51)
15:14:07.012638 IP programminglab.39346 > dns.google.domain: 56383+ [1au] PTR? 169.77.10.10.in-addr.arpa. (54)
15:14:07.032702 IP dns.google.domain > programminglab.39346: 56383 NXDomain 0/0/1 (54)
15:14:07.033465 IP programminglab.56265 > dns.google.domain: 37293+ [1au] PTR? 169.78.10.10.in-addr.arpa. (54)
15:14:07.058548 IP dns.google.domain > programminglab.56265: 37293 NXDomain 0/0/1 (54)
15:14:07.059296 IP programminglab.48612 > dns.google.domain: 50326+ [1au] PTR? 169.79.10.10.in-addr.arpa. (54)
15:14:07.081574 IP dns.google.domain > programminglab.48612: 50326 NXDomain 0/0/1 (54)
15:14:07.082295 IP programminglab.42399 > dns.google.domain: 37163+ [1au] PTR? 170.64.10.10.in-addr.arpa. (54)
15:14:07.100496 IP 10.10.1.119.41549 > 255.255.255.255.29810: UDP, length 367
15:14:07.101549 IP dns.google.domain > programminglab.42399: 37163 NXDomain 0/0/1 (54)
15:14:07.102279 IP programminglab.39263 > dns.google.domain: 28270+ [1au] PTR? 170.65.10.10.in-addr.arpa. (54)
15:14:07.104098 ARP, Request who-has 10.10.65.182 tell 10.10.1.69, length 46
15:14:07.104109 ARP, Request who-has 10.10.66.182 tell 10.10.1.69, length 46
15:14:07.104111 ARP, Request who-has 10.10.67.182 tell 10.10.1.69, length 46
15:14:07.104113 ARP, Request who-has 10.10.68.182 tell 10.10.1.69, length 46
15:14:07.104115 ARP, Request who-has 10.10.69.182 tell 10.10.1.69, length 46
15:14:07.104151 ARP, Request who-has 10.10.70.182 tell 10.10.1.69, length 46
15:14:07.104153 ARP, Request who-has 10.10.71.182 tell 10.10.1.69, length 46
15:14:07.104154 ARP, Request who-has 10.10.72.182 tell 10.10.1.69, length 46
15:14:07.104154 ARP, Request who-has 10.10.73.182 tell 10.10.1.69, length 46
15:14:07.104155 ARP, Request who-has 10.10.74.182 tell 10.10.1.69, length 46
15:14:07.124608 IP dns.google.domain > programminglab.39263: 28270 NXDomain 0/0/1 (54)
15:14:07.125384 IP programminglab.36486 > dns.google.domain: 39110+ [1au] PTR? 170.66.10.10.in-addr.arpa. (54)
15:14:07.263967 IP programminglab.56100 > dns.google.domain: 24814+ [1au] PTR? 120.1.10.10.in-addr.arpa. (53)
15:14:07.301858 IP dns.google.domain > programminglab.56100: 24814 NXDomain 0/0/1 (53)
15:14:07.302770 IP programminglab.34538 > dns.google.domain: 31884+ [1au] PTR? 8.8.8.8.in-addr.arpa. (49)
15:14:07.304915 ARP, Request who-has 10.10.79.182 tell 10.10.1.69, length 46
15:14:07.304925 ARP, Request who-has 10.10.64.183 tell 10.10.1.69, length 46
15:14:07.304926 ARP, Request who-has 10.10.65.183 tell 10.10.1.69, length 46
15:14:07.304927 ARP, Request who-has 10.10.66.183 tell 10.10.1.69, length 46
15:14:07.304928 ARP, Request who-has 10.10.67.183 tell 10.10.1.69, length 46
15:14:07.304929 ARP, Request who-has 10.10.68.183 tell 10.10.1.69, length 46
15:14:07.304929 ARP, Request who-has 10.10.69.183 tell 10.10.1.69, length 46
15:14:07.304930 ARP, Request who-has 10.10.70.183 tell 10.10.1.69, length 46
15:14:07.304939 ARP, Request who-has 10.10.71.183 tell 10.10.1.69, length 46
15:14:07.304940 ARP, Request who-has 10.10.72.183 tell 10.10.1.69, length 46
15:14:07.348841 IP dns.google.domain > programminglab.34538: 31884 1/0/1 PTR dns.google. (73)
15:14:07.349637 IP programminglab.60892 > dns.google.domain: 11976+ [1au] PTR? 180.69.10.10.in-addr.arpa. (54)
15:14:07.391739 IP dns.google.domain > programminglab.60892: 11976 NXDomain 0/0/1 (54)
15:14:07.392599 IP programminglab.52224 > dns.google.domain: 15194+ [1au] PTR? 180.70.10.10.in-addr.arpa. (54)
15:14:07.441356 IP dns.google.domain > programminglab.52224: 15194 NXDomain 0/0/1 (54)
15:14:07.442198 IP programminglab.37256 > dns.google.domain: 34543+ [1au] PTR? 180.71.10.10.in-addr.arpa. (54)
15:14:07.505703 ARP, Request who-has 10.10.79.182 tell 10.10.1.69, length 46
15:14:07.505715 ARP, Request who-has 10.10.64.183 tell 10.10.1.69, length 46
15:14:07.505716 ARP, Request who-has 10.10.65.183 tell 10.10.1.69, length 46
15:14:07.505717 ARP, Request who-has 10.10.66.183 tell 10.10.1.69, length 46
15:14:07.505718 ARP, Request who-has 10.10.67.183 tell 10.10.1.69, length 46
15:14:07.505719 ARP, Request who-has 10.10.68.183 tell 10.10.1.69, length 46
15:14:07.505720 ARP, Request who-has 10.10.69.183 tell 10.10.1.69, length 46
15:14:07.505721 ARP, Request who-has 10.10.70.183 tell 10.10.1.69, length 46
15:14:07.505732 ARP, Request who-has 10.10.71.183 tell 10.10.1.69, length 46
15:14:07.505733 ARP, Request who-has 10.10.72.183 tell 10.10.1.69, length 46
15:14:07.514033 IP dns.google.domain > programminglab.37256: 34543 NXDomain 0/0/1 (54)
15:14:07.514988 IP programminglab.38375 > dns.google.domain: 59751+ [1au] PTR? 180.72.10.10.in-addr.arpa. (54)
15:14:07.532734 IP dns.google.domain > programminglab.38375: 59751 NXDomain 0/0/1 (54)
15:14:07.533617 IP programminglab.57017 > dns.google.domain: 22922+ [1au] PTR? 180.73.10.10.in-addr.arpa. (54)
15:14:07.557338 IP dns.google.domain > programminglab.57017: 22922 NXDomain 0/0/1 (54)
15:14:07.558130 IP programminglab.34764 > dns.google.domain: 38068+ [1au] PTR? 180.74.10.10.in-addr.arpa. (54)
15:14:07.574950 IP dns.google.domain > programminglab.34764: 38068 NXDomain 0/0/1 (54)
15:14:07.575645 IP programminglab.49978 > dns.google.domain: 25534+ [1au] PTR? 180.75.10.10.in-addr.arpa. (54)
15:14:07.671570 IP programminglab.39897 > dns.google.domain: 56514+ [1au] PTR? b.f.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.0.2.0.f.f.ip6.arpa. (101)
15:14:07.706533 ARP, Request who-has 10.10.77.183 tell 10.10.1.69, length 46
15:14:07.706549 ARP, Request who-has 10.10.78.183 tell 10.10.1.69, length 46
15:14:07.706550 ARP, Request who-has 10.10.79.183 tell 10.10.1.69, length 46
15:14:07.706551 ARP, Request who-has 10.10.64.184 tell 10.10.1.69, length 46
15:14:07.706552 ARP, Request who-has 10.10.65.184 tell 10.10.1.69, length 46
^C15:14:07.706553 ARP, Request who-has 10.10.66.184 tell 10.10.1.69, length 46

167 packets captured
914 packets received by filter
651 packets dropped by kernel
mtech@programminglab:~/Desktop$ mkdir Avany
mtech@programminglab:~/Desktop$ touch lab.md
mtech@programminglab:~/Desktop$ touch lab2.md
mtech@programminglab:~/Desktop$ nano qwerty.md
mtech@programminglab:~/Desktop$ pwd
/home/mtech/Desktop
mtech@programminglab:~/Desktop$ ls
'80 and'  'almost always faster and more effective.'   Avany  'e your odds of penetrating strict firewalls by sending many'
mtech@programminglab:~/Desktop$ mtech@programminglab:~/Desktop$ ip a
mtech@programminglab:~/Desktop$ mtech@programminglab:~/Desktop$ ip a
mtech@programminglab:~/Desktop$ mtech@programminglab:~/Desktop$ ip a
mtech@programminglab:~/Desktop$ mtech@programminglab:~/Desktop$ ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo_lft forever
       valid_lft forever preferred_lft forevertu 1500 qdisc pfifo_fast state UP group default qlen 1000
    inet6 ::1/128 scope host noprefixroute vertu 1500 qdisc pfifo_fast state UP group default qlen 1000
       valid_lft forever preferred_lft forevertu 1500 qdisc pfifo_fast state UP group default qlen 1000
2: enp1s0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state UP group default qlen 1000
    link/ether d0:ad:08:55:ae:31 brd ff:ff:ff:ff:ff:ffdynamic noprefixroute enp1s0
    inet 10.10.1.81/16 brd 10.10.255.255 scope global dynamic noprefixroute enp1s0
       valid_lft 25767sec preferred_lft 25767seck noprefixroute 
    inet6 fe80::2f75:6593:32da:359c/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever27.0.0.1/8
mtech@programminglab:~/Desktop$ sudo nmap -A 127.0.0.1/8
[sudo] password for mtech: ndp$ sudo nmap -A 127.0.0
sudo: nmap: command not foundp$ sudo nmap -A 127.0.0.
mtech@programminglab:~/Desktop$ sudo nmap -A 127.0.0.
sudo: nmap: command not foundp$ sudo nmap -A 127.0.0.
mtech@programminglab:~/Desktop$ sudo nmap -A 127.0.0.
sudo: nmap: command not foundp$ sudo nmap -A 10.10.1.87
mtech@programminglab:~/Desktop$ sudo nmap -A 10.10.1.87
sudo: nmap: command not foundp$ sudo nmap -A 10.10.1.87
mtech@programminglab:~/Desktop$ sudo nmap -A 10.10.1.87
sudo: nmap: command not foundp$ sudo nmap -A 10.10.1.87
mtech@programminglab:~/Desktop$ sudo nmap -A 10.10.1.87
sudo: nmap: command not foundp$ sudo apt instal nmapp
mtech@programminglab:~/Desktop$ sudo apt instal nmapp
E: Invalid operation instaltop$ sudo apt install nmap
mtech@programminglab:~/Desktop$ sudo apt install nmap
Reading package lists... Doneoneeatically installed and are no longer required:
Building dependency tree... Doneeatically installed and are no longer required:
Reading state information... Doneatically installed and are no longer required:
The following packages were automatically installed and are no longer required:
  amd64-microcode bpfcc-tools bpftrace ieee-data intel-microcode iucode-tooldr
  libbpfcc libclang-cpp18 libclang1-18 libllvm18 python3-bpfcc python3-netaddrpenetrating strict firewalls by sending many'0.0.0.0.0.0.2.0.f.f.ip6.arpa.
  thermald ubuntu-kernel-accessoriesthem.effective.'   Avany  'e your odds of penetrating strict firewalls by sending many'0.0.0.0.0.0.2.0.f.f.ip6.arpa.Use 'sudo apt autoremove' to remove them.
'80 and'  'almost always faster and more effective.'   Avany  'e your odds of penetrating strict firewalls by sending many'0.0.0.0.0.0.2.0.f.f.ip6.arpa.




mtech@programminglab:~$ whois google.com
Command 'whois' not found, but can be installed with:
sudo apt install whois
mtech@programminglab:~$ whois www.google.com
Command 'whois' not found, but can be installed with:
sudo apt install whois
mtech@programminglab:~$ sudo apt update
[sudo] password for mtech: 
Get:1 http://security.ubuntu.com/ubuntu noble-security InRelease [126 kB]
Hit:2 http://archive.ubuntu.com/ubuntu noble InRelease  
Get:3 http://archive.ubuntu.com/ubuntu noble-updates InRelease [126 kB]
Get:4 http://security.ubuntu.com/ubuntu noble-security/main amd64 Components [44.9 kB]
Get:5 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Components [76.3 kB]
Get:6 http://archive.ubuntu.com/ubuntu noble-backports InRelease [126 kB]
Get:7 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages [1,079 kB]
Get:8 http://archive.ubuntu.com/ubuntu noble-updates/main i386 Packages [514 kB]
Get:9 http://archive.ubuntu.com/ubuntu noble-updates/main amd64 Components [181 kB]
Get:10 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages [1,659 kB]
Get:11 http://archive.ubuntu.com/ubuntu noble-updates/universe i386 Packages [1,130 kB]
Get:12 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 Components [388 kB]
Get:13 http://archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Components [940 B]
Get:14 http://archive.ubuntu.com/ubuntu noble-backports/main amd64 Components [5,760 B]
Get:15 http://archive.ubuntu.com/ubuntu noble-backports/universe amd64 Components [10.5 kB]
Fetched 5,467 kB in 3s (1,998 kB/s)                                 
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
254 packages can be upgraded. Run 'apt list --upgradable' to see them.
mtech@programminglab:~$ whois google.com
Command 'whois' not found, but can be installed with:
sudo apt install whois
mtech@programminglab:~$ sudo apt install whois
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages were automatically installed and are no longer required:
  amd64-microcode bpfcc-tools bpftrace ieee-data intel-microcode iucode-tool
  libbpfcc libclang-cpp18 libclang1-18 libllvm18 python3-bpfcc python3-netaddr
  thermald ubuntu-kernel-accessories
Use 'sudo apt autoremove' to remove them.
The following NEW packages will be installed:
  whois
0 upgraded, 1 newly installed, 0 to remove and 254 not upgraded.
Need to get 51.7 kB of archives.
After this operation, 279 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu noble/main amd64 whois amd64 5.5.22 [51.7 kB]
Fetched 51.7 kB in 0s (239 kB/s) 
Selecting previously unselected package whois.
(Reading database ... 229165 files and directories currently installed.)
Preparing to unpack .../whois_5.5.22_amd64.deb ...
Unpacking whois (5.5.22) ...
Setting up whois (5.5.22) ...
Processing triggers for man-db (2.12.0-4build2) ...
mtech@programminglab:~$ whois google.com
   Domain Name: GOOGLE.COM
   Registry Domain ID: 2138514_DOMAIN_COM-VRSN
   Registrar WHOIS Server: whois.markmonitor.com
   Registrar URL: http://www.markmonitor.com
   Updated Date: 2019-09-09T15:39:04Z
   Creation Date: 1997-09-15T04:00:00Z
   Registry Expiry Date: 2028-09-14T04:00:00Z
   Registrar: MarkMonitor Inc.
   Registrar IANA ID: 292
   Registrar Abuse Contact Email: abusecomplaints@markmonitor.com
   Registrar Abuse Contact Phone: +1.2086851750
   Domain Status: clientDeleteProhibited https://icann.org/epp#clientDeleteProhibited
   Domain Status: clientTransferProhibited https://icann.org/epp#clientTransferProhibited
   Domain Status: clientUpdateProhibited https://icann.org/epp#clientUpdateProhibited
   Domain Status: serverDeleteProhibited https://icann.org/epp#serverDeleteProhibited
   Domain Status: serverTransferProhibited https://icann.org/epp#serverTransferProhibited
   Domain Status: serverUpdateProhibited https://icann.org/epp#serverUpdateProhibited
   Name Server: NS1.GOOGLE.COM
   Name Server: NS2.GOOGLE.COM
   Name Server: NS3.GOOGLE.COM
   Name Server: NS4.GOOGLE.COM
   DNSSEC: unsigned
   URL of the ICANN Whois Inaccuracy Complaint Form: https://www.icann.org/wicf/
>>> Last update of whois database: 2026-07-08T08:54:06Z <<<

For more information on Whois status codes, please visit https://icann.org/epp

NOTICE: The expiration date displayed in this record is the date the
registrar's sponsorship of the domain name registration in the registry is
currently set to expire. This date does not necessarily reflect the expiration
date of the domain name registrant's agreement with the sponsoring
registrar.  Users may consult the sponsoring registrar's Whois database to
view the registrar's reported date of expiration for this registration.

TERMS OF USE: You are not authorized to access or query our Whois
database through the use of electronic processes that are high-volume and
automated except as reasonably necessary to register domain names or
modify existing registrations; the Data in VeriSign Global Registry
Services' ("VeriSign") Whois database is provided by VeriSign for
information purposes only, and to assist persons in obtaining information
about or related to a domain name registration record. VeriSign does not
guarantee its accuracy. By submitting a Whois query, you agree to abide
by the following terms of use: You agree that you may use this Data only
for lawful purposes and that under no circumstances will you use this Data
to: (1) allow, enable, or otherwise support the transmission of mass
unsolicited, commercial advertising or solicitations via e-mail, telephone,
or facsimile; or (2) enable high volume, automated, electronic processes
that apply to VeriSign (or its computer systems). The compilation,
repackaging, dissemination or other use of this Data is expressly
prohibited without the prior written consent of VeriSign. You agree not to
use electronic processes that are automated and high-volume to access or
query the Whois database except as reasonably necessary to register
domain names or modify existing registrations. VeriSign reserves the right
to restrict your access to the Whois database in its sole discretion to ensure
operational stability.  VeriSign may restrict or terminate your access to the
Whois database for failure to abide by these terms of use. VeriSign
reserves the right to modify these terms at any time.

The Registry database contains ONLY .COM, .NET, .EDU domains and
Registrars.
mtech@programminglab:~$ whois nssce.com
   Domain Name: NSSCE.COM
   Registry Domain ID: 1881501226_DOMAIN_COM-VRSN
   Registrar WHOIS Server: whois.namebright.com
   Registrar URL: http://www.NameBright.com
   Updated Date: 2025-10-22T07:36:55Z
   Creation Date: 2014-10-21T18:26:36Z
   Registry Expiry Date: 2026-10-21T18:26:36Z
   Registrar: TurnCommerce, Inc. DBA NameBright.com
   Registrar IANA ID: 1441
   Registrar Abuse Contact Email: support@namebright.com
   Registrar Abuse Contact Phone: 17204960020
   Domain Status: clientTransferProhibited https://icann.org/epp#clientTransferProhibited
   Name Server: NSG1.NAMEBRIGHTDNS.COM
   Name Server: NSG2.NAMEBRIGHTDNS.COM
   DNSSEC: unsigned
   URL of the ICANN Whois Inaccuracy Complaint Form: https://www.icann.org/wicf/
>>> Last update of whois database: 2026-07-08T08:55:36Z <<<

For more information on Whois status codes, please visit https://icann.org/epp

NOTICE: The expiration date displayed in this record is the date the
registrar's sponsorship of the domain name registration in the registry is
currently set to expire. This date does not necessarily reflect the expiration
date of the domain name registrant's agreement with the sponsoring
registrar.  Users may consult the sponsoring registrar's Whois database to
view the registrar's reported date of expiration for this registration.

TERMS OF USE: You are not authorized to access or query our Whois
database through the use of electronic processes that are high-volume and
automated except as reasonably necessary to register domain names or
modify existing registrations; the Data in VeriSign Global Registry
Services' ("VeriSign") Whois database is provided by VeriSign for
information purposes only, and to assist persons in obtaining information
about or related to a domain name registration record. VeriSign does not
guarantee its accuracy. By submitting a Whois query, you agree to abide
by the following terms of use: You agree that you may use this Data only
for lawful purposes and that under no circumstances will you use this Data
to: (1) allow, enable, or otherwise support the transmission of mass
unsolicited, commercial advertising or solicitations via e-mail, telephone,
or facsimile; or (2) enable high volume, automated, electronic processes
that apply to VeriSign (or its computer systems). The compilation,
repackaging, dissemination or other use of this Data is expressly
prohibited without the prior written consent of VeriSign. You agree not to
use electronic processes that are automated and high-volume to access or
query the Whois database except as reasonably necessary to register
domain names or modify existing registrations. VeriSign reserves the right
to restrict your access to the Whois database in its sole discretion to ensure
operational stability.  VeriSign may restrict or terminate your access to the
Whois database for failure to abide by these terms of use. VeriSign
reserves the right to modify these terms at any time.

The Registry database contains ONLY .COM, .NET, .EDU domains and
Registrars.
Domain Name: NSSCE.COM
Registry Domain ID: 1881501226_DOMAIN_COM-VRSN
Registrar WHOIS Server: whois.NameBright.com
Registrar URL: https://www.NameBright.com
Updated Date: 2020-10-15T07:07:53.712Z
Creation Date: 2014-10-21T18:26:36.000Z
Registrar Registration Expiration Date: 2026-10-21T18:26:36.000Z
Registrar: TurnCommerce, Inc. DBA NameBright.com
Registrar IANA ID: 1441
Registrar Abuse Contact Email: abuse@NameBright.com
Registrar Abuse Contact Phone: +1.7204960020
Domain Status: clientTransferProhibited https://www.icann.org/epp#clientTransferProhibited
Registry Registrant ID: Not Available From Registry
Registrant Name: Domain Admin / This Domain is For Sale
Registrant Organization: HugeDomains.com
Registrant Street: 2635 Walnut Street
Registrant City: Denver
Registrant State/Province: CO
Registrant Postal Code: 80205
Registrant Country: US
Registrant Phone: +1.3038930552
Registrant Phone Ext: 
Registrant Fax: 
Registrant Fax Ext: 
Registrant Email: domains@hugedomains.com
Registry Admin ID: Not Available From Registry
Admin Name: Domain Admin / This Domain is For Sale
Admin Organization: HugeDomains.com
Admin Street: 2635 Walnut Street
Admin City: Denver
Admin State/Province: CO
Admin Postal Code: 80205
Admin Country: US
Admin Phone: +1.3038930552
Admin Phone Ext: 
Admin Fax: 
Admin Fax Ext: 
Admin Email: domains@hugedomains.com
Registry Tech ID: Not Available From Registry
Tech Name: Domain Admin / This Domain is For Sale
Tech Organization: HugeDomains.com
Tech Street: 2635 Walnut Street
Tech City: Denver
Tech State/Province: CO
Tech Postal Code: 80205
Tech Country: US
Tech Phone: +1.3038930552
Tech Phone Ext: 
Tech Fax: 
Tech Fax Ext: 
Tech Email: domains@hugedomains.com
Name Server: NSG1.NAMEBRIGHTDNS.COM
Name Server: NSG2.NAMEBRIGHTDNS.COM
DNSSEC: unsigned
URL of the ICANN WHOIS Data Problem Reporting System: http://wdprs.internic.net/
>>> Last update of WHOIS database: 2020-10-15T07:07:53.712Z <<<
mtech@programminglab:~$ whois 8.8 8.8
No whois server is known for this kind of object.
mtech@programminglab:~$ whois 8.8.8.8

#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2026, American Registry for Internet Numbers, Ltd.
#


NetRange:       8.8.8.0 - 8.8.8.255
CIDR:           8.8.8.0/24
NetName:        GOGL
NetHandle:      NET-8-8-8-0-2
Parent:         NET8 (NET-8-0-0-0-0)
NetType:        Direct Allocation
OriginAS:       
Organization:   Google LLC (GOGL)
RegDate:        2023-12-28
Updated:        2023-12-28
Ref:            https://rdap.arin.net/registry/ip/8.8.8.0



OrgName:        Google LLC
OrgId:          GOGL
Address:        1600 Amphitheatre Parkway
City:           Mountain View
StateProv:      CA
PostalCode:     94043
Country:        US
RegDate:        2000-03-30
Updated:        2019-10-31
Comment:        Please note that the recommended way to file abuse complaints are located in the following links. 
Comment:        
Comment:        To report abuse and illegal activity: https://www.google.com/contact/
Comment:        
Comment:        For legal requests: http://support.google.com/legal 
Comment:        
Comment:        Regards, 
Comment:        The Google Team
Ref:            https://rdap.arin.net/registry/entity/GOGL


OrgAbuseHandle: ABUSE5250-ARIN
OrgAbuseName:   Abuse
OrgAbusePhone:  +1-650-253-0000 
OrgAbuseEmail:  network-abuse@google.com
OrgAbuseRef:    https://rdap.arin.net/registry/entity/ABUSE5250-ARIN

OrgTechHandle: ZG39-ARIN
OrgTechName:   Google LLC
OrgTechPhone:  +1-650-253-0000 
OrgTechEmail:  arin-contact@google.com
OrgTechRef:    https://rdap.arin.net/registry/entity/ZG39-ARIN


#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2026, American Registry for Internet Numbers, Ltd.
#

mtech@programminglab:~$ 



