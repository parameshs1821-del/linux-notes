TEXT PROCESSING

Command Name : grep
Purpose : Search for text or patterns inside files.
Syntax : grep [options] pattern filename
Example : grep “ERROR” app.log
Sample Output : ERROR Database connection failed
Explanation : Displays lines containing the specified text or pattern.

⸻

Command Name : sort
Purpose : Sort lines of text.
Syntax : sort [options] filename
Example : sort names.txt
Sample Output : Lines displayed in sorted order
Explanation : Sorts file contents alphabetically by default and can also perform numerical or reverse sorting.

⸻

Command Name : uniq
Purpose : Remove or identify adjacent duplicate lines.
Syntax : uniq [options] filename
Example : sort names.txt | uniq
Sample Output : Unique lines from the file
Explanation : Filters adjacent duplicate lines. It is commonly used after sort so identical lines are placed together.

⸻

Command Name : cut
Purpose : Extract specific fields or characters from text.
Syntax : cut [options] filename
Example : cut -d “ “ -f2 employees.txt
Sample Output : Rahul Priya Arun
Explanation : Extracts selected fields. -d specifies the delimiter and -f specifies the field number.

⸻

Command Name : awk
Purpose : Process and extract field-based text.
Syntax : awk ‘pattern {action}’ filename
Example : awk ‘{print $2}’ employees.txt
Sample Output : Rahul Priya Arun
Explanation : Processes text field by field. $1, $2, $3 represent the first, second and third fields.

⸻

Command Name : sed
Purpose : Search, replace and transform text.
Syntax : sed ‘command’ filename
Example : sed ‘s/Rahul/Rohan/’ employees.txt
Sample Output : Lines are displayed with Rahul replaced by Rohan where matched.
Explanation : A stream editor commonly used to replace or modify text. Without an in-place option, the original file is not changed.

⸻

Command Name : wc
Purpose : Count lines, words and bytes/characters in files.
Syntax : wc [options] filename
Example : wc -l employees.txt
Sample Output : 10 employees.txt
Explanation : -l counts lines, -w counts words and -c counts bytes.

⸻

Command Name : tr
Purpose : Translate or delete characters.
Syntax : tr SET1 SET2
Example : echo “linux” | tr ‘a-z’ ‘A-Z’
Sample Output : LINUX
Explanation : Converts or replaces characters from standard input.

⸻

Command Name : tee
Purpose : Display output and save it to a file at the same time.
Syntax : command | tee filename
Example : ls | tee files.txt
Sample Output : Displays the file list and stores it in files.txt
Explanation : Useful when you want to see command output while also saving a copy.

⸻

Command Name : | (Pipe)
Purpose : Send the output of one command to another command.
Syntax : command1 | command2
Example : ps -ef | grep ssh
Sample Output : Processes containing ssh
Explanation : Connects commands so the output of the first becomes input to the second.
