# Windows Forensics Projects

This repository contains a collection of hands-on projects focused on Windows forensics.

The goal of this repository is to demonstrate practical SOC Analyst (L1) forensic analysis skills on Windows systems, with a focus on incident investigation, evidence collection, and threat detection using real-world artifacts.

---

## 📁 Projects Included

### 1. Investigating Windows Event Logs for Security Incidents
Windows Event Logs are a crucial source of information for identifying and investigating security incidents.

**Key Focus Areas:**
- Accessing Windows Event Logs using Event Viewer
- Filtering and Exporting Event Logs
- Parsing Event Logs using Log Parser
- Analyzing Event Logs using PowerShell
- Correlating Events for Comprehensive Analysis

---

### 2. Analyzing Windows Registry for Evidence of Malicious Activity
The Windows Registry is a critical hierarchical database that stores low-level settings for the operating system and installed applications.

**Key Focus Areas:**
- Extracting Windows Registry Hives from a Memory Image
- Analyzing the SAM Hive for User Information
- Investigating Autorun Entries in the Software Hive
- Examining User Assist Keys in the NTUSER.DAT Hive
- Correlating Registry Artifacts for Comprehensive Analysis

---

### 3. Forensic Analysis of Windows File Systems and Artifacts
Windows file systems and artifacts contain valuable information that can be crucial during forensic investigations.

**Key Focus Areas:**
- Creating a Forensic Image using FTK Imager
- Analyzing File System with Autopsy
- Extracting and Analyzing MFT (Master File Table)
- Analyzing Windows Prefetch Files
- Investigating Recent Activity using Shellbags
 
---

### 4. Extracting and Interpreting Browser Artifacts on Windows
Web browsers store a wealth of information about user activities, including history, cookies, cache, and download records.

**Key Focus Areas:**
- Extracting Browser History
- Recovering Stored Passwords
- Analyzing Browser Cookies
- Examining Browser Cache
- Interpreting Download Records

---

### 5. Recovering and Analyzing Deleted Files on Windows Systems
Deleted files can still contain valuable information for forensic investigations. Recovering and analyzing these files can provide critical evidence of user activities or malicious actions.

**Key Focus Areas:**
- Recovering Deleted Files using Recuva
- Creating a Forensic Image of the Disk using FTK Imager
- Analyzing Deleted Files using Autopsy
- Examining Metadata of Recovered Files
- Correlating Recovered Files with System Events

---

## 🎯 Objective
The objective of this repository is to:
- To understand Windows forensic artifacts and their role in security investigations
- To investigate security incidents using Windows logs and system artifacts
- To identify malicious activities, persistence mechanisms, and user behavior
- To gain practical experience in incident analysis and evidence collection
- To build SOC Analyst L1–level investigation skills through hands-on exercises

---

## 🧰 Tools Used

### 🔹 Built-in Windows Tools
- **Event Viewer** – Analyze security, system, and application logs  
- **PowerShell** – Automate log analysis and artifact extraction   

### 🔹 Forensic & Analysis Tools
- **Log Parser** – Parse and analyze Windows Event Logs
- **Volatility** – An advanced memory forensics framework 
- **FTK Imager** – Acquire and analyze disk images and files
- **Autopsy** – Perform file system and deleted file analysis
- **Windows File Analyzer** – A tool to analyze various Windows artifacts
- **Recuva** – A tool for recovering deleted files   

### 🔹 Browser Forensics Tools
- **WebBrowserPassView** – A tool to recover passwords stored in we browsers.
- **BrowserHistoryViewer** – Analyze browsing history and downloads  
- **SQLite Browser** – Examine browser database files  

---
