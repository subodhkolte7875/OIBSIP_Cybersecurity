# Task 1: Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap in order to identify open ports and services on a target system.

## Tool Used
- Nmap (Network Mapper)

## Environment
- Operating System: Kali Linux (VirtualBox)
- Scan Target: scanme.nmap.org

## Command Used
nmap scanme.nmap.org

## Results
The Nmap scan identified the following open ports and services:
- 22/tcp – SSH
- 80/tcp – HTTP
- 9929/tcp – Nping Echo
- 31337/tcp – Elite

## Explanation
Open ports indicate services that are actively running on the target system. Identifying open ports helps security analysts understand the attack surface and detect potential vulnerabilities.

## Files Included
- nmap_scan_results.txt (Scan output)
- nmap_screenshot.png (Proof of execution)

## Conclusion
This task demonstrates how Nmap can be used for basic network reconnaissance to identify open ports and services, which is a fundamental step in cybersecurity assessments.
