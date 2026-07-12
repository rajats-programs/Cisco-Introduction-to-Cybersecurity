# Module 2: Attacks, Concepts and Techniques

## 2.1 Analyzing a Cyber Attack

## What is a Cyber Attack?

A cyber attack is an intentional attempt by an attacker to gain unauthorized access, steal information, damage systems, or disrupt services.

Attackers usually exploit:
- Weak security controls
- Human mistakes
- Software vulnerabilities
- Poor configurations

---

# Malware

## What is Malware?

Malware (Malicious Software) is software designed to harm systems, steal data, disrupt operations, or gain unauthorized access.

Malware can:
- Damage files
- Steal information
- Monitor user activity
- Allow attackers remote access

---

# Types of Malware

## 1. Virus

A virus is a malicious program that attaches itself to a legitimate file or application and spreads when the infected file is executed.

Characteristics:
- Requires user action to spread
- Can modify or delete files
- Spreads through infected files

Prevention:
- Avoid unknown downloads
- Use antivirus software
- Scan external devices

---

## 2. Worm

A worm is malware that can automatically spread across networks without requiring user interaction.

Characteristics:
- Self-replicating
- Spreads quickly
- Uses network vulnerabilities

Example:
- A worm exploiting outdated software on connected computers

---

## 3. Trojan Horse

A Trojan is malware disguised as a legitimate application to trick users into installing it.

Characteristics:
- Does not replicate itself
- Depends on user deception
- Can create unauthorized access

Example:
- Fake software containing malicious code

---

## 4. Ransomware

Ransomware is malware that encrypts files or locks systems and demands payment from victims.

Effects:
- Loss of access to files
- Financial damage
- Business disruption

Protection:
- Maintain backups
- Avoid suspicious attachments
- Keep systems updated

---

## 5. Spyware

Spyware secretly monitors user activity and collects information.

It may steal:
- Passwords
- Browsing history
- Personal information

---

## 6. Adware

Adware displays unwanted advertisements and may track user behavior.

Effects:
- Pop-up advertisements
- Reduced performance
- Privacy concerns

---

# Symptoms of Malware Infection

Common signs include:

- Slow computer performance
- Frequent crashes
- Unexpected pop-ups
- Unknown applications appearing
- Battery draining quickly
- High network activity
- Browser redirects
- Disabled security tools
- Unusual account activity

---

# 2.2 Methods of Infiltration

Attackers use different techniques to enter systems and networks.

---

# Social Engineering

Social engineering is a technique where attackers manipulate people instead of directly attacking technology.

The attacker uses:
- Trust
- Fear
- Urgency
- Curiosity

to convince victims to reveal information or perform actions.

---

# Types of Social Engineering Attacks

## Phishing

Phishing is a fraudulent attempt to steal sensitive information through fake messages or websites.

Common targets:
- Passwords
- Banking details
- Login credentials

Example:
- Fake email pretending to be from a bank

---

## Spear Phishing

A targeted phishing attack aimed at a specific person or organization.

Characteristics:
- Personalized messages
- Requires research about the target

---

## Baiting

Baiting uses attractive offers or rewards to trick users.

Example:
- Free software containing malware

---

## Pretexting

Attackers create a fake situation or identity to gain information.

Example:
- Pretending to be a company employee

---

# Denial-of-Service (DoS)

A Denial-of-Service attack attempts to make a service unavailable by overwhelming it with excessive requests.

Effects:
- Website becomes slow
- Users cannot access services
- System resources are exhausted

---

# Distributed Denial-of-Service (DDoS)

A DDoS attack is a DoS attack performed using multiple compromised devices.

These devices form a network called a:

**Botnet**

Advantages for attackers:
- More powerful attack
- Difficult to block because traffic comes from many sources

---

# Botnet

A botnet is a group of infected devices controlled by an attacker.

Compromised devices are called:
- Bots
- Zombies

Uses:
- DDoS attacks
- Spam distribution
- Malware spreading
- Cryptocurrency mining

---

# On-Path Attack

An on-path attack occurs when an attacker secretly places themselves between two communicating devices.

Also called:
- Man-in-the-Middle (MITM) attack

Attackers can:
- Read communication
- Modify messages
- Steal information

Protection:
- Use encryption
- Use secure connections (HTTPS)

---

# SEO Poisoning

SEO poisoning manipulates search engine results to direct users to malicious websites.

Attackers:
- Create fake websites
- Improve their ranking
- Trick users into visiting them

Risk:
- Malware downloads
- Credential theft

---

# Wi-Fi Password Cracking

Attackers attempt to gain unauthorized access to wireless networks by discovering passwords.

Methods:
- Weak password exploitation
- Dictionary attacks
- Brute-force attacks

Protection:
- Strong Wi-Fi passwords
- WPA2/WPA3 security
- Regular password changes

---

# Password Attacks

Password attacks attempt to discover or steal user passwords.

Common methods:

## Brute Force Attack
Trying every possible password combination.

## Dictionary Attack
Using a list of commonly used passwords.

## Credential Stuffing
Using leaked passwords from previous breaches.

Protection:
- Strong passwords
- Multi-factor authentication
- Avoid password reuse

---

# Password Cracking Time

Password strength depends on:

- Length
- Complexity
- Uniqueness

A longer password takes significantly more time to crack.

Example:

Weak:

password123

Strong:

T9@kL#82mQ!


Best practice:
- Use long passphrases
- Use password managers

---

# Advanced Persistent Threats (APT)

An APT is a long-term targeted cyber attack where attackers secretly maintain access to a system.

Characteristics:

- Highly organized
- Targets valuable information
- Remains undetected for long periods

Common targets:
- Governments
- Large organizations
- Critical infrastructure

---

# 2.3 Security Vulnerabilities and Exploits

## Vulnerability

A vulnerability is a weakness in hardware, software, or processes that attackers can exploit.

Examples:
- Outdated software
- Weak passwords
- Incorrect configurations

---

# Exploit

An exploit is a method or tool used by attackers to take advantage of a vulnerability.

Relationship:
Vulnerability = Weakness
Exploit = Method used to attack that weakness


---

# Hardware Vulnerabilities

Hardware vulnerabilities are weaknesses in physical devices.

Examples:

- Faulty hardware design
- Insecure firmware
- Physical access risks

Protection:
- Secure device access
- Update firmware
- Follow security practices

---

# Software Vulnerabilities

Software vulnerabilities occur due to weaknesses in programs or applications.

Causes:
- Programming mistakes
- Poor security design
- Outdated software

Examples:
- Buffer overflow
- Security bugs

---

# Categorizing Software Vulnerabilities

Common categories:

## Configuration Vulnerabilities
Caused by incorrect settings.

## Coding Vulnerabilities
Caused by programming errors.

## Authentication Vulnerabilities
Weak login and identity verification.

## Update Vulnerabilities
Systems missing security patches.

---

# Software Updates

Software updates are important because they:

- Fix security vulnerabilities
- Improve performance
- Add new features

Security patches help protect systems from known attacks.

Best practices:
- Enable automatic updates
- Update applications regularly
- Remove unsupported software

---

# 2.4 The Cybersecurity Landscape

Cyber threats continue evolving with new technologies.

Modern cybersecurity challenges include:

- Cryptocurrency-related attacks
- Cryptojacking
- Advanced malware
- Data theft

---

# Cryptocurrency

Cryptocurrency is a digital currency secured using cryptography and recorded through blockchain technology.

Examples:
- Bitcoin
- Ethereum

Security concerns:
- Wallet theft
- Fraud
- Phishing attacks

---

# Cryptojacking

Cryptojacking is the unauthorized use of someone else's computer resources to mine cryptocurrency.

Attackers use:
- Malware
- Browser scripts
- Compromised systems

Effects:
- High CPU usage
- Slow performance
- Increased electricity consumption

Protection:
- Keep software updated
- Use security tools
- Avoid suspicious websites

---

# Module 2 Quick Revision

- Malware is malicious software designed to damage, steal, or disrupt.
- Viruses need user action; worms spread automatically.
- Trojans disguise themselves as legitimate software.
- Ransomware locks data and demands payment.
- Social engineering attacks target human psychology.
- DoS and DDoS attacks disrupt services.
- Botnets are networks of infected devices controlled by attackers.
- Vulnerabilities are weaknesses; exploits take advantage of them.
- Regular updates reduce security risks.
- APT attacks are targeted and long-term.
- Cryptojacking secretly uses systems for cryptocurrency mining.

