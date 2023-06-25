# Analysis: joingrupjawatan.com

## 1. Absctract:
A Telegram group directory website for vacant jobs and government assistance. The website displays different pages according to the device. If displayed from a smart phone, the page displays only one page with a "Join Group" button that takes the user to the Fake Telegram Login Page (considered phishing page). And If it is displayed through a website (computer) then it will list Telegram group links that lead to ClickJacking for advertising promotions and others.

## 2. Category: Phishing & Click Jacking

## 3. Threat Level: Medium

## 4. Impact Level: Medium

## 5. Digital Footprint Analysis:
### 1. Whois Information:
1. Registrar: CV. JOGJACAMP (Indonesia)
2. Registered: 10 Jun 2023
3. Expired: Tamat: 10 Jun 2024
4. Nameserver: ns1.idwebhost.com, ns2.idwebhost.com
5. Registrant: Kulturo (Jawa Barat Indonesia)

### 2. Basic DNS:
1. A Record IP: 202.52.146.246
2. NS IP Address: 202.52.146.165, 202.52.146.165
3. Reverse PTR: 246.146.52.202.in-addr.arpa ->  bokoharjo.idweb.host
4. MX IP: joingrupjawatan.com -> 202.52.146.246 [p=0]
	
### 3. DNS Enumeration:
**No results on basic DNS Enum**

### 4. Basic Port Scanning
List of open port (nmap -sV -p1-65535 -O):
1. Remote Access:
- 21 (ftp), 4422 (ssh OpenSSH 8.0)

2. Mail Related:
- 110, 143, 465, 587, 993, 995

3. Database Related:
- 3306 (MySQL 5.5.5-10.5.20-MariaDB)

4. Http Service:
- 80 (LiteSpeed), 443 (LiteSpeed), 2078 (ssl CPanel)

5. Web Host:
- 2078 (ssl CPanel)

6. Uncommon:
- 111, 2077, 2082, 2083, 2095, 2096

7. OS Detection: Linux 3.10 - 3.12 (93%)

### 5. Service Base Public Exploit Analysis
No public exploits match to the nmap port/service scan results.

### 6. Zero Exploit Script
No exploit has been perfromed

## 6. Threat Analysis


## 7. Hypothesis
1. The website has been developed wisely and tricky. The person behind this website is expert in development. 
2. Currently all information appoints to Indonesian personal/organization which they use IP from Indonesia ISP, Datacenter from Indonesia's company called IDWebHost (idwebhost.com).
3. No public exploit were found in Exploit-DB. This datacenter has kept their client server safely.
4. The reverse PTR address returns to "bokoharjo.idweb.host" and the word "bokoharjo" is a place in Yogyakarta, Indonesia. This doesn't mean the scammer are from here but maybe the IDWebHost has multiple server co-location across Indonesia.
5. The IP address in A record is different with the NS record. This means the server behind "joingrupjawatan.com" is the same VPS/Server as the provided by IDWebHost.

## Public Response Plan
To anyone who has been trapped and become a victim, here's a few step you can do:
1. Change your Telegram password.
2. Remove all login device except your phone (Go to settings > devices > terminate all).
3. Create a Police report if the hacker post something illegal on your name.
4. Create a public announcement which URL has hacked you.

## Public Action Plan
### Legal Action
If your loses too much, maybe your credibilties, career etc, then you can bring this case to court. But you will need to get the IDWebHost's coorperation to start with. Taking this case to court will cost us a lot. For those who wants to take revenge, we can take down this site with report it to IDWebHost. Then it's on IDWebHost whether to take this site down or not.

Usually web hosting company will remove the site. If not, then we can report the web host integrity to public to make sure all users banned the web hosting company.

### Illegal Action
From this external basic information, we can take down this site is DDoS attack. But as we all knows that DDoS only work for temporary down time. Taking this action is explicitly illegal and we forbid any of MyOPECS members to do so. We, MyOPECS do not held responsibilities of the risk or misconduct of this DDoS activities.

