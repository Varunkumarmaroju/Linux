Day 2 - Linux File Operations

1. Create Multiple Files
touch aws.txt cloud.txt
-> Creates empty files aws.txt and cloud.txt.

2. View File Content
cat aws.txt
cat cloud.txt
->Displays file content (empty initially).

3. Edit a File
nano aws.txt
Type content like hello learn aws. Save & exit (CTRL+O, CTRL+X).

4. Rename a File
mv cloud.txt cloud_renamed.txt
Renames cloud.txt to cloud_renamed.txt.

5. Copy a File
cp aws.txt aws_backup.txt
Creates a copy aws_backup.txt.

6. Delete a File
rm aws_backup.txt
Removes the backup file.

7. List Files with Details
ls -l
Shows size, permissions, owner, and modification date.

8. List All Files (including hidden)
ls -a
Shows all files including hidden ones.

9. List Files by Pattern
ls *.txt
Shows all .txt files available.

10. View File with Pagination
less aws.txt
Navigate with arrows, exit with q.

[Image](./Images/Day2-cmds.png)
