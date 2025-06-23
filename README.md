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
