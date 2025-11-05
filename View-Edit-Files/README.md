Linux – File Viewing & Editing Commands 
Commands Practiced :-

This session focuses on learning how to view, read, edit, and analyze file contents directly from the terminal.
Commands & Usage -

1. cat – Display file contents
cat file.txt

📘 Prints the entire content of the file on the terminal.

2. vim – Edit file using Vim editor
vim file.txt


Opens the file in the Vim text editor to create or modify content.
Use :wq to save and exit, :q! to quit without saving.

3. more – View file page by page
more file.txt
👁️ Shows file contents one screen at a time (useful for large files).

4. head – Display the beginning of a file
head file.txt
head -n 2 file.txt
📄 Shows the first 10 lines by default. Use -n to specify how many lines.

5. tail – Display the end of a file
tail file.txt
tail -n 2 file.txt
📄 Shows the last 10 lines by default. Use -n to specify line count.

6. sort – Sort lines in a file alphabetically
sort file.txt
📊 Arranges the lines of text in ascending order.

7. wc – Count words, lines, and characters
wc file.txt
📈 Displays count of lines, words, and bytes.
Use options:
-l → lines
-w → words
-c → characters

Example:
wc -l file.txt
Output Example
9  19 104 file.txt
Means:
9 lines
19 words
104 characters

🖼️ Screenshots

 Images
