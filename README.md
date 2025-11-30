# SKILL-HORIZON-Assignment-5
1) Nmap scan:-
 Command:- nmap -sn http://testphp.vulnweb.com
Host is up
testphp.vulnweb.com ip address (44.228.249.3)
Port 80(tcp) open
Service:(tcpwrapped)

2) Web Fingerprinting-using WHATWEB
Command:- whatweb http:// -v testphp.vulnweb.com
Found
Title:- Home of Acunetix Art
ip:- .228.248.3
Country:- United States(US)
String       : text/JavaScript
Version      : 5.6.40-38+ubuntu20.04.1+deb.sury.org+1


3) Directory discovery using gobuster
Directory  STATUS        SIZE      REDIRECT
/admin    (Status: 302) [Size: 0] [--> /login.jsp]
/aux      (Status: 200) [Size: 0]
/bank     (Status: 302) [Size: 0] [--> /login.jsp]

/images   (Status: 302) [Size: 0] [--> /images/]

/pr       (Status: 302) [Size: 0] [--> /pr/]

/static   (Status: 302) [Size: 0] [--> /static/]
/util     (Status: 302) [Size: 0] [--> /util/]




