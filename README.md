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

![image](https://github.com/user-attachments/assets/91104689-f8a1-47ed-b96b-1e796779629a)


 dsniff:

![image](https://github.com/user-attachments/assets/aa7ddaf9-2559-40dd-92da-d54590ec35b9)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/user-attachments/assets/b6690d42-1c93-4c78-9e4f-8d18dc1c6769)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/52efd57d-dcd9-4bd9-aac0-5c94e36ffb83)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
