Linux Fundamentals - Day 2
Topic: File and Directory Management

In this section, we learn basic Linux file and directory management commands. These commands are essential for creating, organizing, copying, moving, and deleting files/folders in the Linux system. They form the foundation for daily terminal usage and cybersecurity work.

------------------------------------------------------------

1. mkdir (Make Directory)
Used to create directories (folders).

Create a folder:
mkdir notes
mkdir projects

Create multiple folders:
mkdir day1 day2 day3


------------------------------------------------------------

2. rmdir (Remove Directory)
Used to delete EMPTY directories only.

Example:
rmdir day3

Note:
- If the folder contains files, rmdir will not work.


------------------------------------------------------------

3. touch
Used to create empty files.

Create single files:
touch notes.txt
touch day2.txt

Create multiple files:
touch file1.txt file2.txt file3.txt


------------------------------------------------------------

4. cp (Copy)
Used to copy files and directories.

Copy a file:
cp notes.txt backup.txt

Copy a folder:
cp -r projects projects_backup

Note:
- -r means recursive (required for folders)


------------------------------------------------------------

5. mv (Move / Rename)
Used to move or rename files and folders.

Rename a file:
mv notes.txt linux_notes.txt

Move a file:
mv linux_notes.txt projects/


------------------------------------------------------------

6. rm (Remove)
Used to delete files and directories.

Delete a file:
rm file1.txt

Delete a folder:
rm -r projects_backup

Warning:
- Deleted files do NOT go to recycle bin
- Be very careful with rm -r command


------------------------------------------------------------

Key Takeaways:
- mkdir → create folders
- rmdir → remove empty folders
- touch → create files
- cp → copy files/folders
- mv → move or rename files/folders
- rm → delete files/folders permanently
- Always double-check before using rm -r