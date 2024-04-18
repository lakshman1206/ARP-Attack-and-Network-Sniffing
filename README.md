# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![Screenshot 2024-04-12 100959](https://github.com/RahulKrishna05/ARP-Attack-and-Network-Sniffing/assets/162027231/c65ad8e1-9969-4c7b-815b-ac4ce3bb22ab)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2024-04-12 102327](https://github.com/RahulKrishna05/ARP-Attack-and-Network-Sniffing/assets/162027231/2054870d-dcc2-4b97-b531-7f27c5b65a16)

 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2024-04-12 103739](https://github.com/RahulKrishna05/ARP-Attack-and-Network-Sniffing/assets/162027231/685a7d33-9475-4990-9567-0219efc0bc7c)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2024-04-12 110446](https://github.com/RahulKrishna05/ARP-Attack-and-Network-Sniffing/assets/162027231/0d988d5c-ee61-420e-bca9-081e750573de)


Invoke the wireshark and examine the various menus  and controls of the tool:

![Screenshot 2024-04-12 110101](https://github.com/RahulKrishna05/ARP-Attack-and-Network-Sniffing/assets/162027231/06c5d32f-e1d5-41e1-a27d-b7e293f97b54)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
