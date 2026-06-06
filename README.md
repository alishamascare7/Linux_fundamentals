# Linux Fundamentals Learning Portfolio

## About Me
I am learning Linux fundamentals as part of my transition into Cybersecurity.

---

## Topics I Learned

### 1. Basic Commands
- ls → list files
- pwd → show current directory
- cd → change directory
- mkdir → create folder
- rm → delete file

### 2. File Permissions
- chmod 755 file.sh
- chown user file.txt
  
 ## what it means -
7 (owner) = read (4) + write (2) + execute (1) = rwx
5 (group) = read (4) + execute (1) = r-x
5 (others) = read (4) + execute (1) = r-x

### 3. File Operations
# Create files & folders
- touch file.txt → create empty file
- mkdir folder → create directory
  
# View files
- cat file.txt → show full file content
- head file.txt → first 10 lines
- tail file.txt → last 10 lines
  
# Edit files
- nano file.txt → simple editor
- echo file.txt → prints text to screen
  
# Copy, move, rename
- cp file1 file2 → copy file
- mv file1 folder/ → move file
- mv oldname newname → rename file

 # Delete
- rm file.txt → delete file
- rm -r folder → delete folder

# File info
ls → list files
ls -l → detailed list (permissions)

### 4. Process Management
- ps → show processes
- kill → stop process

---
##  What I Learned

### Linux Basics
- File system navigation (cd, ls, pwd)
- File operations (touch, nano, cat, echo)
- Permissions (chmod, chown)

### Log Analysis
- grep for filtering logs
- awk for extracting fields
- sort and uniq for analysis
- building pipelines with |

### Bash Scripting
- Writing and executing scripts
- Variables and command substitution
- If/else conditions
- Functions
- Automation of log analysis

### SOC Simulation Projects
- Brute-force detection script
- Smart alert system
- Multi-rule detection engine
- Incident generation system

##  Example Skills Demonstrated
- Log parsing & threat detection
- Automation of security tasks
- Basic incident response simulation
- SOC-style alert generation

---
## Linux Hands-On Practice Screenshots

### Removing Directory Command
![Remove directory](screenshots/linux_remove_dir.png)

### Script Execution
![Linux script](screenshots/linux_script.png)

### Authentication Log Analysis
![Auth log](screenshots/linux_auth_log.png)

### Linux Scripts Report
![Scripts](screenshots/linux_report.png)

---

## Goal
To build strong Linux skills for a future Security Analyst role.
