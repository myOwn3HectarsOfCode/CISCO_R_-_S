# CISCO_R_-_S
This file works with 7.3.1 version of Packet Tracer
I have made an example of little network (but with 3-4 routers so with the same  amount of LAN's  in the branch ).
There are a many of computers and printers - hosts had added to individual subnets (there are 16 VLAN's). The movenet between hosts from one VLAN to second is realized by L3 switches and furter it is  go by routers with static routing. Packets from hosts (access layer) go to DMS (R2->R3->DMS). At the top is Fortigate- this device replaces FortiGate (here must be set traffic rules for security and for VPN traffic - because privileged users can to connect with hosts from bottom of net).

Try how the traffic is happened - undirectly, because through 2-3 routers (this is (1): for a redundancy and (2): for security because(1) you can change cables and add connection to R2 router from L3 switches and (2) you can  set ACL  for differend kinds of traffic and filters for IP adresses)-
Testing of traffic can may done by simulation mode of Packet Tracer.
