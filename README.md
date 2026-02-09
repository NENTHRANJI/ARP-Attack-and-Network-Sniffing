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
<img width="854" height="657" alt="image" src="https://github.com/user-attachments/assets/2d097923-f573-47e8-97c2-8e1704acdb2f" />
From kali linux issue the command :
sudo arpspoof -i eth0 -t 
## OUTPUT:
<img width="839" height="570" alt="image" src="https://github.com/user-attachments/assets/1ba55a62-6b2a-42c7-a65a-1eedc865a66c" />

 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="686" height="324" alt="image" src="https://github.com/user-attachments/assets/fc8e7532-e61f-4d9c-ab46-bc24f4faad4c" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="816" height="130" alt="image" src="https://github.com/user-attachments/assets/0c1c2217-52cf-4a00-8374-015883647c8c" />
Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1834" height="385" alt="image" src="https://github.com/user-attachments/assets/81ac2e00-1129-4194-938d-505977c99b41" />
<img width="1883" height="387" alt="image" src="https://github.com/user-attachments/assets/f075e5ee-b164-4011-bc6f-abba1b159aba" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
