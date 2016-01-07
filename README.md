# ICMPTunnel
Create a reverse icmp tunnel to forward tcp traffic,this maybe useful in some lan env
Usage:

Server ://   must be in a public network
echo 1> /proc/sys/net/ipv4/icmp_echo_ignore_all
python IcmpTunnel_S.py



Client :
python IcmpTunnel_S.py {serverIP} {needConnectIP} {needConnectPort}
