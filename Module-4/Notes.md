# Module 4: Protecting the Organization

## 4.1 Cybersecurity Devices and Technologies

Organizations use different security devices and technologies to protect networks, systems, and data from cyber threats.

---

# Security Appliances

Security appliances are dedicated hardware or software devices designed to protect computer networks.

Examples:

- Firewall
- Intrusion Detection System (IDS)
- Intrusion Prevention System (IPS)
- Antivirus systems

Purpose:

- Monitor network traffic
- Detect threats
- Prevent unauthorized access
- Protect sensitive data

---

# Firewalls

A firewall is a security device that controls incoming and outgoing network traffic based on predefined security rules.

It acts as a barrier between:

- Trusted internal networks
- Untrusted external networks (Internet)

---

## Functions of a Firewall

- Blocks unauthorized access
- Allows legitimate communication
- Filters network traffic
- Prevents certain attacks

---

## Types of Firewalls

### Packet Filtering Firewall

- Examines individual data packets
- Allows or blocks packets based on rules

### Stateful Firewall

- Tracks active connections
- Makes decisions based on connection state

### Application Firewall

- Filters traffic at the application level
- Protects specific applications

---

# Port Scanning

Port scanning is the process of checking open ports on a device or network.

A port is a communication endpoint used by applications and services.

Attackers use port scanning to:

- Discover running services
- Find vulnerabilities
- Identify possible entry points

Security professionals use it for:

- Network auditing
- Vulnerability assessment

---

# Intrusion Detection and Prevention Systems (IDPS)

IDPS monitors network activity to detect and respond to suspicious behavior.

There are two main types:

## Intrusion Detection System (IDS)

- Detects suspicious activity
- Sends alerts
- Does not automatically block attacks

## Intrusion Prevention System (IPS)

- Detects threats
- Automatically takes action
- Blocks malicious activity

---

# IDS vs IPS

| IDS | IPS |
|---|---|
| Detects attacks | Detects and prevents attacks |
| Generates alerts | Takes automatic action |
| Passive security | Active security |

---

# Real-Time Detection

Real-time detection means identifying security threats immediately as they occur.

It uses:

- Monitoring tools
- Security analytics
- Threat intelligence

Benefits:

- Faster response
- Reduced damage
- Improved security visibility

---

# Protecting Against Malware

Organizations protect systems from malware using:

## Antivirus Software

Detects and removes malicious programs.

## Endpoint Protection

Protects devices connected to a network.

## Regular Updates

Fix security vulnerabilities.

## User Awareness

Helps prevent social engineering attacks.

---

# Security Best Practices

Important security practices:

- Use strong passwords
- Enable multi-factor authentication
- Keep software updated
- Perform regular backups
- Restrict user access
- Monitor network activity
- Train employees about security

---

# 4.2 Behavior Approach to Cybersecurity

Traditional security focuses on known threats.

Behavior-based security focuses on identifying unusual activities.

It detects threats by analyzing:

- User behavior
- Network activity
- System actions

---

# Behavior-Based Security

Behavior-based security identifies abnormal patterns instead of only searching for known malware signatures.

Example:

A user normally logs in from India.

Suddenly:
- Login occurs from another country
- Large data transfer starts

The system may identify this as suspicious behavior.

---

# Advantages

- Detects unknown threats
- Helps identify advanced attacks
- Improves threat detection

---

# NetFlow

NetFlow is a network monitoring technology that collects information about network traffic.

It records:

- Source IP address
- Destination IP address
- Data volume
- Communication time
- Protocol information

---

# Uses of NetFlow

- Network monitoring
- Detecting unusual traffic
- Investigating attacks
- Understanding network performance

---

# Penetration Testing

Penetration testing (Pen Testing) is an authorized simulated attack used to find security weaknesses.

Security professionals act like attackers to identify vulnerabilities.

---

## Steps of Penetration Testing

### 1. Planning
Define scope and goals.

### 2. Scanning
Identify possible weaknesses.

### 3. Exploitation
Attempt to exploit vulnerabilities.

### 4. Reporting
Document findings and recommendations.

---

# Benefits of Penetration Testing

- Finds vulnerabilities before attackers do
- Improves security
- Tests defense mechanisms

---

# Impact Reduction

Impact reduction means minimizing damage caused by security incidents.

Methods:

- Backups
- Disaster recovery plans
- Incident response plans
- Access control

Goal:

Reduce:
- Downtime
- Data loss
- Financial damage

---

# Risk Management

Risk management is the process of identifying, analyzing, and reducing security risks.

---

## Risk Management Process

### 1. Identify Risk

Find possible threats and vulnerabilities.

### 2. Analyze Risk

Determine likelihood and impact.

### 3. Reduce Risk

Apply security controls.

### 4. Monitor Risk

Continuously review security.

---

# 4.3 Cisco's Approach to Cybersecurity

Cisco follows a structured approach to detect, respond, and prevent cyber threats.

---

# Cisco CSIRT

CSIRT stands for:

**Computer Security Incident Response Team**

A CSIRT is a team responsible for handling cybersecurity incidents.

---

## Responsibilities of CSIRT

- Detect security incidents
- Investigate attacks
- Respond to threats
- Recover systems
- Improve future security

---

# Security Playbook

A security playbook is a documented set of procedures for responding to security incidents.

It defines:

- What actions to take
- Who is responsible
- How to handle different threats

---

# Benefits of Security Playbooks

- Faster response
- Consistent actions
- Reduced confusion during incidents

---

# Tools for Incident Detection and Prevention

Organizations use security tools such as:

## SIEM (Security Information and Event Management)

Collects and analyzes security logs.

Purpose:

- Detect suspicious activity
- Investigate incidents

---

## IDS/IPS

Monitors network traffic and blocks threats.

---

## Endpoint Security Tools

Protect individual devices from attacks.

---

# Cisco ISE and TrustSec

## Cisco ISE (Identity Services Engine)

Cisco ISE controls who can access network resources.

Functions:

- User authentication
- Device identification
- Access control

---

# Cisco TrustSec

TrustSec provides secure access control based on user identity instead of only location.

Benefits:

- Better network protection
- Reduced unauthorized access
- Improved security management

---

# Module 4 Quick Revision

- Security appliances protect networks and systems.
- Firewalls control network traffic based on security rules.
- Port scanning identifies open communication points.
- IDS detects threats; IPS detects and prevents threats.
- Real-time detection helps respond quickly to attacks.
- Behavior-based security identifies unusual activities.
- NetFlow analyzes network traffic patterns.
- Penetration testing finds vulnerabilities through simulated attacks.
- Risk management reduces security impact.
- CSIRT handles cybersecurity incidents.
- Security playbooks provide response procedures.
- Cisco ISE manages identity-based access control.
- TrustSec improves secure network access.
