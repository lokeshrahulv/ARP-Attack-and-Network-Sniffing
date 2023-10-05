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
![VirtualBox_windows_05_10_2023_08_57_54](https://github.com/lokeshrahulv/ARP-Attack-and-Network-Sniffing/assets/118423842/f43711f1-f6ea-422d-a86b-61271a3e5494)

From kali linux issue the command :sudo arpspoof -i eth0 -t

## OUTPUT:
![b6105e25-f9a8-4d28-9464-c910b87049f0](https://github.com/lokeshrahulv/ARP-Attack-and-Network-Sniffing/assets/118423842/89a7ecca-74e6-4e64-ba8d-efd1faa284d7)

### dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![c426f3cc-47e2-4631-aaae-ba1244ff9633](https://github.com/lokeshrahulv/ARP-Attack-and-Network-Sniffing/assets/118423842/28b3edc7-3cf5-4658-a6bd-842aab75a4a1)
In Kali issue the following commands:sudo dsnifff
## OUTPUT:
![8123604d-0355-4114-8e7c-52728d5d08ef](https://github.com/lokeshrahulv/ARP-Attack-and-Network-Sniffing/assets/118423842/88aec302-91f2-4ea3-829c-ce71a82fce75)
Invoke the wireshark and examine the various menus  and controls of the tool:
![6e4f849a-9c76-4376-b777-0a9defbe64ba](https://github.com/lokeshrahulv/ARP-Attack-and-Network-Sniffing/assets/118423842/2f6643f1-7e85-46b8-9c7e-c273c76e618a)
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
