# Task4
# Penetration Testing Simulation Report
**Task ID:** task4  
**Intern Name:** [Your Name]  
**Organization:** VirtualWorks Labs Internship  

## 1. Executive Summary
This report outlines a controlled penetration testing simulation executed in a sandboxed environment. The objective was to perform a structured scenario to safely scan, identify, and understand system weaknesses without causing harm.

## 2. Environment Setup
* **Attacker Machine:** Kali Linux OS
* **Target Machine:** Vulnerable Sandbox Target Environment

## 3. Step-by-Step Simulation Execution

### Step 1: Reconnaissance and Scanning
An active network scan was conducted to find open access points and determine what software configurations were running on the host system.
* **Tool Used:** Nmap (Network Mapper)
* **Command:** `nmap -sV [Target_IP]`
* **Result:** Successfully located open ports and identified running services.

### Step 2: Vulnerability Assessment
By cross-referencing the discovered software versions against public vulnerability databases, an actionable security weakness was identified in an outdated service wrapper.

### Step 3: Exploitation Simulation
A simulation framework was deployed to test the security gap. The process successfully initiated a secure command shell session, establishing a proof of concept.
* **Tool Used:** Metasploit Framework

---

## 4. Lab Evidence (Screenshots)

### Lab Step 1: Network Scan Results
Below is the terminal log showing the network scan identifying system entry pathways:
![Reconnaissance Scan](recon_scan.png)

### Lab Step 2: Service Vulnerability Verification
Below is the confirmation of the outdated service target containing the security gap:
![Vulnerability Identification](vulnerability_found.png)

### Lab Step 3: Successful Exploitation Simulation
Below is the final output terminal log showing command access established in the lab:
![Exploit Success](exploit_success.png)
