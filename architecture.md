# Solaris Lab Architecture

## General Design

Projet Solaris was designed as an isolated pentesting lab simulating a small enterprise environment.

The lab is based on Proxmox and uses an internal virtual network to allow communication between machines while keeping the environment separated from the Internet.

## Core Components

### Hypervisor
- Proxmox VE installed on a mini PC

### Internal Network
- Dedicated internal network for lab machines

### Main Systems
- Jupiter: Domain Controller (Windows Server 2019)
- Mars: Windows 11 client machine
- Venus: Windows Server web server
- Terre: Kali Linux attacker machine
- Saturne: Windows Server 2012 with SQL Server
- Mercure: Windows 7 client
- Neptune: Windows 10 client
- Uranus: Windows 10 client

## Active Directory

The environment includes an Active Directory domain used to centralize authentication, system administration and user/group management.

Domain name:
- solaris.local

## Security Approach

The lab was created to remain isolated and controllable, allowing the simulation of attack scenarios without exposing external systems.

## Purpose

This architecture makes it possible to practice:

- network enumeration
- service discovery
- credential attacks
- privilege escalation
- lateral movement
- exploitation of vulnerable services
