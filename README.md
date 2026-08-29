# Cybersecurity Framework for Small Businesses

## Project Overview

This project focuses on implementing a practical cybersecurity framework for small businesses using structured security controls and open-source tools.

The project uses a virtual lab environment to demonstrate network security, firewall configuration, attack simulation, attack prevention, and intrusion detection.

## Objectives

- Analyze common security threats
- Select a suitable cybersecurity framework
- Configure a secure virtual network
- Implement firewall rules
- Simulate network-based attacks
- Detect and prevent suspicious activity
- Configure IDS/IPS monitoring

## Framework

The **CIS Controls** framework was selected for this project because it provides essential security practices suitable for small business environments.

The implementation focuses on areas such as:

- Access control
- Network monitoring
- Vulnerability management
- Traffic filtering
- Threat detection

## Lab Environment

The virtual lab consisted of:

- **pfSense** – Firewall
- **Kali Linux** – Attack simulation
- **Ubuntu** – Target system
- **Suricata** – Intrusion Detection and Prevention

Connectivity between the systems was verified before testing.

## Firewall Configuration

pfSense firewall rules were configured to control network traffic and restrict unauthorized connections.

The configuration was tested by applying traffic filtering rules and verifying whether specific network services could be accessed.

## Attack Simulation

Network-based attack scenarios were simulated from Kali Linux against the target environment.

The testing included network scanning and connection attempts to evaluate whether the configured security controls could restrict unwanted traffic.

## Attack Prevention

Firewall rules were applied to block malicious or unauthorized traffic.

The configuration was then tested again to verify that previously accessible or suspicious connections were blocked or filtered.

## IDS/IPS with Suricata

Suricata was integrated with pfSense to provide real-time network monitoring.

It was configured to:

- Monitor network traffic
- Detect suspicious activity
- Generate security alerts
- Identify scanning and intrusion attempts
- Block malicious traffic

## Tools Used

| Tool | Purpose |
|------|---------|
| pfSense | Firewall and network security |
| Kali Linux | Attack simulation |
| Ubuntu | Target system |
| Suricata | Intrusion detection and prevention |

## Results

The project demonstrated how small business networks can use structured security controls, firewall filtering, and IDS/IPS monitoring to improve network protection.

Testing showed that firewall rules could block or filter unwanted traffic, while Suricata provided monitoring and alerting for suspicious activity.


