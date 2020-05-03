### Insight into OSCP course -

### -- Benefits of OSCP for a Security Analyst -- 
This course will help you to fully understand tactics and strategies hackers use, by giving you hands-on experience in finding security vulnerabilities and exploiting them.

### -- Studdy format --
1. You are provided with video tutorials (17+ hours) and 850-page PDF course going trough basic concepts of enumeration and exploatation of computer systems.
   It is important to master content provided because its scope is exactly within what you can expect from exam.
2. Access to lab trough VPN. (It is good idea to make alias for this in your console configuration to save time)
3. 'Special' build of Kali linux (All tools installed that you will need)
From my experience, other systems can be used, in my case i used BlackArch without any problems and had enough tools to do the job. However debian is considered to have 
easyer learning curve than Arch based systems. 

### -- Lab -- 
1. Windows VM with debuger and vulnorable applications for buffer overflow practice.
2. Public domain with 50+ systems Windows / Unix.
3. IT Department, Development network, Administrative department. (arround 5 targets each)
4. Controll Panel, where you can reset machines if needed.
5. Crack station for passwords you obtain during engagement.
6. Active student forums, where you can discuss boxes with other students if you get stuck.

### -- Current Lab prices (prerequisite for taking exam) --
```
PWK course + 30 days lab access + OSCP exam certification fee -	$999
PWK course + 60 days lab access + OSCP exam certification fee -	$1199
PWK course + 90 days lab access + OSCP exam certification fee -	$1349
```

### -- Bahemoths --
Besides a lot of "normal" boxes in the lab there are few exceptions like behimuths and bosses that we will cover now.
Behimuth is usually Windows Server / Domain controler with a lot of services running, all of them require investigation and can provide some type of access that
can be utilised in exploit chain later.

Exampe NMAP output of such machine -
```
Starting Nmap 7.80 ( https://nmap[.]org ) at 2020-04-18 17:48 CEST
Nmap scan report for 127.0.0.1
Host is up (0.14s latency).
Not shown: 65520 filtered ports
PORT      STATE SERVICE
21/tcp    open  ftp
53/tcp    open  domain
80/tcp    open  http
88/tcp    open  kerberos-sec
135/tcp   open  msrpc
139/tcp   open  netbios-ssn
389/tcp   open  ldap
445/tcp   open  microsoft-ds
636/tcp   open  ldapssl
3268/tcp  open  globalcatLDAP
3269/tcp  open  globalcatLDAPssl
5985/tcp  open  wsman
49154/tcp open  unknown
49155/tcp open  unknown
```

### -- Bosses -- 
There are 5 bosses (or more in new oscp lab) that you will encounter. 
These machines are "Bahemoths" that require long exploit chain, utilizing some type of reverse engieneering or custom exploatation.
What i found usefull here is not to overthink it, these boxes are not full CTF type machines and attack path is rather straitghforward.

### -- Tip for Bosses/Bahemoth --
Taking notes every step of the way. Dont move faster than your notes.
What i do with machines like this is enumerate and gather all information i can before trying to move forward to exploatation.

### -- New OSCP (2020) --
I havent had the pleasure to work within new lab that they rolled out end of january this year. 
In short they added Active Directory attacks and passive information gathering.
You can find whole list of modules they introduced here - https://www.offensive-security.com/offsec/pwk-2020-update/

Lab till 2020 was very old, utilising even in some cases XP systems, powershell wasnt fully operation on large number of systems.
However i beleive 2020 update revived this certificate and added content made it relevant on market again.

### -- Exam Format --
Exam cost is 150$.
Exam takes 24 hours to complete.
You need 70 out of total 100 points to pass.

## Exam points are devided on systems -
```
 1. 25 points for Buffer overflow (Boss)
 2. 25 points for Behemoth 
 3. 2 x 20 point Normal machines.
 4. 10 point macgine (easy)
```
