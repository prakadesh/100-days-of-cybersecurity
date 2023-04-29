# #100DaysOfCode Log - Round 1 - [PRAKADESH]

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


