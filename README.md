Week 4 Assignment by Mahesh Karki, 1063667

# CS 450 Mini Project: File Management Automation Engine  
**Instructor**: Dr. Murchtricia Jones  
**Semester**: Summer 2025  
**University**: Carolina University, Winston-Salem  

---

##  Project Description  
A **menu-driven shell script** that automates file management tasks in Unix, including:  
- Organizing files by type (e.g., `.txt`, `.log`).  
- Analyzing log files for errors/warnings.  
- Monitoring system disk usage.  

---

##  Features  
| Feature                | Command Used           | Description                          |  
|------------------------|------------------------|--------------------------------------|  
| File Organizer         | `find`, `mv`, `mkdir`  | Sorts files into `Text/`, `Logs/`, etc. |  
| Log Analyzer           | `grep`, `wc`, `tail`   | Counts errors/warnings and shows recent activity. |  
| Disk Usage Reporter    | `df`, `awk`, `column`  | Displays storage metrics in a clean table. |  

---

##  Installation & Usage  
### Dependencies  
- Bash (`v4.0+`)  
- Core Unix utilities: `find`, `grep`, `awk`, `df`  

### Steps to Run  
1. Clone the project:  
   ```bash  
    
   cd cs450-mini-project  





   #

   Then, run this command in your wsl i.e bash

./automation_engine.sh  

[Note: Now, You shoud be able to get output as expected]


# Week V

### **Cron Jobs**  
1. **Weekly File Organization**  
   - Runs every Sunday at 11:59 PM  
   - Command: `automation_engine.sh organize_files <DIR> <LOG>`  

2. **Daily Log Analysis**  
   - Runs at 2:30 AM daily  
   - Command: `automation_engine.sh analyze_logs <LOGFILE> <LOG>`  

To install cron jobs:  
```bash
crontab crontab.txt


## Job Control Demo
Run `./job_demo.sh` to see:
- Background process creation (`&`)
- Job listing (`jobs -l`)
- Process monitoring (`ps`, `kill`)
- Foreground/background switching

Logs are saved to `job_control.log`.

## Validation Screenshots
![Terminal Output](terminal.png)  
- Log analysis showing 2 errors/2 warnings  
- Files organized into `Text/`, `Logs/`, etc.  
- Job control log contents verified

![alt text](<Screenshot 2025-07-24 150858.png>)