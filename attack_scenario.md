# Example Attack Scenario

## Scenario Overview

One of the attack paths developed in Projet Solaris starts from the attacker machine and follows a realistic internal network compromise scenario.

## Attacker Position

- Initial access from Kali Linux attacker machine
- No privileged access at the beginning
- Only network visibility and reachable hosts

## Attack Steps

1. Perform network reconnaissance
2. Identify live hosts and open services
3. Capture NTLMv2 credentials using responder-like techniques
4. Crack the captured hash
5. Reuse valid credentials for remote access
6. Explore the compromised machine
7. Retrieve a flag or access sensitive resources

## Techniques and Tools

- Nmap
- Responder
- Hashcat
- RDP access
- Windows internal exploration

## Skills Demonstrated

- reconnaissance
- service enumeration
- credential capture
- password cracking
- remote access
- internal navigation

## Goal

The purpose of this scenario is to reproduce a realistic attack chain inside a controlled lab environment and document each step clearly.
