# Lab: Active Network Mapping & Host Discovery with Nmap

## 1. Objective
Performed active network mapping to discover live assets on a target subnet across different network layers using specialized Nmap flags.

## 2. Key Commands Practiced
```bash
# ARP Scan (Data Link Layer Discovery)
nmap -PR -sn <target_ip>

# ICMP Echo Scan (Network Layer Discovery)
nmap -PE -sn <target_ip>

# TCP SYN Ping Scan (Transport Layer Discovery)
nmap -PS -sn <target_ip>
```

## 3. Practical Verification Proof
Below is the verification showing successful host discovery and packet responses on the live target environment:

![Nmap Verification Proof](nmap-proof.png)
