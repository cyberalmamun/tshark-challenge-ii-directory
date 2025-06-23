# TShark Challenge II: Directory — TryHackMe Walkthrough

## Overview

This room simulates a real-world SOC analyst task where we analyze network traffic captured in a PCAP file using **TShark**. The goal is to investigate DNS queries, identify suspicious domains, analyze HTTP traffic, extract files, and understand malware indicators.
TShark Challenge II: Directory
> Room link: https://tryhackme.com/room/tsharkchallengestwo

---

## Tools Used

- TShark (CLI version of Wireshark)  
- CyberChef (for defanging and data manipulation)  
- VirusTotal (for domain and file reputation)  
- sha256sum (for hashing files)  
- Linux command line utilities: awk, grep, sort, uniq, wc

---

## Step-by-Step Walkthrough
![Screenshot 2025-06-23 at 11 22 35 PM](https://github.com/user-attachments/assets/56dd4b00-d391-4a44-aac2-15704a1be5c5)
![Screenshot 2025-06-23 at 11 51 01 PM](https://github.com/user-attachments/assets/3fa35863-8f28-4189-838c-ed23685f5dd2)
![Screenshot 2025-06-23 at 11 46 59 PM](https://github.com/user-attachments/assets/fbc337a8-049a-48b0-90bc-f503dda9155c)
![Screenshot 2025-06-23 at 11 40 51 PM](https://github.com/user-attachments/assets/0c44d60b-242a-4e33-b8b5-ad568defaf8c)
![Screenshot 2025-06-23 at 11 26 20 PM](https://github.com/user-attachments/assets/af25a7e0-99a3-41f4-9f8c-47dfba4796aa)
![Screenshot 2025-06-23 at 11 24 21 PM](https://github.com/user-attachments/assets/dd24a852-476d-4de9-a8ae-8e1ef543cb56)
