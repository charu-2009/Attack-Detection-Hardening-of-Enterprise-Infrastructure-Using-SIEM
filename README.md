# Attack-Detection-Hardening-of-Enterprise-Infrastructure-Using-SIEM

📌 Overview

This project focuses on simulating real-world cyberattacks on enterprise infrastructure, detecting malicious activities using a SIEM solution (Wazuh), and applying effective security hardening techniques. It demonstrates the complete security lifecycle from attack execution to detection, mitigation, and validation.

🎯 Project Objectives
    
    Simulate common Red Team attacks on Linux servers
    
    Monitor and detect security events using SIEM
    
    Centralize and correlate logs from multiple systems
    
    Implement system hardening and security controls
    
    Evaluate system security before and after hardening

🏗 Architecture

    The project is implemented using multiple virtual machines:
    
    Internal Server (Victim) – Target for internal attacks
    
    Web Server (Attacker & Victim) – Used for web-based attacks and log generation
    
    SIEM Server – Centralized log collection, monitoring, and alerting
    
    All endpoints forward logs to the SIEM server for analysis.
