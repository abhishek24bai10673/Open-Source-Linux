# oss-audit-24BAI10500
Open Source Audit of Python - Shell scripts and written report for the OSS NGMC course at VIT. Topics: Licensing, Linux footprint, and FOSS ecosystem analysis.

# OSS Audit — Python
**Student Name:** Abhishek Mishra  
**Course:** Open Source Software  
**Unit Coverage:** 1 – 5  
**Software Audited:** Python  
**License:** PSF License (Python Software Foundation)

---

## About

This repository contains the shell scripts written as part of the 
Open Source Audit capstone project for the Open Source Software 
course at VIT. The project is a structured audit of Python as an 
open-source software project, covering its origin, philosophy, 
licensing, Linux footprint, and FOSS ecosystem.

All scripts were written and tested on Ubuntu 24.04 LTS using WSL2.

---

## Dependencies Required

Before running any script, make sure these are installed:
```bash
sudo apt update
sudo apt install python3
sudo apt install python3-pip
sudo apt install lsb-release
```

These are all free and open-source packages available via apt.

---

## Scripts

| File | Description |
|------|-------------|
| script1.sh | System Identity Report — displays system info, kernel version, username, uptime, and installed Python version |
| script2.sh | Package Check — checks if Python3 is installed and displays version and description |
| script3.sh | Disk and Permission Auditor — checks system directories for permissions and sizes |
| script4.sh | Log File Analysis — searches system logs for Python related entries and counts occurrences |
| script5.sh | Manifesto Generator — takes user input and generates a personalised open source manifesto |

---

## How to Run
```bash
chmod +x script1.sh    //System Identity Report
./script1.sh

chmod +x script2.sh    //Package Check
./script2.sh

chmod +x script3.sh    //Disk and Permission Auditor
./script3.sh

chmod +x script4.sh    //Log File Analysis
./script4.sh

chmod +x script5.sh    //Manifesto Generator
./script5.sh
```

---

## System

- OS: Ubuntu 24.04 LTS via WSL2  
- Shell: Bash  
- Python: Python 3.12.3
