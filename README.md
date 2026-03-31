Open Source Audit: Linux Kernel

Student Name: Likitha Vijayakumar  
Roll Number: 24BAS10103  
Course: Open Source Software (Linux Administration)  
Chosen Software: Linux Kernel

Project Overview
What is This Project?
This project is a comprehensive philosophical and technical audit of the
Linux Kernel, one of the most influential open-source projects in
history. The Linux Kernel is the core of the Linux operating system,
powering everything from smartphones and laptops to supercomputers and
cloud infrastructure.
Technical Environment
Component            Details
---
Platform         Windows Subsystem for Linux (WSL2)
Distribution     Ubuntu 22.04 LTS
Kernel Version   6.6.87.2-microsotf-standard-WSL2
Shell            Bash 5.1.16
Architecture     x86_64
Shell Scripts
---
Script                     Description             Key Linux Concepts
---
`system_report.sh`         Displays kernel         Variables, command substitution,
version, system info,   `uname`, `uptime`, `free`
uptime, memory, and  
GPLv2 license
`kernel_inspector.sh`      Checks kernel headers,  `if-then-else`, `lsmod`, `grep`,
loaded modules, and     exit status
provides philosophical  
notes
`kernel_audit.sh`          Audits kernel           For loops, arrays, `ls -ld`,
directories (/boot,     `du`, `awk`, `cut`
/proc, /sys,  
/lib/modules)
`kernel_log_analyzer.sh`   Analyzes kernel logs    While read loop, command-line
for errors/warnings,    arguments, counters
counts occurrences
`kernel_manifesto.sh`      Interactive script that `read` input, string
generates a             concatenation, file writing
personalized  
open-source manifesto
---
How to Run
Prerequisites
Linux system (Ubuntu on WSL2 recommended)
Bash shell
Sudo privileges for scripts 3 and 4
Basic understanding of Linux commands
Installation
``` bash
# Clone the repository
git clone https://github.com/Yashodhara2024/oss-audit-24BCE10696.git
cd oss-audit-24BCE10696

# Make scripts executable
chmod +x scripts/*.sh
```
Running Scripts
``` bash
# Script 1: System Identity Report
./scripts/system_report.sh

# Script 2: Kernel Package Inspector
./scripts/kernel_inspector.sh

# Script 3: Kernel Directory Auditor (requires sudo)
sudo ./scripts/kernel_audit.sh

# Script 4: Kernel Log Analyzer (requires sudo)
sudo ./scripts/kernel_log_analyzer.sh error
sudo ./scripts/kernel_log_analyzer.sh warning

# Script 5: Manifesto Generator (interactive)
./scripts/kernel_manifesto.sh
```
