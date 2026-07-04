3. VIEWING FILES

Command Name : cat
Purpose      : Display the entire file.
Syntax       : cat filename
Example      : cat story.txt
Sample Output:
Linux is an operating system.
AWS uses Linux servers.
Explanation  : Displays the complete file content.

⸻

Command Name : head
Purpose      : Display the first lines of a file.
Syntax       : head filename
Example      : head story.txt
head -5 story.txt
Sample Output:
1
2
3
4
5
Explanation  : Shows the beginning of a file.

⸻

Command Name : tail
Purpose      : Display the last lines of a file.
Syntax       : tail filename
Example      : tail story.txt
tail -20 story.txt
Sample Output:
96
97
98
99
100
Explanation  : Shows the end of a file.

⸻

Command Name : tail -f
Purpose      : Continuously monitor a file for new content.
Syntax       : tail -f filename
Example      : tail -f server.log
Sample Output:
New log entries appear automatically.
Explanation  : Commonly used to monitor log files.

⸻

Command Name : less
Purpose      : View a file one screen at a time.
Syntax       : less filename
Example      : less story.txt
Sample Output:
Displays one page of the file.
Explanation  : Allows scrolling forward and backward through large files.

⸻

Command Name : more
Purpose      : View a file one screen at a time.
Syntax       : more filename
Example      : more story.txt
Sample Output:
Displays one page of the file.
Explanation  : Similar to less but with fewer navigation features.
