🚀 UFW Firewall Configuration Project

📋 Project Overview

This project involved setting up and configuring a firewall on an Ubuntu server using UFW (Uncomplicated Firewall) inside a virtual machine on UTM for Mac. The goal was to secure the server by implementing strict firewall rules to control network traffic and prevent unauthorized access.

 🔐 What Is a Firewall & Why It Matters

A firewall acts as a security barrier between your computer and the network, filtering traffic based on defined rules. Proper firewall configuration is essential in cybersecurity to protect systems from attacks and unauthorized connections.

🧠 What I Did

- Installed and enabled UFW on Ubuntu.
- Configured default policies to deny all incoming traffic and allow all outgoing traffic.
- Allowed only essential ports: SSH (22), HTTP (80), and HTTPS (443).
- Enabled SSH connection rate limiting to prevent brute-force attacks.
- Enabled logging to monitor firewall activity.
- Verified the firewall’s status and rule effectiveness.

🧩 Issues I Encountered & How I Solved Them

- Initially, the installer ISO kept booting, resolved by removing the ISO from the VM settings.
- Learned to safely configure UFW without locking out remote access by allowing SSH before enabling the firewall.
- Researched and implemented SSH rate limiting to enhance security.

🧪 Testing & Validation

Tested connectivity by ensuring SSH remained accessible while other ports were blocked. Confirmed firewall rules using `sudo ufw status verbose`.

💡 What I Learned

- Practical firewall setup using UFW on Ubuntu.
- Importance of a default deny policy and least privilege principle.
- SSH rate limiting as a security best practice.
- Enabling firewall logging for security monitoring.

✨ Why This Project Matters

Firewalls are a fundamental defense mechanism in cybersecurity. This project helped me gain hands-on experience in securing a Linux server, configuring network rules, and understanding firewall best practices  all essential skills for cybersecurity roles.

