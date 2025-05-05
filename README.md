```
NAME: PRADEEP V
REG NO: 212223240119
```



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
![arp-a](https://github.com/user-attachments/assets/ddf4c952-ee40-4769-b7d5-725b1aed8e2c)
![arp -a 1](https://github.com/user-attachments/assets/418733aa-f3a6-4713-837d-adead14f7aa7)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![arpspoof](https://github.com/user-attachments/assets/f9699724-ab99-42d5-bac0-85ca8e3c9b99)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![ftp _ip_](https://github.com/user-attachments/assets/e35266c5-1b81-44a1-b987-7a99130cb813)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![dsniff](https://github.com/user-attachments/assets/8c1c9fc5-b4d4-448e-97a9-94ac7ab54458)



Invoke the wireshark and examine the various menus  and controls of the tool:

## OUTPUT
![og wi](https://github.com/user-attachments/assets/c662675c-75b1-451b-91cc-362eb3ac4dd2)

## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:
## OUTPUT:
![og wire](https://github.com/user-attachments/assets/481ca386-be94-49bd-b58f-f75ee570f4d5)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
