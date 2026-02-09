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
<img width="977" height="748" alt="image" src="https://github.com/user-attachments/assets/0eaeaeb2-eabb-4d22-aadb-625dc2efa561" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="839" height="570" alt="image" src="https://github.com/user-attachments/assets/1d0c9b79-f3c9-44bf-89a0-7c6d3d5c4677" />


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="686" height="324" alt="image" src="https://github.com/user-attachments/assets/289723d7-0f42-4dd8-bc0b-6114414dba92" />




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="1570" height="320" alt="image" src="https://github.com/user-attachments/assets/6c9122b2-c421-4581-b929-cf962db26e51" />
Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1834" height="385" alt="image" src="https://github.com/user-attachments/assets/a96c9514-c555-456c-9086-c66b242bd735" />

<img width="1883" height="387" alt="image" src="https://github.com/user-attachments/assets/b202db2e-1f24-4180-abbf-920fb33d8bd2" />




## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
