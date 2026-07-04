4. FINDING FILES

Command Name : find
Purpose      : Search for files and directories.
Syntax       : find path options
Example      : find . -name “.txt”
find . -type f
find . -type d
find . -type d -empty
find . -type f -name “.txt” -empty
Sample Output:
./story.txt
./notes.txt
Explanation  : Searches files and directories based on different conditions.

⸻

Command Name : which
Purpose      : Locate the executable of a command.
Syntax       : which command
Example      : which python3
Sample Output:
/usr/bin/python3
Explanation  : Shows the executable path of a command.

⸻

Command Name : whereis
Purpose      : Locate the binary, source and manual page.
Syntax       : whereis command
Example      : whereis python3
Sample Output:
python3: /usr/bin/python3 /usr/share/man/man1/python3.1.gz
Explanation  : Displays related locations for a command.

⸻

Command Name : locate
Purpose      : Search files using a database.
Syntax       : locate filename
Example      : locate story.txt
locate Downloads
Sample Output:
/home/paramesh/story.txt
Explanation  : Searches much faster than find because it uses an indexed database. Use ‘sudo updatedb’ to update the database if recent files are not found.
