Day 2: File and Directory Management

1. mkdir (Make Directory)
Create folders:
mkdir notes
mkdir projects

Create multiple folders:
mkdir day1 day2 day3


2. rmdir (Remove Directory)
Delete an empty folder:
rmdir day3

If the folder contains files, rmdir won't work.


3. touch
Create empty files:
touch notes.txt
touch day2.txt

Create multiple files:
touch file1.txt file2.txt file3.txt


4. cp (Copy)
Copy a file:
cp notes.txt backup.txt

Copy a folder:
cp -r projects projects_backup


5. mv (Move / Rename)
Rename a file:
mv notes.txt linux_notes.txt

Move a file to another folder:
mv linux_notes.txt projects/


6. rm (Remove)
Delete a file:
rm file1.txt

Delete a folder and everything inside it:
rm -r projects_backup

Be careful with rm; deleted files don't go to a recycle bin.
------------------------------------------------------------

Key Takeaways:
- mkdir → creates directories
- rmdir → removes empty directories only
- touch → creates empty files
- cp → copies files/folders (-r for folders)
- mv → moves or renames files/folders
- rm → deletes files/folders permanently
- Always be careful with rm -r command