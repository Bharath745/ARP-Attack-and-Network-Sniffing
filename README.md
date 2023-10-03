# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## ALGORITHM:

1) Install kali linux either in partition or virtual box or in live mode

2) Investigate on the various categories of tools as follows:

3) Open terminal and try execute some kali linux commands


## METHODS:

### ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.

In windows 7 give the command arp -a

#### OUTPUT:

![image](https://github.com/Bharath745/ARP-Attack-and-Network-Sniffing/assets/94508354/d54a3b5c-3938-4f13-9ba3-1eece373e1f0)




### From kali linux issue the command : sudo arpspoof -i eth0 -t <target system> <gateway>

#### OUTPUT:

![image](https://github.com/Bharath745/ARP-Attack-and-Network-Sniffing/assets/94508354/d1274e7c-3316-47c5-b3e1-71c489afaf0b)




### dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

![image](https://github.com/Bharath745/ARP-Attack-and-Network-Sniffing/assets/94508354/57e116b4-6c13-4ffa-8056-1d5fb5ccbb3e)



### In Kali issue the following commands:  sudo dsnifff

#### OUTPUT:

![image](https://github.com/Bharath745/ARP-Attack-and-Network-Sniffing/assets/94508354/e234a0f5-959e-4a49-8ff8-8859126c82bc)



### Invoke the wireshark and examine the various menus and controls of the tool:

![image](https://github.com/Bharath745/ARP-Attack-and-Network-Sniffing/assets/94508354/dcb291b5-7072-4ffe-b963-34f7605f9749)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
