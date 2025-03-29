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
![image](https://github.com/user-attachments/assets/e09dc0c8-3025-4224-a913-7304c7b9a58b)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/533a1b9f-b0bb-4d4d-bcc7-93d146b98c16)

 dsniff:
![image](https://github.com/user-attachments/assets/e3f83615-5c7e-4889-89dd-86cbf0a983f6)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/e3f83615-5c7e-4889-89dd-86cbf0a983f6)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
