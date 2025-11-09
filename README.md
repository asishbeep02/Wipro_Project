# Wipro_Project 
# 📘 Project Overview
. This project is part of the Capstone series that integrates Linux Operating System (LinuxOS) and Linux System Programming (LSP) concepts.

. Assignment 5 focuses on creating a suite of Bash scripts to automate essential system maintenance tasks such as system backups, updates, cleanup, and log monitoring.

. The scripts are designed to improve system reliability and reduce manual intervention by automating routine administrative jobs.

# 🎯 Objectives

. Automate system backup, update, and cleanup operations.

. Monitor and analyze system logs for errors or anomalies.

. Combine multiple scripts into a single, menu-driven maintenance suite.

. Implement error handling and logging mechanisms to ensure reliability.

# 🗂️ Day-wise Task Breakdown
# Day	                          Task
Day 1	             Write a Bash script for automated system backups.

Day 2	             Create a script for system updates and cleanup.

Day 3	             Develop a log monitoring script that detects and alerts on specific conditions.

Day 4	             Combine all scripts into a unified maintenance suite with a menu-driven interface.

Day 5	             Perform testing, add error handling, and logging functionalities for robustness.

# ⚙️ Features

. Automated Backups – Scheduled or manual file backups to designated directories.

. System Updates – Executes updates and removes unnecessary packages/files.

. Log Monitoring – Continuously checks system logs for warnings or errors.

. Menu Interface – Easy navigation to select and run scripts.

. Error Handling & Logging – Captures script errors and logs them for analysis.

# 🧰 Technologies Used

. Shell Scripting (Bash)

. Linux Command-Line Utilities (rsync, tar, apt, grep, awk, cron)

. System Logging (syslog, journalctl)

# 🚀 How to Run

. Clone or download the repository.

. Navigate to the project directory:

     cd Assignment5_SystemMaintenance

. Make the scripts executable:

        chmod +x *.sh

. Run the main maintenance suite:

    ./maintenance_suite.sh

# 🧩 Example Menu
========================================
  System Maintenance Suite
========================================
1. Perform System Backup
2. Update and Clean System
3. Monitor Logs
4. Exit
Enter your choice:

# 🧪 Testing & Validation

. Each script was tested individually for functionality and error resilience.

. The integrated suite was validated on a Linux environment (Ubuntu 22.04).

. Simulated log errors were used to verify the monitoring script’s alerting behavior.

# 📝 Future Improvements

. Add email notifications for alerts.

. Implement cloud backup integration.

. Enhance the interface using dialog or whiptail for better user experience.
