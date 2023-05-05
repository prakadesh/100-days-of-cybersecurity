# #100DaysOfCybersecurity Log -[PRAKADESH]

The log of my #100DaysOfCybersecurity challenge. Started on [April 19, Wednesday, 2023].


## Log

### R1D1 
completed my first day of learning cybersecurity 
by completing the **Introduction to Cybersecurity course** offered by Cisco, where I learned about a variety of topics related to cybersecurity,
- Different types of attacks and attack vectors
- Defense mechanisms such as firewalls, IDS, IPS, and DPS
- Security models like Bell-LaPadula, Biba, and Clark-Wilson
- Basic security controls like authentication, authorization, and encryption

The course emphasized the importance of understanding and minimizing attack pathways in order to better protect organizations from cyberattacks. It also stressed the need for strong passwords, software upgrades, and security awareness training for staff members.

Overall, I found the course to be very informative and a great foundation for further learning in the cybersecurity field.

[My Credly Badge](https://www.credly.com/badges/05eaee04-7371-46d7-9f8d-8bf19cecc011/public_url)


Here are two additional resources I found helpful:
- Introduction to Classic Security Models - https://www.geeksforgeeks.org/introduction-to-classic-security-models/
- Understanding Attack Vectors: The Top 10 Most Common Paths to Attack - https://www.upguard.com/blog/attack-vector
### R1D2
completed my day 2 on  **The frameworks and standards** where i learned on:

- The NIST Cybersecurity Framework provides a flexible, risk-based approach to cybersecurity that can be customized to an organization's specific needs.

- ISO/IEC 27001 is an international standard that provides a comprehensive framework for establishing, implementing, maintaining, and continually improving an information security management system (ISMS).

- CIS Controls is a set of 20 critical security controls that organizations can use to protect their systems and networks against cyber attacks.

- PCI DSS is a set of requirements that organizations must follow if they handle credit card data.

- HIPAA Security Rule provides guidelines for protecting the privacy and security of protected health information (PHI) in the healthcare industry.

- COBIT is a framework for governance and management of IT that provides a holistic approach to IT security.

- ITIL is a set of best practices for IT service management that includes a security management process.

- CSA Security Guidance provides best practices for securing cloud computing environments.

- OWASP provides a set of guidelines for developing secure web applications.

- SANS Critical Security Controls is a set of 20 controls that organizations can implement to improve their cybersecurity posture.

### R1D3
completed my day 3 on  **cybersecurity threats and vulnerabilities**

learned on **Introduction to Cybersecurity Tools & Cyber Attacks** by IBM on coursera

### R1D4
completed my day 4 on Symmetric encryption learned that 

- It is one of the fundamental building blocks of cryptography that provides confidentiality, while data integrity and authenticated encryption provide both confidentiality and data integrity.

- Symmetric encryption is a technique in which the same key is used for encrypting and decrypting data. The security of symmetric encryption relies on keeping the key secret. However, this technique does not provide any assurance about the integrity of the data.

- Data integrity is the assurance that data has not been tampered with during transit. To ensure data integrity, authenticated encryption is used, which provides both confidentiality and data integrity. Authenticated encryption uses a symmetric encryption algorithm and a message authentication code (MAC) algorithm. The MAC algorithm produces a tag that is attached to the encrypted data to ensure data integrity.

- There are different symmetric encryption algorithms such as AES, DES, and Blowfish, while there are different authenticated encryption algorithms such as AES-GCM, ChaCha20-Poly1305, and AES-CCM. Both symmetric encryption and authenticated encryption are essential to ensure the confidentiality and integrity of data in various applications such as communication, storage, and e-commerce.

### R1D5-D8
completed these days studying for my exams on 
- Cloud Security 
   - I learned on encryption and decryption algorithms RSA, PKI,x509 certification
   - also on the virutalization and those vulnerablity along with attacks based on it 
- Software Vulnerability Testing 
   - learned on neccesity of auditing 
   - auditing and black box testing
   - vulnerability assesment and testing methods 
   - memory corruption vulnerability
   - vulnerability assesment methods testing process
### R1D9
completed my day 9 after completing my exam started on learning network fundamental
- types of networks
- Types of Network Components
- Types of Network Media
- Types of Geographical distance Networks
- Open Systems Interconnection (OSI) model
continue learning the remaining on d10 
### R1D10
completed my day 10 on Firewall technology
- packet filtering we can make decision based on the source and destination parameter alone
- also we block the inbound tcp segment with ack=0 to prevent external clients from making tcp connection with tcp but allow internal to connect with external
- APPLICATION gateway are also a type of packet filtering on a application data as well as on the they are present at the top of the osi stacks as well as on the ip transport layer this can cause masquerade or spook the IP address. packet generally have all or noting policy for udp
- xml gateway is a transport protocol that moves documents, communication artifacts through conventional firewalls without inspection. port 80 is used so a standard firewall cannot differentiate between XML traffic and a communication tool, an external web server. So a standard firewall cannot differentiate between XML traffic and a communication tool, an external web server. There's a challenge within that. XML gateways, which are generally installed just inside the first firewall in a DMZ takes a look at the payload of the XML message for compliance, for security policy compliance. So fundamentally, this is the XML message to stack
- stateless firewalls has no concept of the state. It can also be called packet filters. They make their decisions based on IP and port. They lacked the sense of the state, and they're less secure
- Stateful firewalls, they have a state tables basically allowed the firewall to compare current packets with previous packets. which makes the firewall  slower, more secure than their stateless firewall. they're also called application firewalls, and they can make decisions based on filter information based on the type of website that somebody is listening
- antivirus generally Comparing hashes of files is how most detect malicious files on your system. to the malicious file md5 hash

### R1D11
day 11 done with a completion of course on coursera on topic Introduction to Cybersecurity Tools & Cyber Attacks by IBM

cryptographic attack

the five common forms of cryptographic attack, brute force, rainbow tables, social engineering, known plaintext, known ciphertext

brute force is an attack based on trial and error, and effectively would work through submission of many passwords or fast traces to hope that eventually it will guess correctly.

Rainbow tables are similar, but they use a limited amount of information or entity, or files, and they actually contain three hash passwords that we can check against hash customers, that makes the attacks a lot faster.

Social engineering consists using non-technical methods to get those, maybe get the password from the end users themselves.

The known plaintext attack is based on having only plain text, and doing analysis based on that plaint text to try to understand how the cipher works, and how the cipher encrypts the information. This is an attempt to actually understand and try to get the actual key that is used in the cipher to encrypt the information. Once you have the key, you are able to decrypt or encrypt any information

The known ciphertext attack is the process of having only ciphertext. It's similar to the plaintext attack, but with the difference that we don't own plaintext, we just own ciphertext, and based on that ciphertext, we try to defer the key used in the cipher to again, encrypt and decrypt information.

- Substitution cipher is a simple form of symmetric key cryptography where one letter is substituted for another, but it is not secure due to the uneven distribution of letters in the English language.
- The weakness of symmetric key cryptography is key distribution, where the challenge is to securely transmit the encryption key to the receiver.

### R1D12
I completed a amazing room on tryhackme on Intrusion Detection
https://tryhackme.com/room/idsevasion#

I learned about how alerts are produced when an Nmap scan is conducted and how to reduce alerts using user-agents and Nmap scripts. I also explored Wazuh and Suricata alerts, evasion and tuning techniques, which can help reduce alert count and improve the efficiency of the IDS/IPS system.

In particular, I learned about IDS evasion on Nikto, which can be used to reduce the number of alerts generated by this active scanner. Evasion techniques are essential in avoiding detection by IDS/IPS systems.

During my exploration, I came across the Grafana OSINT tool, which was a new concept for me. I found it interesting and plan to explore it further in the future.

Furthermore, I learned about privilege escalation with Docker on a non-root user.

Overall, today's exploration of IDS and IPS systems has taught me a lot about detecting and preventing intrusions into computer systems. The various techniques and tools I have learned will no doubt be useful in improving security measures for any computer system.

### R1D13
completed my day on Command Injection and Broken Authentication
i learned about the Command Injection and Broken Authentication from the tryhackme room OWASP Top 10

- Command line injection is a type of attack where an attacker injects malicious code into a command line interface (CLI) to execute unauthorized commands on a target system. To protect against this type of attack, it's crucial to validate all input data and sanitize user input to prevent the execution of unauthorized commands.
- Broken authentication is another vulnerability that occurs when an application fails to properly authenticate users, allowing attackers to gain unauthorized access to the system. To protect against this, it's important to implement secure authentication mechanisms such as multi-factor authentication and strong password policies.
By staying vigilant and implementing best practices, we can protect our systems and data against these and other types of attacks.

### R1D14
on day 14 I wasn't able to study anything specifically related to cybersecurity. Instead, I spent my time preparing for and completing an Android app group project.

Although I don't know Java, I was able to learn how to use and understand the various components and structure of an Android app. I focused on the functionality of the app and added some features, such as sending an API request to an endpoint API server.

The endpoint API server was self-hosted and run by a machine learning model to predict certain outcomes. It was interesting to learn about how the app components worked together to make this feature possible.

Even though this project wasn't directly related to cybersecurity, it still taught me valuable skills that can be applied in various areas,

### R1D15
I learned about a powerful web vulnerability scanner called "Nuclei". 
- Nuclei is an open-source project that helps to automate web application testing and identify vulnerabilities in web applications.

- it was possible to scan a website for a wide range of vulnerabilities such as cross-site scripting (XSS), SQL injection, and remote code execution. 
- it uses a simple YAML-based syntax to define the attack templates and the payload for the tests. which makes it easy to write custom attack scripts that can test for specific vulnerabilities.
- Nuclei has a ability to detect and report issues in real-time.
### R1D16
I have been learning about two  topics from the tryhackme room OWASP Top 10: XML External Entity (XXE) and Broken Access Control.
- XXE is a type of attack where an attacker can exploit a vulnerability in an XML parser to access sensitive data or execute arbitrary code. To prevent this, it's important to sanitize all input data and disable external entities in XML parsers.
- Broken Access Control is another vulnerability that occurs when an application fails to properly restrict access to sensitive data or functionality. This can lead to unauthorized access and information disclosure. To prevent this, access controls should be properly implemented and tested.
### R1D17
I learned about the history of malware from a TryHackMe room. Malware is a combination of "malicious" and "software," and it refers to software designed to cause harm to computers or networks.

Throughout the history of computing, numerous types of malware have been created with various goals in mind, including theft of personal data, destruction of files, and gaining unauthorized access to systems. Some of the earliest recorded instances of malware include the Creeper Program, which was created in the 1970s, and the Reaper, which was designed to delete the Creeper Program.

Other notable examples of early malware include the Wabbit, which was created in the 1980s and could quickly replicate itself, as well as ANIMAL, which was designed to attack IBM mainframe computers. The Elk Cloner, which was created in 1982, was the first virus to spread to personal computers.

In 1988, the Morris Internet Worm made headlines for its rapid spread across the internet and its ability to infect thousands of computers. This incident served as a wakeup call for the need for better security measures to protect against malware.

Finally, the Cascade virus, which was created in 1987, was one of the first viruses to encrypt its own code, making it more difficult for security experts to detect and remove.


**Note**: Due to some issue, my daily updates for some days may take some time to be updated, but I will make sure to update them first in the README file.
