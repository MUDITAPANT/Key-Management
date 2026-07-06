# Key Management Scheme for Secure Communication
Acadmic Project 2023
## Overview
This project implements an **Authentication and Key Agreement (AKA) protocol** for secure communication between smart devices and cloud servers. It ensures confidentiality, integrity, and authenticity in IoT-based environments such as smart cities, where sensitive data is continuously exchanged.

The protocol is written in **SPDL (Security Protocol Description Language)** and verified using the **Scyther tool**.

---

## Features
- Secure communication between smart devices and cloud servers  
- Mutual authentication using AKA protocol  
- Session key establishment for future communication  
- Formal verification using Scyther  
- Protection against replay, impersonation, and man-in-the-middle attacks  

---

## System Model
- **Smart Devices (DV):** End-user IoT devices  
- **Cloud Server (CS):** Centralized data storage and processing  
- **Trusted Authority (TA):** Registers devices and servers, generates pseudo-identities and temporal credentials  
- **Session Key:** Established after mutual authentication for secure communication  

---

## Methodology
The proposed scheme consists of two main phases:

### 1. Registration Phase
- TA registers smart devices and cloud servers  
- Generates pseudo-identities and temporal credentials  
- Stores credentials in device/server memory before deployment  

### 2. Authentication & Key Establishment Phase
- Smart device initiates authentication with nonce and timestamp  
- Cloud server verifies timeliness and authenticity  
- Both parties generate and validate session keys  
- Secure communication channel established  

---

## Tools Required
- [Scyther](https://people.cispa.io/cas.cremers/scyther/) – Automated security protocol verification  
- [GraphViz](http://www.graphviz.org/Download.php) – Visualization support  
- [Python](http://www.python.org/download/) – Runtime environment  
- [wxPython](http://www.wxpython.org/download.php) – GUI support for Scyther  

---

## Results
- The proposed AKA protocol was successfully verified using Scyther  
- The scheme is secure against multiple attack vectors  
- Demonstrated efficiency in establishing secure communication between sender and receiver entities  

---

## Conclusion
This project presents a robust key management scheme for secure communication in IoT environments. The verified protocol ensures confidentiality, integrity, and authenticity of data exchange between smart devices and cloud servers.

---

## Future Work
- Integration of blockchain for enhanced trust and privacy  
- Comparative analysis with other existing schemes  
- Simulation studies to measure performance impact  
- Enhancements in security, privacy handling, and accuracy  


## Author
- **Mudita** – B.Tech in Computer Science (2025) 
