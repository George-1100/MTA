# Malware traffic analysis in the origin logger(originLogger is key logger from Agent tesla family)
# Description
The victim Download keylogger(originlogger) from some malicious website unknowingly. The keylooger take victim's email client client user name and passwords
and web login credencials such us amazon

1. Run a windows on VMware
2. Downd and install wireshark

   Questions
1. What is the victim’s IP address?
2. What is the victim’s MAC address?

![MAws1](https://github.com/George-1100/MTA/assets/76154087/fc274b62-7072-4a3b-bcaf-726e4e49e764)

In ARP request contain Victim IP address and Mac Address

3.What is the victim’s Windows host name?

![MAws3](https://github.com/George-1100/MTA/assets/76154087/7192e0ab-6976-41d9-9b95-4327fdfc319f)

I use match frames filter for identify the default windows host name (desktop) 

4. What is the victim’s Windows user account name?
5. How much RAM does the victim’s host have?
6. What type of CPU is used by the victim’s host?
7. What is the public IP address of the victim’s host?
8. What type of account login data was stolen by the malware?
   Email client login and website account credencials
   
   ![MAws4](https://github.com/George-1100/MTA/assets/76154087/e4302675-2ea6-4c15-b8ae-979cda62090e)
   
 HTTP request contain png image maybe victim send the file to somone. the request contain all rest of information. 

   9. When did the malicious traffic start in UTC?

       ![MAws2](https://github.com/George-1100/MTA/assets/76154087/94e5bd52-84eb-4253-9770-815ec5d4dda7)

