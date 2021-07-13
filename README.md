# awesome-infosec-interview-questions

## Table of Contents

* [CyberSecurity](https://github.com/impalanichamy/awesome-infosec-interview-questions#CyberSecurity) 
* [WebApp-Security](https://github.com/impalanichamy/awesome-infosec-interview-questions#WebApp-Security)
* [MobileApp-Security](https://github.com/impalanichamy/awesome-infosec-interview-questions#MobileApp-Security)
* [Api-Security](https://github.com/impalanichamy/awesome-infosec-interview-questions#Api-Security)
* [Cloud-Security](https://github.com/impalanichamy/awesome-infosec-interview-questions#Cloud-Security)
* [Network-Security](https://github.com/impalanichamy/awesome-infosec-interview-questions#Network-Security)
* [IOT-Security](https://github.com/impalanichamy/awesome-infosec-interview-questions#IOT-Security)
* [Secure-Code-Review](https://github.com/impalanichamy/awesome-infosec-interview-questions#Secure-Code-Review)
* [Scenario-based-questions](https://github.com/impalanichamy/awesome-infosec-interview-questions#Scenario-based-questions)

## CyberSecurity
  * What is Cryptography?
  * What is the difference between Symmetric and Asymmetric encryption?
  * What is the difference between IDS and IPS?
  * Explain CIA triad.
  * How is Encryption different from Hashing?
  * What is a Firewall and why is it used?
  * What is the difference between VA(Vulnerability Assessment) and PT(Penetration Testing)?
  * What is a three-way handshake?
  * What are the response codes that can be received from a Web Application?
  * What is traceroute? Why is it used?
  * What is the difference between HIDS and NIDS?
  * What are the steps to set up a firewall?
  * Explain SSL Encryption
  * What steps will you take to secure a server?
  * Explain Data Leakage
  * What are some of the common Cyberattacks?
  * What is a Brute Force Attack? How can you prevent it?
  * What is Port Scanning?
  * What are the different layers of the OSI model? Explain about the different layers?
  * What is a VPN?
  * What do you understand by Risk, Vulnerability & Threat in a network?
  * How can identity theft be prevented?
  * What are black hat, white hat and grey hat hackers?
  * How often should you perform Patch management?
  * How would you reset a password-protected BIOS configuration?
  * Explain MITM attack and how to prevent it?
  * Explain DDOS attack and how to prevent it?
  * Explain XSS attack and how to prevent it?
  * What is an ARP and how does it work?
  * What is port blocking within LAN?
  * What protocols fall under TCP/IP internet layer?
  * What is a Botnet?
  * What are salted hashes?
  * Explain SSL and TLS
  * What is data protection in transit vs data protection at rest?
  * What is 2FA and how can it be implemented for public websites?
  * What is Cognitive Cybersecurity?
  * What is the difference between VPN and VLAN?
  * Explain Phishing and how to prevent it?
  * Explain SQL Injection and how to prevent it?
  * 
## WebApp-Security

## MobileApp-Security

## Api-Security

## Cloud-Security

## Network-Security

## IOT-Security

## Secure-Code-Review

## Scenario-based-questions
  * Here’s a situation- You receive the following email from the help desk:
    Dear XYZ Email user,
    To create space for more users we’re deleting all inactive email accounts. Here’s what you have to send to save your account from getting deleted:
    Name (first and last):
    Email Login:
    Password:
    Date of birth:
    Alternate email
    If we don’t receive the above information from you by the end of the week, your email account will be terminated.
    ### If you’re a user what do you do? Justify your answer.
    This email is a classic example of “phishing” – trying to trick you into “biting”. The justification is the generalized way of addressing the receiver which is used in mass     spam emails.Above that, a corporate company will never ask for personal details on mail.They want your information. Don’t respond to email, instant messages (IM),   
    texts,phone calls, etc., asking you for your password or other private information.You should never disclose your password to anyone, even if they say they work for UCSC,   
    ITS, or  other campus organizations.
    
  * A friend of yours sends an e-card to your mail. You have to click on the attachment to get the card.
    
    ### What do you do? Justify your answer
    
    There are four risks here:
    Some attachments contain viruses or other malicious programs, so just in general, it’s risky to open unknown or unsolicited attachments.
    Also, in some cases just clicking on a malicious link can infect a computer, so unless you are sure a link is safe, don’t click on it.
    Email addresses can be faked, so just because the email says it is from someone you know, you can’t be certain of this without checking with the person.
    Finally, some websites and links look legitimate, but they’re really hoaxes designed to steal your information.
    
  * One of the staff members in XYZ subscribes to many free magazines. Now, to activate her subscriptions one of the magazines asked for her month of birth, second asked for her     year of birth, the other one asked for her maiden name.
    
    ### What do you infer from this situation? Justify.

    All three newsletters probably have the same parent company or are distributed through the same service. The parent company or service can combine individual pieces of    
    seemingly-harmless information and use or sell it for identity theft
    It is even possible that there is a fourth newsletter that asks for a day of birth as one of the activation questions
    Often questions about personal information are optional. In addition to being suspicious about situations like the one described here, never provide personal information    
    when it is not legitimately necessary, or to people or companies, you don’t personally know. 
    
  * In our computing labs, print billing is often tied to the user’s login. Sometimes people call to complain about bills for printing they never did only to find out that the       bills are, indeed, correct.
  
    ### What do you infer from this situation? Justify.

    Sometimes they realize they loaned their account to a friend who couldn’t remember his/her password, and the friend did the printing. Thus the charges. It’s also possible  
    that somebody came in behind them and used their account
    This is an issue with shared or public computers in general. If you don’t log out of the computer properly when you leave, someone else can come in behind you and retrieve 
    what you were doing, use your accounts, etc. Always log out of all accounts, quit programs, and close browser windows before you walk away.
    
  * There is this case that happened in my computer lab. A friend of mine used their yahoo account at a computer lab on campus. She ensured that her account was not left open   
    before she left the lab. Someone came after her and used the same browser to re-access her account. and they started sending emails from it.
    
    ### What do you think might be going on here?

    The first person probably didn’t log out of her account, so the new person could just go to history and access her account.
    Another possibility is that she did log out, but didn’t clear her web cache. (This is done through the browser menu to clear pages that the browser has saved for future 
    use
 
  * Two different offices on campus are working to straighten out an error in an employee’s bank account due to a direct deposit mistake.
    Office #1 emails the correct account and deposit information to office #2, which promptly fixes the problem. The employee confirms with the bank that everything has, indeed, 
    been straightened out.
    
    ### What is wrong here?

    Account and deposit information is sensitive data that could be used for identity theft. Sending this or any kind of sensitive information by email is very risky because   
    email is typically not private or secure. Anyone who knows how can access it anywhere along its route.
    As an alternative, the two offices could have called each other or worked with ITS to send the information a more secure way.
    
  * The mouse on your computer screen starts to move around on its own and click on things on your desktop. What do you do?
     a) Call your co-workers over so they can see
     b) Disconnect your computer from the network
     c) Unplug your mouse
     d) Tell your supervisor
     e) Turn your computer off
     f) Run anti-virus
     g) All of the above
    Select all the options that apply.
    ### Right answer is B & D.
    
    This is definitely suspicious. Immediately report the problem to your supervisor and the ITS Support Center: itrequest.ucsc.edu, 459-HELP (4357), help@ucsc.edu or Kerr Hall 
    room 54, M-F 8AM-5PM. Also, since it seems possible that someone is controlling the computer remotely, it is best if you can disconnect the computer from the network (and 
    turn off wireless if you have it) until help arrives. If possible, don’t turn off the computer.
