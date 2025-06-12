# Zscaler-sub-sim
I used Arch Linux to simulate substitutes of the propietary Zscaler

This mini-project demonstrates how DNS-level filtering can be enforced system-wide using `dnsmasq`, following real-world enterprise setup principles where 100,000+ devices are managed with Zscaler/Cisco/Cloudfare policies.

### What This Setup Does

- Routes all DNS traffic through `127.0.0.1` via `dnsmasq`
- Applies domain-level blocking for platforms like:
  - `tiktok.com`
  - `instagram.com`
- Affects all apps, both CLI and GUI
- Follows ZIA’s DNS filtering and policy control across endpoints

### Stack used
- Arch Linux CLI + XFCE GUI (thin)
- Firefox browser
- systemd

<img width="1470" alt="Screenshot 2025-06-12 at 01 02 28" src="https://github.com/user-attachments/assets/f4e0d0f8-0544-481c-b98e-8a40b7ffc7fd" />

<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/4b787bf5-d32d-4c5c-bde1-a0e296a89935" />

<img width="1470" alt="Screenshot 2025-06-11 at 21 24 32" src="https://github.com/user-attachments/assets/e149cf06-2ef6-46cd-bf6d-69f92a118645" />

<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/9c379772-2874-4c6a-bfa0-911ff6b73a97" />

<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/00ec0462-634d-41d4-a02f-696df9b8453c" />

### Similar Project(s)-Arch From Scratch

https://github.com/ProjectTSAP/ArchLinux-From-Scratch
