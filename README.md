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

![EXPT 4 1](https://github.com/22008686/ARP-Attack-and-Network-Sniffing/assets/118916413/67c687d6-b446-44d0-a131-fe5ec7c35505)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![EXPT 4 2](https://github.com/22008686/ARP-Attack-and-Network-Sniffing/assets/118916413/fb466a15-c416-4d2c-b4d4-2a5a7d01adb0)

dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![EXPT 4 3](https://github.com/22008686/ARP-Attack-and-Network-Sniffing/assets/118916413/96ab47e3-8577-4de5-bfe2-3c482e0540ba)

In Kali issue the following commands:
sudo dsnifff

## OUTPUT:

![EXPT 4 4](https://github.com/22008686/ARP-Attack-and-Network-Sniffing/assets/118916413/c76ef559-4030-4bcd-88bf-cfc4fc216b94)

Invoke the wireshark and examine the various menus  and controls of the tool:

![EXPT 4 5](https://github.com/22008686/ARP-Attack-and-Network-Sniffing/assets/118916413/a39a5680-37a5-4071-8e70-10d990e11b85)

## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
