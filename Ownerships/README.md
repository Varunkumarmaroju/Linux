# Linux – File Ownership & Permissions 

## Topics Covered

1. **Change Permissions (chmod)**
   ->chmod 744 file.txt → rwx for user, r for group, r for others
   -> chmod u+x script.sh → Add execute for user
   ->chmod g-w file.txt → Remove write from group
   ->chmod o-r file.txt → Remove read from others  

2. **Change Ownership (chown)**
   ->sudo chown varunkumar:varunkumar file.txt
   ->Changes both **owner** and **group** to varunkumar.

3. **Change Group (chgrp)**
   ->sudo chgrp developers file.txt 
   -> Only changes the **group ownership**.

4. **Check Users**
   -> whoami → Current logged-in user  
     ->who → Active sessions  

5. **File Type**
   ->file file.txt → Detects type (ASCII, binary, script, etc.)

6. **Disk Usage**
   ->du -h → Human-readable file sizes  
   ->du -sh *→ Summary per file/folder  

7. **Disk Free Space**
   ->df -h → Free/used space in human-readable format  

8. **Manual Pages**
   ->man chmod → Help for chmod  
   ->man ls → Help for ls  

## ✅ Key Learnings
->Difference between **permissions** (rwx) & **ownership**.  
->How **user, group, others** can be controlled separately.  
->Importance of chown and chgrp for system administration.  

[View Images](./Images)
