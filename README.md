Phishing Simulation Homelab
Overview

This project demonstrates a phishing attack simulation conducted in a controlled homelab environment. The objective of the lab is to understand how phishing pages are created, deployed, and used to capture credentials in order to improve cybersecurity awareness and defensive strategies.

The simulation was carried out using Zphisher to generate the phishing template. To allow testing outside the local network, Cloudflare Tunnel was used to securely expose the locally hosted phishing page to the internet.

Tools Used

Zphisher

Cloudflare Tunnel

Kali Linux

Virtual Machines (Homelab Environment)

Lab Setup

The phishing simulation was performed within a virtual homelab environment consisting of:

Attacker Machine: Kali Linux VM

Target Machine: Windows VM

Internal virtual network connecting both systems

Phishing Page Configuration

A login-based phishing template was selected to simulate a common real-world phishing scenario.

The phishing page was hosted locally using Zphisher. To make the page accessible outside the lab network, Cloudflare Tunnel was used to create a secure tunnel that generated a publicly accessible URL.

This allowed controlled testing from external devices without requiring port forwarding or exposing the local network.

Legal Disclaimer

⚠️ This project is for educational and cybersecurity research purposes only.

All testing was conducted within a controlled homelab environment, and no real users, organizations, or systems were targeted.

The techniques demonstrated using Zphisher and Cloudflare Tunnel are intended solely for learning and defensive security research. Any misuse of the information in this repository is the sole responsibility of the individual using it.

Author

Gideon Daniel
Cybersecurity Enthusiast | IT Support | Homelab Projectsal access enabled through Cloudflare Tunnel for controlled testing and educational purposes.
