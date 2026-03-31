# Open Source Audit Project

##  Student Details

* **Name:** [Your Name]
* **Roll Number:** [Your Roll Number]
* **Course:** Open Source Software (OSS NGMC)

---

##  Project Overview

This project is a structured audit of an open-source software system. It explores the philosophy, licensing, ecosystem, and real-world impact of open-source development, along with practical Linux shell scripting tasks.

---

##  Chosen Software

**[Write your chosen software here — e.g., Git / Linux Kernel / Apache / MySQL / Python]**

---

##  Repository Structure

```
oss-audit-[rollnumber]/
│
├── README.md
├── report/
├── scripts/
│   ├── script1.sh
│   ├── script2.sh
│   ├── script3.sh
│   ├── script4.sh
│   └── script5.sh
└── screenshots/
```

---

##  Shell Scripts Description

###  Script 1 — System Identity Report

Displays system information such as:

* Kernel version
* Logged-in user
* System uptime
* OS distribution details

---

###  Script 2 — FOSS Package Inspector

* Checks if the selected package is installed
* Displays version, license, and summary
* Uses a `case` statement to describe the software

---

###  Script 3 — Disk and Permission Auditor

* Audits key system directories
* Shows:

  * Disk usage
  * Permissions
  * Ownership

---

###  Script 4 — Log File Analyzer

* Reads a log file
* Counts occurrences of keywords like `ERROR`
* Displays summary and last matching entries

---

###  Script 5 — Open Source Manifesto Generator

* Takes user input
* Generates a personalized open-source philosophy statement
* Saves output to a `.txt` file

---

##  How to Run the Scripts

### Step 1: Clone the Repository

```
git clone https://github.com/[your-username]/oss-audit-[rollnumber].git
cd oss-audit-[rollnumber]/scripts
```

### Step 2: Give Execute Permission

```
chmod +x *.sh
```

### Step 3: Run Scripts

#### Script 1

```
./script1.sh
```

#### Script 2

```
./script2.sh
```

#### Script 3

```
./script3.sh
```

#### Script 4

```
./script4.sh /var/log/syslog error
```

#### Script 5

```
./script5.sh
```

---

##  Dependencies

* Linux OS (Ubuntu / Fedora / etc.)
* Bash shell
* Basic utilities: `grep`, `awk`, `du`, `df`

---

##  Project Report

The full report is included in:

```
/report/OSS_Audit_Report.pdf
```

---

##  Notes

* All scripts are tested on a Linux system.
* Each script includes comments explaining functionality.
* Screenshots of execution are provided in `/screenshots`.

---

## Conclusion

This project demonstrates both conceptual understanding of open-source philosophy and practical Linux skills through scripting and system interaction.

---

##  Submission Checklist

*  GitHub repository (public)
*  README.md included
*  5 shell scripts
*  Project report PDF
