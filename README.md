# Penetration Tester

## Intro to Offensive Security (Red teams and penetration testers)
Hack your first website (legally in a safe environment) and experience an ethical hacker's job.  
**Offensive security** is the process of breaking into computer systems, exploiting software bugs, and finding loopholes in applications to gain unauthorized access to them.   
On the flip side, there is also **defensive security**, which is the process of protecting an organization's network and computer systems by analyzing and securing any potential digital threats.  

### Hacking your first machine
We will use a command-line application called **"GoBuster"**  
Type the following command into the terminal to find potentially hidden pages on FakeBank's website using GoBuster (a command-line security application).

```gobuster -u http://fakebank.com -w wordlist.txt dir```  

In the command above, -u is used to state the website we're scanning, -w takes a list of words to iterate through to find hidden pages.

#### Careers in cyber security  
Hackers (security consultants)  
Defenders (security analysts fighting cybercrime)  

**Offensive security roles:**  
**Penetration Tester** - Responsible for testing technology products to find exploitable security vulnerabilities.
**Red Teamer** - Plays the role of an adversary, attacking an organization and providing feedback from an enemy's perspective.
**Security Engineer** - Design, monitor, and maintain security controls, networks, and systems to help prevent cyberattacks.  

## Intro to Defensive Security  
Introducing defensive security and related topics, such as threat intelligence, SOC, DFIR, and SIEM.  
**Offensive security** focuses on one thing: breaking into systems. Breaking into systems might be achieved through exploiting bugs, abusing insecure setups, and taking advantage of unenforced access control policies, among other things. **Red teams and penetration testers** specialize in offensive security.

**Defensive security** is somewhat the opposite of offensive security, as it is concerned with two main tasks:  
- Preventing intrusions from occurring  
- Detecting intrusions when they occur and responding properly  
Blue teams are part of the defensive security landscape.
