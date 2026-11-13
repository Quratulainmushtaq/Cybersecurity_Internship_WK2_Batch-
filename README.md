# Cybersecurity_Internship_WK2_Batch-
Cyber Security Internship _NetworkWalks_Batch B084
# Cybersecurity Internship - Week 2 | Networkwalks (Batch B084)

This repository contains my practical lab work, command outputs, and penetration testing report for **Week 2** of the Cybersecurity Internship with **Networkwalks** (Batch B084).

---

## 📋 Week 2 Modules Summary

During Week 2, I completed all footprinting, reconnaissance, and network scanning modules (W2-PM1 to W2-PM5) along with the final penetration testing report on authorized targets (`networkwalks.com` and local subnet).

---

### 1. W2-PM1: Footprinting & Reconnaissance with Multiple Kali Tools
Performed passive and active information gathering on `networkwalks.com` using six different Kali Linux command-line tools (`whois`, `nslookup`, `whatweb`, `curl`, `wafw00f`, and `dnsrecon`) to gather domain registration details, DNS records, web technologies, and firewall information.

* **Key Findings & Execution:**
  * Checked domain ownership and registrar details using `whois`.
  * <img width="1364" height="667" alt="ss1" src="https://github.com/user-attachments/assets/4e200268-85f2-4aad-bb18-7fa2619ef8f1" />
  * Queried DNS records and name servers using `nslookup` and `dnsrecon`<img width="1364" height="668" alt="ss6" src="https://github.com/user-attachments/assets/4a0e7d79-f7a0-4059-b1a5-fd62532b0d54" />
  <img width="1362" height="644" alt="ss 9(a)" src="https://github.com/user-attachments/assets/0e9b4721-5409-4d81-8d8c-ff5b7cf09cd9" />
  
  * Identified web server technologies and WAF protection via `whatweb`, `curl`, and `wafw00f`.
<img width="1361" height="669" alt="ss7" src="https://github.com/user-attachments/assets/67a9413e-636a-47ae-9316-6ef925c724fa" />
<img width="1365" height="668" alt="ss8" src="https://github.com/user-attachments/assets/8a835838-3d5f-42cd-94e3-f19a7f7d4eb3" />
<img width="1365" height="669" alt="ss5" src="https://github.com/user-attachments/assets/117e6ab2-7726-4b36-9d37-3fc9578f3c13" />
---

### 2. W2-PM2: GHDB Based Footprinting Attacks
Utilized **Google Hacking Database (GHDB)** dorks (`site:`, `inurl:`, `intitle:`, `filetype:`) to uncover publicly exposed pages, indexed files, and sensitive information related to the target domain without directly interacting with the target server.
<img width="1363" height="726" alt="pm2 ss1" src="https://github.com/user-attachments/assets/e556a7e5-b8df-445e-82f9-8ffd9b7f8b9c" />

* **Key Findings & Execution:**
  * Tested multiple search operators to map indexed subdomains and public documents.

W2-PM2 GHDB Search 1 <img width="1358" height="763" alt="pm2 ss2" src="https://github.com/user-attachments/assets/50479eb8-80e0-45e9-9a95-6d798a0cd5c3" />

W2-PM2 GHDB Search 2 <img width="1365" height="767" alt="pm2 ss3" src="https://github.com/user-attachments/assets/d5e10b01-de6f-4d47-b3aa-6b1c35197c68" />


<img width="1359" height="767" alt="pm2 ss4" src="https://github.com/user-attachments/assets/a1764601-75c1-4ba8-a7c2-5b1bbb8daf8a" />

---

### 3. W2-PM3: Maltego Based Footprinting Attacks
Used **Maltego** to perform visual OSINT and infrastructure reconnaissance on `networkwalks.com`.

* **Key Findings & Execution:**
  * Added the target domain entity and ran transforms including **Footprint L1** to map DNS names, mail servers, and network infrastructure visually.
<img width="1357" height="720" alt="pm3 ss1" src="https://github.com/user-attachments/assets/4f995c0d-591b-4217-8a6c-d4f52786cbf7" />
<img width="1365" height="718" alt="pm3 ss3" src="https://github.com/user-attachments/assets/22a1ca5f-ca6e-4b5a-971c-bf25602a18ea" />

---

### 4. W2-PM4: theHarvester Based Footprinting Attacks! 
<img width="1365" height="663" alt="pm4 ss1" src="https://github.com/user-attachments/assets/25eed405-87a6-44ec-b067-f36fbf1100b6" />
Executed **theHarvester** in Kali Linux to gather open-source intelligence such as email addresses, subdomains, hostnames, and IP details from public search engines and data sources.

* **Key Findings & Execution:**
  * Ran targeted scans against `networkwalks.com` across multiple passive data sources.
<img width="1362" height="664" alt="pm4 ss2" src="https://github.com/user-attachments/assets/f779961e-06dc-48d2-ab7c-85cf748ed3da" />
---
### 5. W2-PM5: Zenmap Based Network Scanning
Performed local network discovery and port scanning using **Zenmap / Nmap** within my authorized local subnet.

* **Key Findings & Execution:**
  * Checked local IP configuration and subnet mask via Command Prompt
 (`ipconfig /all`).
<img width="1308" height="612" alt="ss cmd" src="https://github.com/user-attachments/assets/03bb70ee-c463-4404-9ca6-502e4fa483e6" />

  * Executed host discovery (`Ping Scan`) and port scans across the local subnet to identify active hosts and open services.

W2-PM5 IP Configuration <img width="1359" height="767" alt="pm5 ss2" src="https://github.com/user-attachments/assets/a0994622-385d-4476-9ec8-2db2792c6f2d" />

W2-PM5 Zenmap Scan Result <img width="1299" height="531" alt="z ss" src="https://github.com/user-attachments/assets/e700f8c9-a2f4-4267-a187-bf50bd83f3da" />
---

### 6. W2-PM-FINAL: Penetration Testing Report
Compiled a structured penetration testing report documenting the scope, Letter of Authorization (LOA), methodology, tool outputs, and security observations across all completed modules.

---

## 🛠️ Tools & Environment
* **OS:** Windows 10 & Kali Linux (VirtualBox)
* **Reconnaissance Tools:** `whois`, `nslookup`, `whatweb`, `curl`, `wafw00f`, `dnsrecon`, GHDB, Maltego, theHarvester
* **Scanning Tools:** Zenmap / Nmap

---

## 👤 Intern Details
* **Name:** Qurat Ul ain mushtaq
* **Batch:** B084
* **Program:** Networkwalks Cybersecurity Internship
