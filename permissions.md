2. PERMISSIONS & OWNERSHIP

Command Name : chmod
Purpose      : Change file or directory permissions.
Syntax       : chmod permissions filename
Example      : chmod 755 script.sh
chmod u+x script.sh
Sample Output:
(No output)
Explanation  : Controls read, write and execute permissions.

⸻

Command Name : chown
Purpose      : Change the owner of a file or directory.
Syntax       : sudo chown owner:group filename
Example      : sudo chown paramesh:paramesh notes.txt
Sample Output:
(No output)
Explanation  : Changes file ownership.

⸻

Command Name : ls -l
Purpose      : Display permissions, owner and group.
Syntax       : ls -l
Example      : ls -l
Sample Output:
-rw-r–r– 1 paramesh paramesh 120 Jul 4 notes.txt
Explanation  : Shows detailed file information.
