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
![image](https://github.com/kavisree86/ARP-Attack-and-Network-Sniffing/assets/145759687/6635cd3b-bbf3-4a46-af14-6da89503c7c0)



From kali linux issue the command :sudo arpspoof -i eth0 -t


sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/kavisree86/ARP-Attack-and-Network-Sniffing/assets/145759687/48f9ebfe-4724-496a-b10f-f0cfedbb0219)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/kavisree86/ARP-Attack-and-Network-Sniffing/assets/145759687/26ab77fe-875a-42e7-b0b1-c4f0ff8418ad)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/kavisree86/ARP-Attack-and-Network-Sniffing/assets/145759687/802b9fe6-b349-42fe-897a-fb355df491de)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/kavisree86/ARP-Attack-and-Network-Sniffing/assets/145759687/fd059d28-9b2f-4b16-af51-9407069ed6f9)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
