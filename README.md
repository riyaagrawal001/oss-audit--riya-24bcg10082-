# oss-audit--riya-24bcg10082-
# OSS Audit Project

## Student Details

Name:Riya Agrawal
Registration Number:24BCG10082

##  Chosen Software

I have chosen **Git**, which is a widely used open-source version control system. It helps developers track changes in their code and collaborate efficiently on projects.

## Project Overview

This project is a part of the **Open Source Software (OSS)** course.
The main aim of this project is to understand how open-source systems work and to gain practical knowledge by writing shell scripts in a Linux environment.

Through this project, I explored basic Linux commands, system-level operations, and the importance of open-source tools in real-world applications.

## Shell Scripts Description

###  Script 1 – System Identity Report

This script displays important details about the system such as:

* Kernel version
* Current user
* System uptime
* Operating system details
* Current date and time

It mainly uses variables and command substitution to fetch system information.

###  Script 2 – FOSS Package Inspector

This script checks whether **Git** is installed on the system or not.
If installed, it displays useful details like version and description.

Concepts used:

* `if-else` condition
* `case` statement
* Package management commands (`dpkg`)

###  Script 3 – Disk and Permission Auditor

This script analyzes important system directories such as `/etc`, `/home`, and `/var/log`.

It shows:

* Directory size
* Permissions
* Owner details

A `for` loop is used to go through multiple directories.

###  Script 4 – Log File Analyzer

This script reads a log file and counts how many times a specific keyword (by default **"error"**) appears.

It also shows the last few matching lines for better understanding.

Concepts used:

* `while` loop
* `if` condition
* Command-line arguments
  
###  Script 5 – Open Source Manifesto Generator

This is an interactive script where the user gives input.
Based on the input, it generates a simple open-source philosophy statement and saves it in a text file.

##  How to Run the Scripts

### Step 1: Open Terminal

### Step 2: Go to project folder

```bash
cd oss-audit-24BCG10082
```

### Step 3: Give permission to scripts

```bash
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```

### Step 4: Run the scripts

```bash
./script1.sh
./script2.sh
./script3.sh
./script4.sh /var/log/syslog
./script5.sh
```
##  Requirements

* Linux Operating System (Ubuntu preferred)
* Bash shell
* Basic knowledge of terminal commands

##  Repository Contents

* `README.md` → Project description
* `script1.sh` → System report
* `script2.sh` → Package checker
* `script3.sh` → Disk analysis
* `script4.sh` → Log analyzer
* `script5.sh` → Manifest generator
* `report.pdf` → Final project report

##  Conclusion

Working on this project helped me understand:

* The concept of open-source software
* How Linux systems work
* Basics of shell scripting
* Practical use of commands and automation

Overall, this project improved my understanding of system-level programming and open-source tools.

##  Note

I have written all the scripts myself. I tested them on Linux. The work I am submitting is what I have learned and understand about the scripts. I did all the work, in a Linux environment. The scripts and the work are based on my learning and understanding.
