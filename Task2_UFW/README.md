# Task 2: Basic Firewall Configuration with UFW

## Objective
The objective of this task is to configure a basic firewall on a Linux system using UFW to allow secure access and block unnecessary services.

## Tool Used
- UFW (Uncomplicated Firewall)

## Environment
- Operating System: Kali Linux (VirtualBox)

## Configuration Steps
The following firewall rules were applied:
- Allowed SSH traffic to enable secure remote access.
- Denied HTTP traffic to restrict unnecessary web access.

## Commands Used
sudo ufw allow ssh
sudo ufw deny http
sudo ufw enable
sudo ufw status

## Results
The firewall was successfully enabled and the configured rules were verified using the UFW status command.

## Files Included
- ufw_status.png (Screenshot of firewall status)

## Conclusion
This task demonstrates the basic use of UFW to configure firewall rules, which is an essential step in securing Linux systems.
