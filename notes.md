# Footprinting & Reconnaissance

## Overview
This repository contains resources, tools, and scripts to conduct footprinting and reconnaissance. The goal is to gather publicly available information about a target before performing any penetration testing or ethical hacking activities.

## Table of Contents
- [Introduction](#introduction)
- [Notes & Methodologies](#notes--methodologies)
- [Tools](#tools)
- [Scripts](#scripts)
- [Useful Links](#useful-links)

## Introduction
Footprinting and reconnaissance are the first steps in ethical hacking. They involve gathering information about a target organization, individual, or system to understand its infrastructure, technology stack, and potential vulnerabilities.

## Notes & Methodologies
- **Passive Reconnaissance** (Using public sources like WHOIS, DNS records, etc.)
- **Active Reconnaissance** (Interacting with the target, such as port scanning and fingerprinting)
- **Open-Source Intelligence (OSINT)**
- **Social Engineering Techniques**
- **Network Mapping**

### Notes:
- [Footprinting Techniques](notes/footprinting-techniques.md)
- [Reconnaissance Checklist](notes/recon-checklist.md)
- [OSINT Resources](notes/osint-resources.md)

## Tools
Here are some commonly used tools for reconnaissance:

### Passive Recon Tools:
- [WHOIS Lookup](https://who.is)
- [Shodan](https://www.shodan.io)
- [theHarvester](https://github.com/laramies/theHarvester)

### Active Recon Tools:
- [Nmap](https://nmap.org/)
- [Metasploit](https://www.metasploit.com/)
- [Recon-ng](https://github.com/lanmaster53/recon-ng)

### OSINT Tools:
- [Maltego](https://www.maltego.com/)
- [SpiderFoot](https://github.com/smicallef/spiderfoot)
- [Amass](https://github.com/owasp-amass/amass)

## Scripts
Custom scripts to automate reconnaissance tasks:
- [DNS Enumeration Script](scripts/dns_enum.py)
- [Subdomain Finder](scripts/subdomain_finder.py)
- [IP Range Scanner](scripts/ip_range_scanner.py)

## Useful Links
- [OWASP Recon Methodologies](https://owasp.org/www-project-information-gathering/)
- [HackTricks - Footprinting](https://book.hacktricks.xyz/)
- [Bug Bounty Recon Resources](https://bugbountyforum.com/tools/)

## Contribution
Feel free to contribute by adding new tools, scripts, or improving documentation. Open a pull request or submit an issue!

## Disclaimer
This repository is for educational purposes only. Use responsibly and ensure you have authorization before performing reconnaissance on any system.
