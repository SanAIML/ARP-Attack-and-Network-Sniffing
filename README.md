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
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
<img width="1702" height="622" alt="Screenshot 2025-09-19 133935" src="https://github.com/user-attachments/assets/bd443acb-7f7b-4a9d-81ff-c3b9cd5659d0" />

## OUTPUT:


 dsniff:



<img width="1324" height="752" alt="Screenshot 2025-09-19 133959" src="https://github.com/user-attachments/assets/2f71e46f-11c2-4571-88cb-dffcdbbeed4e" />



In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
<img width="1506" height="680" alt="Screenshot 2025-09-19 134016" src="https://github.com/user-attachments/assets/d9fc45b4-4ae6-4fba-af24-ba93fd0af086" />

## OUTPUT:
In Kali issue the following commands:
sudo dsnifff

<img width="1148" height="242" alt="Screenshot 2025-09-19 134028" src="https://github.com/user-attachments/assets/dabb9ab5-f427-45de-8759-407c6fff06ea" />


## OUTPUT:



Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1650" height="347" alt="Screenshot 2025-09-19 134049" src="https://github.com/user-attachments/assets/7c584115-066c-43a1-acd3-6f2b635e693c" />
<img width="1074" height="244" alt="Screenshot 2025-09-19 140418" src="https://github.com/user-attachments/assets/249516df-d201-4659-b08b-7f1b136fe905" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
