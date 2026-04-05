lesson 2.1B Prof. Messer - Common ports 
for the CompTIA A+ exam I would need to know port number, protocol and how the protocol is being used (and why it’s important) 
a bit tedious but after time it becomes second nature 

TCP 20   - both for file sharing dont know which is which  
TCP 21 - ;p 
TCP 22 - SSH for encrypted (stuff dont know what exactly)
TCP 23 - Telnet - outdated and not secure and encrypted
TCP 25 - mail sharing? (looked at the video to see it’s simple mail) 
UDP 67 - both for DHCP? automatic configuration of IP, firewalls a subnet mask? (i looked at the video) 
UDP 68  - 
UDP 53 - Domain name system (converts web site names to IP addresses) (DNS) 
TCP 80 - HTTP - Hyper text transfer protocol 
TCP 443  - HTTPS - Hyper text transfer protocol secure (the protocol most sites are using) 
TCP 3389 - remote desktop access (often related with windows but works on any OS) (RDP-Remote Desktop protocol) 
TCP 110 - simple mail version 3 (outdated mailing system?) (SMTP) 
TCP 143 - newer something mail version 4 (allows mail management and new features)
UDP 137 - both for outdates file/printer sharing netbios over tcp/udp protocol?  
TCP 139 - 
TCP 445 - the newer version without netbios? (whatever that means) all three fall into the graph 
Server Message Block - SMB
TCP 389 -  LDAP didnt really get what exactly for it is, I know it makes something like a graph for a organization?

lesson 2.2 Prof. Messer - Wireless Networks 

IEEE is a global  institution that has something to do with wifi? 
the old 802.11 names for ac ax ae for 5/6/7 respectively and updated them to eliminate confusion 
could be 2.4 GHZ 5 GHZ or 6 GHZ with each upgrade having a broader range of them mbits 
20/40/80/160/320 depends on the type of wifi, an example was shown for US spectrum 
how the band broadens with each upgrade,

wifi is not the only wireless connection you can do, there is bluetooth, eliminates any wires and allows for mouses/keyboards, headsets, printers and other peripherals to be wireless you can be in a building move around and still be connected via the wireless bluetooth connection  
then we have 

RFID - radio frequency identification, its pretty much everywhere, is used for the tracking of packages, identification of pets on top of other things, is a physical device found in 2 ways one being as big as a grain of rice, or flat 2D flab with some antennas at the center used more for certain hardware, I think? 

NFC chips (near field communication)  built in phone allows for the wireless processing of payments on top of other functions 

lesson 2.3 Prof. Messer - Network Services 
DNS - domain name service is used to identify as a website’s IP or vice verca, 

DHCP - Domain something forgot the full abbreviation is used to configurate automatically your IP, 
firewalls, on top of other things in your system without having to do it manually 
Dynamic Host Configuration Protocol. The word "Dynamic" is the giveaway.

File Share - basically renaming deleting sharing files on your system, I understand it for example the file explorer and it’s properties on windows, find this kind of murky though

Mail Server - pretty much self-explanatory 24/7 support one of the most important (services?)
running to this day allows the sending and receiving of mail 

SysLog - basically storing large large amounts of data logs, it’s own separate device from what I have seen, 

Web server - using HTTP and HTTPS (the secure one), HTML, HTML 5 on top of other things 

Authentication server - self-explanatory as well, but a centralized custodial server based with a purpose of authentication?

NTP server - time protocol something server really important used for precise data and time on devices 

Database servers I really don’t remember for example what is the difference between a syslog and these server I know companies have to store data and that’s what it about and yeah (?)
you knew what a database was from your notes. You just didn't connect "SQL Server" to "database management system." SQL = database. Always.

Spam gateways - the thing blocking spam and data that is questionable basically like a filter 
the thing on your gmail when you go in and look at your spam folder, the spam, folder is because of the gateways, they are not 100% though can make mistakes, with treating good normal emails as spam and vice versa 

All-in one security appliance - basically a device with multiple security functions like VPN, Proxy, Spam filter, firewall and more 
Load balancers - balances load and deals with outages quickly and efficiently

Proxy server - on behalf of the user it goes and does the task going to the receiving server, executing the task and it verifies the information and if it thinks everything is alright it reports back to the user (intermediary) 

SCADA/ICS - supervised control over server/data/database/logs, at least that’s how I understand it
industrial control systems. The quiz just confirmed that gap. Power plants, factories, water treatment. Not IT servers.

Legacy systems - old most likely important can be 10-20+ years old, treated as a security measure (no!)? treated as a liability but they are critical and often can’t me replaced 
he said learning old can be just as helpful as learning new 

IOT devices (internet of things devices) 
basically a smart refrigarator, amazon’s alexa, a garage remote or a doorbell & more 
stored on a separate server to minimize risk in threat of a security breach

SQL - 
CLARIFICATION: I did skim the names of half of the network services names because I didnt remember the names of all of them, because I watched once and I am doing a memory dump, but any further explanation is all me, also skimmed over to RFID just because I forgot about it 

Claude talk after quiz reviews and stuff 

78% and 70% on first pass. Both above the 65% threshold. You're clear to move forward.
DHCP — Dynamic Host Configuration Protocol. The word "Dynamic" is the giveaway. It dynamically assigns IP addresses. ARP is what maps IPs to MAC addresses. Two different things. One sentence, lock it in.

File server vs mail server — you picked mail server for "shared document storage." Read the question again: "access, store, and manage shared documents." No mention of email. CompTIA loves this — they describe a function and give you a server type that sounds plausible but doesn't match. Slow down on the "which server" questions and match the function exactly, not approximately

SQL Server — you knew what a database was from your notes. You just didn't connect "SQL Server" to "database management system." SQL = database. Always. That's a one-time fix.
SCADA — you wrote in your notes it was "supervised control over servers." I corrected it to industrial control systems. The quiz just confirmed that gap. Power plants, factories, water treatment. Not IT servers.

The pattern in your mistakes: You're not failing on concepts. You're either seeing material the quiz pulled from outside your current lesson, or you're reading questions too fast and picking the first plausible answer instead of the exact right one. That second habit is the one to fix now because it costs you points on every single quiz going forward.

Lesson 2.4A Prof. Messer - DNS Configuration 

key function - provide an IP address when all you know is the name of the site 

DNS records for address (A, AAAA) - domain 

canonical names (CNAME) - only name no domain 

mail exchanger (MX) text (TXT)  - 

Domain Keys Identified Mail (DKIM) - there is domain public key tied to the email and you see if that particular key is trusted and indentified? 

Sender Policy Framework (SPF) - like a whitelist who can send and who can’t 

Domain-based Message Authentication Reporting  Conformance (DMARC)
-if both DKIM, SPF fail treated as a security measure 

here I started reading from the transcript of the video because it got muddy 

13 root clusters over 1000 servers in reality 

GLTDs - generic top level domains (.org.com.net etc.), 275 country domains (.us .uk .ca)
in the video he showed some type of hierarchy on top being . then .com .org or others
then behind the name of the site www. or mail. 

[katie.east.professormesser.com](http://katie.east.professormesser.com/) or a [judy.west.professormesser.com](http://judy.west.professormesser.com/) he showed these I think it’s an example you can base the server of your site In US west or US east or any region in the world, making it accessible, and nowhere has it been said but I think it’s to deal with high latency ping issues (NOPE) (It’s a organizational tree for for naming or subdomains) 

dig - allows queries for a server, gives an answer to a question (how the DNS server is configured) 
on windows we can do nslookup for the same command 

he then showed if you made a query for his site, it shows 3 different IP addresses so if one goes offline you can use the others 

RR - Resource Records - information for site/configuration (that’s why when we make a query information is being returned) 

he didn’t have raw text configuration file he had a  web based front end 

A or AAAA records they determine the IP address A (version 4) AAAA (version 6)

the time to live (TTL), which is how long someone will remember this IP address changes will eventually be made to everyone in maximum 15 minutes if the time to live is 15 minutes, because it will update when they request the IP address again (could be done with both A or AAAA pretty much same process) 

CNAME - canonical names for chat, www and more, different names same server 

MX records - mail exchanger record, allows to send and receive emails from your domain 
ex. [william@claude.ai](mailto:william@claude.ai) 

TXT - can enter text in the domain system, things you would want others to access, is used for verify email messages or minimize spam, one of the TXT files is 

DKIM record - Domain Keys Identified Mail Record (encryption? public and private key?) 
 **the domain owner publishes a public key in DNS. When they send an email, the server signs it with the private key. The receiver checks the signature against the public key in DNS. If it matches, the email is legit. That's it.**

SPF - Sender Policy Framework - verifying who can send and who can’t (another TXT record) 

DMARC (TXT Record) - Domain-Based Message Authentication, Reporting and Conformance 
if the above 2 fail, this allows rules of sending unverified mail to spam, or not receiving it all? 
 **It tells receiving mail servers what to do when both DKIM and SPF checks fail. Options are: do nothing, quarantine it, or reject it entirely. It's the policy layer on top of the other two.**

**The email security trio in one line: SPF says who's allowed to send. DKIM proves the message wasn't tampered with. DMARC says what to do if either fails**.

**CompTIA loves testing those three against each other.**

Lesson 2.4B Prof,. Messer - DHCP (M, CAF, NIC) 

DHCP - Dynamic Host Configuration Protocol
Automatically configuring an IP address, subnet masks, firewalls, etc. **DHCP doesn't configure firewalls. You wrote "firewalls" in your first line — swap that out mentally.**
before everyone was configuring manually and when managing a lot devices that happened to be a tedious process, but in 1997 DHCP was founded 

the process of automatic configuration is called DORA 
The configuration happens to be a four step process 
D - discover - your device is in discovery mode when booted up 
O - offer - the Protocol give your device an offer for an IP
R -request - your device chooses one of the offers, and sends a message to the DCHP servers that the offer is accepted 
A -acknowledge - the DHCP server sends a confirmation back that the IP is now in use 

DHCP scope - IP address range (and all configuration options) (excluded ones also so 2 devices 
 **The scope is the full configuration package: IP range, subnet mask, default gateway, DNS servers, lease time, exclusions — everything.**
don’t use the same at 1 time) (predefined list of IP addresses)

DHCP pool - large amount of IP addresses or the area that the server can actively assign 
**The pool is just the available IP addresses within that scope that haven't been excluded or reserved. Scope is the whole box, pool is what's left inside it to hand out.**
DHCP reservation - self explanatory, device being assigned (reserved) the same address every single time 
you can make all changes in a DHCP server when managing devices no need to be manually doing on the device 

MAC address - one time address of a device assigned to it when created every device has it 
so to configure a device on the DHCP server we assign it’s MAC address to be reserved to this IP every single time 

**Scope vs pool — you have them slightly overlapping. The scope is the full configuration package: IP range, subnet mask, default gateway, DNS servers, lease time, exclusions — everything. The pool is just the available IP addresses within that scope that haven't been excluded or reserved. Scope is the whole box, pool is what's left inside it to hand out.
DHCP doesn't configure firewalls. It configures IP address, subnet mask, default gateway, and DNS server. You wrote "firewalls" in your first line — swap that out mentally.

Good catch. The question is poorly worded.
You're right that technically the pool is the available IP addresses and the scope is the full configuration package. But CompTIA uses "scope" as the answer when they describe "the defined pool of IP addresses that a server can assign" because in CompTIA's world, scope is the broader correct term that encompasses the pool.
Think of it this way: there's no exam question where "pool" is the right answer over "scope." Scope is always the safer pick on CompTIA exams when they're asking about DHCP address ranges. Pool is a concept within the scope, but CompTIA treats scope as the primary term.**

Lesson 2.4C Prof. Messer - VLANs & VPNs

****LANs - Local Area Networks - group of devices in the same broadcast domain 
VLAN - Virtual Local Area Network - group of devices in the same broadcast domain, separates devices logically not physically like (LANs) to separate LANs you need another physical device,  
but when VLANs come in to play you can separate them (remotely?) 
**Not remotely exactly. VLANs are configured on the switch itself. The point is you don't need to buy a separate physical switch for each group. One switch, multiple virtual networks configured through software. The separation is logical, not physical. That's the whole value.
Configuring VLANs** 
 

for this example you have 
VLAN 1 - Room A (gate room) 
VLAN 2 - Room B (dialing room)
VLAN 3 - Room C (infirmary), I think the names are just for the example that’s why the parentheses)

VPN - Virtual Private Network - encrypts all the data that is being sent over the network 

VPN Concentrator - encrypts and decrypts data in real time - can hardware or software

Client-to-site VPN concentrator - you being the client encrypting your data and receiving encrypted data and decrypting it for you 

Site-to-site VPN concentrator - always on or almost, eliminates the internet and is
from an example a corporate network to a remote site using 2 separate concentrators 

**Client-to-site VPN: You're at home on your laptop. You connect to your company's network through a VPN. One person connecting to one network. You turn it on when you need it, turn it off when you're done. That's client-to-site.

Site-to-site VPN: Your company has an office in Sofia and an office in London. Both offices need to share the same network resources constantly. A permanent VPN tunnel connects the two office networks together 24/7. No individual person is connecting — the two networks themselves are connected. That's site-to-site.

Simple distinction: client-to-site is one person to a network. Site-to-site is one network to another network.**

Lesson 2.5 Prof. Messer - Network Devices 

Routers - routes traffic between IP subnets, connects different networks - LAN, WAN, copper, fiber 
routers inside of switches called - layer 3 switches 

Switch - connects local devices to create a local network, uses ASIC, can have routing functionality (multilayer switch) 
ASIC - Application-specific integrated circuit 

POE - Power over Ethernet - delivers both data connection (network) and electrical power 

Unmanaged switches - simple switches, you plug it and it works, can’t configurate it only becomes one VLAN, little integration (no logs stored and etc.), low price point 
(layer 2 switches I guess) 

Managed switches - larger device, offers multiple VLANs, offers configuration 
-offers traffic prioritization web traffic voice traffic gets higher priority over web traffic for example
-offers redundancy (multiple switches if one switch fails you can use another so you don’t have an -outage), (interconnected with other switch via 802.1Q, 
-allows for port mirroring, mirror traffic?  **not "mirror traffic" with a question mark. It's copying all traffic from one port to another port so you can monitor or analyze it. Think of it as a wiretap on a specific network connection. Used for troubleshooting and security monitoring.**
-allows for remote management (SNMP - Simple Network Management Protocol) 

Access point - allowing for wireless connection (bridged communication) 
a wireless router is a router and an access point in a single device 

Cable infrastructure - using a patch panel (RJ45 if you need to change connections) (like a motherboard of an office, everything connected to one block (patch panel) 

Patch Panel - combination of punch down blocks and RJ-45 connectors, permanent connection and you know that connection probably won’t experience problems

Firewall - decides if it allows or disallows traffic (filters by port number) (OSI 4 layer), 
can encrypt traffic in and out of a network 
can be a proxy, most can be a layer 3 device (router) 

PoE - Power over Ethernet - phones, cameras, wireless access point (1 wire = data & electricity)
commonly marked on the device, so you would know for your switch (PoE marked)
15.4 watts DC power, 350 mA max current (milliamperes)

people realized they need more power for their remote devices that’s why 
POE+ - 25.5 watts DC power, 600 mA max current was made 

POE++ (laptops and such)
- 51 W (Type 3) 600 mA max current 
- 71.3 W (Type 4), 960 mA max current 

POE++ can power POE or POE+ devices, but a POE++ device can’t be powered by a POE or POE+ 

Cable Modem - providing a ethernet connection on the other end while receiving cable data 
DOCSIS - Data Over Cable Service Interface Specification, uses high speed (up to 1 gigabit/s) 
because of the high speed data it offers multiple services - data, voice, video, 

DSL modem - Digital Subscriber Line - uses telephone lines, 
-download/upload speeds are asymmetric  (200mbit/s - 20 mbit/s are common) 
~10,000 foot limitation from the central office 
faster speeds if you are closer to the office 

ONT - Optical Network Terminal (fiber, in the ground, converts fiber connection to copper connection to use) 
often times uses DEMARC - has a demarcation point - point and a boundary where a service’s network wiring and obligations about problems and such end and the customer is responsible for any issues or wires (outside of your house is service’s responsibility, inside is yours) 
(LINE OF RESPONSIBILITY)  

NIC - Network Interface Card (specific to the network type), it’s connecting devices and servers directly to the Ethernet network, has it’s own MAC address 

**The layer 3 switch concept — a switch that can also route. CompTIA loves asking "which device can perform both switching and routing?" The answer is multilayer switch or layer 3 switch. That's a free exam point if you remember it.

Both are technically correct — the difference is theoretical max vs what actually reaches the device after power loss over the cable. For the exam, know the IEEE spec numbers: Type 3 = 60W, Type 4 = 100W. Those are what CompTIA uses.

On the cable vs DSL mix-up: One clean distinction to lock in:**

**Cable modem = coaxial cable, shared bandwidth (you share with your neighbors), carries TV signals. DSL modem = telephone lines (twisted-pair copper), dedicated bandwidth (your line is yours), distance-dependent speed.**

**The key exam trick: cable is shared, DSL is dedicated. That's the one CompTIA always tests. Everything else follows from that.

PoE injector — now you know it exists. It's a device that adds PoE power to a non-PoE switch. Sits between the switch and the device, injects power into the ethernet cable. One sentence, done.**

Lesson 2.6A  Prof. Messer - IPv4 and IPv6

IPv4 - Internet Protocol version 4 (primary protocol for almost everything) 
-OSI Layer 3 address
-32 bits, 32 bits = 4 bytes 
8 bytes = 1 bit = octet 
maximum decimal value is 255 
octet - 8 number string of numbers to identify numbers in binary? (ex. 192 = 11000000)

there are over 20 billion devices connected to the internet, but IPv4 support only 4.29 billion. that’s
a problem, that’s where Network Address Translation (NAT) come in to play 

public addresses talk to public addresses on the internet, and private addresses talk to private addresses on their own network, that means none of these private private addresses go towards the total pool of IPv4 (we can have thousands of devices but when we need to communicate to the internet we use a single IPv4 address 

the range of address is configured via RFC (Request for Comment) - 1918
-range 10.0.0.0 through 10.255.255.255 this allows us a combination of over 16 million different addresses that we could have inside of our network
-172.16.0.0 through 172.31.255.255. This combination gives us just over 1 million addresses
-your local device probably assigns IP addresses using the last private range, 192.168.0.0 through 192.168.255.255. This provides a total number of just over 65,000 addresses. 

IPv6 - Internet Protocol v6 - 128-bit address 
-340 undecillion addresses in total 
-removes any limitation we previously had with IPv4 
-structure also different, instead of decimal like the previous version hexadecimal is being used 
128 bits = 16 bits, the binary string look something like this (111111110100100000:00000000000000:000000000000000000:000000000000000. and more)  
DNS becomes important because you can’t memorize them
no subnetting because you don’t need it
the first 64 bits (first half of the string becomes the prefix (/64)
last 64 bits (second half) is the host ID 

Lesson 2.6B Prof. Messer - Assigning IP Addresses 
-every device needs a IP address (ex. 192.168.1.165
-every device needs a subnet mask - to determine which subnet it’s on (255.255.255.0) 
-every device needs a Default Gateway - the router that allows you to communicate outside of your local subnet 
the default gateway must be a IP address on the local subnet 
all 3 are provided via your internet administrator (most of the time), these are big 3 to communicate on your local subnet and outside of it 

Static IP addressing - static IP (doesn’t change), need to be precise when configuring it, difficult to manage, not scalable, avoid it if you can, there are better ways on manual IP addressing 
(DHCP reservation - links the MAC address of the device to a particular IP , always) 

APIPA - Automatic Private IP Addressing 
-no forwarding by routers 
-APIPA uses 169.254.0.0 through 169.254.255.255, first and last 256 addresses reserved 
-when DHCP isn’t responding 
-uses ARP request to confirm if the address isn’t currently being used 

Turning dynamic into static 
DHCP assigns an IP address from the first available one from a large pool 
you may not want your IP address to change though (server,. printer or other) |
disable DHCP - configure all the IP address information manually 
-better - configure an IP reservation on the device and to associate it’s mac address with an IP
 
 **32 bits total, split into 4 groups of 8 bits. Each group of 8 bits = 1 byte = 1 octet. So an IPv4 address is 4 octets. The octet isn't an "8 number string to identify numbers in binary" — it IS 8 binary digits. 192 in binary is 11000000, and that's one octet.

APIPA isn't just "when DHCP isn't responding." It's specifically what happens when a device is configured to use DHCP but can't find a DHCP server.**

**CompTIA loves testing this: "A user can communicate with local devices but not the internet. The IP address starts with 169.254. What is the problem?" Answer: DHCP server is down or unreachable.

92%. That's your highest score yet.
The Class A/B/C mix-up is pure memorization. One line to lock it in:
10.x.x.x = Class A (biggest range, 16 million addresses). 172.16-31.x.x = Class B (medium, 1 million). 192.168.x.x = Class C (smallest, 65,000).
A, B, C = big, medium, small. That's it. You won't miss it again.**

Lesson 2.7A Prof. Messer - Internet Connection Types 

Satellite networking - communication to a satellite
High cost relative to terrestrial networking 
asymmetrical 100 mbit down and 5 mbit/s up are common, used for difficult to network sites
usually high latency because you need to send information to the satellite and it sending back to you (250 ms up 250 ms down) 
starlinks are closer to earth so the connection is faster 25-60 ms 
not always perfect - connectivity problems if a storm brews out (called rain fade) 

Fiber - high speed data communication (frequencies of light) 
higher cost than copper, communicate over long distances 
good for a WAN (ex. large corporate building) 
before it was exclusive but now it comes to your home 

Cable connection  (type of copper) 
-broadband - transmission across multiple frequencies (stream,voice,tv) 
very high speed 

ADSL  - Asymmetric Digital Subscriber Line 
called asymmetric because download speed is faster than the upload speed 
200 mbit/s down and 20 mbit/s up are common 
10,000 foot limitation from the central office 

Cellular networks 
-separates land into cells 
-tethering - turn your phone into a wireless router 

WISP - Wireless Internet Service Provider 
many different ways to use (meshed 802.11 whatever that means, 5G home internet. proprietary wireless) need an antenna 

**DSL = asymmetric speeds, distance-dependent.

Broadband: Just means "high-speed internet." That's it. Any internet connection faster than the old dial-up is broadband. Cable, DSL, fiber, satellite, cellular — all broadband. It's not a technology, it's a category.

Coaxial cable: The thick round cable with the screw-on connector that carries cable TV into your house. Same cable also carries internet data for cable modem connections.**

Lesson 2.7B Prof. Messer  - Network Types 
there are plenty of networks - LAN, WAN, PAN, MAN, SAN, WLAN 

LAN - Local area network - high speed, usually short range the type of network at your home 

WAN - wide area network - slower speed, really large range 

PAN - personal area network - bluetooth and more 

MAN - metropolitan area network - smaller than WAN, larger than LAN, usually government owned

SAN - forgot the acronym - look and feels like a database, large bandwidth (storage area network!)

WLAN - Wireless local area network - 802.11, you can move around a building but same connectivity 

**SAN — Storage Area Network, not Storage Access Network. Close though. It's a dedicated high-speed network specifically for connecting storage devices to servers. Think of it as a private highway just for data storage traffic, separate from the regular network. Not a database — it's the network that connects to the storage.**

**Everything else is clean. LAN, WAN, PAN, MAN, WLAN all correct.**

Lesson 2.8 Prof. Messer - Networking tools 

**Crimper** — squeezes a connector onto the end of a network cable. You strip the wire, arrange the tiny colored wires inside, shove them into an RJ45 connector, and crimp it shut. Makes custom ethernet cables.

**Wi-Fi analyzer** — shows you all the wireless networks around you, what channels they're on, signal strength, interference. Used to figure out why wifi is slow or dropping.

**Tone generator** — you plug it into one end of a cable and it sends a signal. You walk to the other end with a probe that makes a sound when it detects that signal. Used to trace which cable goes where when you're staring at 200 cables in a wall and need to find the right one.

**Punch-down tool** — pushes a wire into a slot on a patch panel or wall jack. The slot has a blade that cuts through the wire insulation and makes the connection. That's how cables get permanently connected to wall outlets in offices.

**Cable tester** — plug both ends of a cable in, it tells you if the cable works or if a wire inside is broken or crossed.

**Loopback plug** — plugs into a network port and sends the signal right back to itself. Tests whether the port itself is working without needing another device on the other end.

**Network tap** — sits between two devices on a cable and copies all the traffic passing through for monitoring. Like a wiretap for network data.

**Your job will be in the cloud — you'll probably never touch a crimper in your life. But CompTIA tests it anyway because A+ is meant to certify you on hardware fundamentals too. Just memorize enough to pass the questions and move on. Don't stress about understanding these deeply.

None of these require deep understanding. CompTIA will show you a picture or describe a scenario and ask which tool you'd use. Match the problem to the tool. Do the quiz, score what you score, and move on. This is not worth spending mental energy on**.
