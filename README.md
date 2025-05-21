Penetration testing is an important part of any complete security strategy since it assist organisation in identifying and mitigating potential risks before attackers can exploit them. Organisation may guarantee that they are effectively protecting their assets and limiting        risk of a security breach by implementing a strategic approach to penetration testing.

This Portfolio will define some the strategies organisation and businesses need to develop to guarantee the security of their information assets. Four domains would be discussed. The domains are System hacking, Foot printing and Reconnaissance, Hacking Mobile Platform, and Distributed of Denial of Service (DDOS). Each domains contains mitigation techniques in addressing the vulnerabilities discovered.

Attack 1: System Hacking
System hacking is the unauthorised access and manipulation of computer systems or networks. It involves exploiting vulnerabilities in a system's security to gain access to confidential information, disrupt operations, or cause damage to the system. The state of security is a state of protection from harm or destruction. The term is also used to describe network security.


To ensure compliance with legal and ethical guidelines, this exercise is conducted within a virtual machine environment using VirtualBox. The target for hacking is Mr. Robot, which is a purposely vulnerable application intended to assist ethical hackers and students in testing their penetration testing skills. Various tools are employed in this exercise, including Kali as the operating system, Netdiscover, Metasploit, Burp Suite, FoxyProxy, Hydra, Network Mapper (Nmap), Nikto, Gobuster, John the Ripper, and others. For detailed information on the utilisation of these tools, please refer to the Appendix of this portfolio.

System hacking involves exploiting vulnerabilities in a system's security to gain unauthorised access to the system, its data, and its resources. To gain access to the system, the following step Methodology will be taken:
1.	Reconnaissance: To choose the most effective technique for obtaining access, it is necessary to identify the target system's vulnerabilities, ports, and services.
2.	Enumeration: the process of discovering a live port or service in a system. The tools that will be used for this exercise include Nmap, which is popularly known for scanning target machines
3.	Password Cracking: This involves using various methods to discover or guess passwords to gain access to user accounts or administrator accounts, such as Hydra, John the Ripper, hashcat, etc.
 
4.	Exploiting software vulnerabilities: This entails exploiting software defects in the system, such as out-of-date software or unpatched security holes.
5.	Maintaining access or Privileges Escalation: Once access to the system has been gained, the hacker may install backdoors or rootkits, change passwords to maintain control over the system.
6.	Clear track: This involves clear the traces of the attack launch against the target. This           stage helps the attacker to delete all communication to avoid being caught.

Attack 2: Foot printing And Reconnaissance
Foot printing is the practice of gathering information about a company or network from publicly accessible sources such as social media, websites, job listings, and other comparable sources. It is the first phase in the hacking process and assists the attacker in identifying potential vulnerabilities and targets for attack.

Reconnaissance, on the other hand, refers to the active scanning of a target network or system to learn about its vulnerabilities, weaknesses, and potential attack vectors. Reconnaissance is a term used to describe the detecting procedures used to obtain information about a target such as Port scanning, vulnerability scanning, and network mapping are examples of reconnaissance techniques Attackers can obtain information via web pages, search engines, the advanced search tool within a website, publicly traded corporations, or by extracting a website archive.

Foot printing and reconnaissance are both crucial elements in the ethical hacking and penetration testing process. They enable security professionals to discover potential vulnerabilities in their networks or systems and remedy them before attackers exploit them.
For this report, Passive and active techniques were adopted as means of gathering information about the target which would be detailed in the Appendix.

Attack 3: Hacking Mobile Platform
Hacking mobile platforms refers to the act of gaining unauthorised access to a mobile operating system or its associated hardware components, such as smartphones, tablets, and other mobile devices.  Hackers frequently employ a variety of tactics to exploit flaws in the mobile operating system, apps, or the device itself, with the ultimate goal of stealing sensitive information or remotely manipulating the device. Attackers have developed malicious software and new techniques to target Android users. As a result, various scholars have confirmed the use of existing methodologies or proposed new tools that may be more effective in correctly identifying malicious apps

1.4 Attack 4: Distributed Denial of Service (DDOS) Attack
Distributed denial of service attack is a type of attack where multiple compromised systems, often referred to as a botnet, are used to flood a target website or network with traffic, making it unavailable to its intended users. Because of their distributed nature, DDoS attacks are notoriously difficult to defend against.

The scope of the attack is within Microsoft Windows hosted on VMWARE and VirtualBox. The tools used for the attack which will be shown in the appendix are Kali Windows 8, Windows 7, and Windows 10, Higher Orbit Ion Canon and Hping3. Window 10 is the target device while Windows 8 and 7 are the attackers(Botnet) performing the attack. The Vulnerabilities exploited in the attack were the result of an ineffective firewall on the system to prevent the attack from taking place.
