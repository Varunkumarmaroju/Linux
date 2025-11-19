# User-Process-Management

This module covers **Linux user management** and **process monitoring**.  
These are essential for Cloud Engineers, DevOps, and System Admin roles.

##  1. Check Current Directory
pwd
Shows the working directory.

 2. View Users in /etc/passwd
tail -n 2 /etc/passwd
tail -n 3 /etc/passwd
Displays the last users registered in the system.

🧩 3. Create a New User
useradd vk
sudo useradd vk
Normal users cannot create accounts → requires sudo.
Creates a user entry in /etc/passwd.

🧩 4. Delete a User
userdel vk
sudo userdel vk
Removes the user account from the system.

🧩 5. Check Current User's Groups
groups
Shows all groups (sudo, docker, users, etc.).

🧩 6. Process Viewing (ps)
ps
Shows only processes running inside the current terminal.

Output example:
PID  TTY   TIME   CMD
372  pts/0 00:00  bash
559  pts/0 00:00  ps

🧩 7. View All System Processes (ps aux)
ps aux
Shows every running process, similar to Windows Task Manager → Details.
Columns include:
USER
PID
%CPU
%MEM
COMMAND

🧩 8. Real-Time Monitoring (top)
top
Inside TOP:
z → enable color
x → highlight sorted column
q → quit
TOP is similar to Windows Task Manager Performance tab.

📸 Screenshots

🔹 User Creation & Deletion
🔹 ps & ps aux Output
🔹 top Command

