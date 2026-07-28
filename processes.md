PROCESSES

Command Name : ps
Purpose : Display running processes in the current terminal.
Syntax : ps
Example : ps
Sample Output : PID TTY TIME CMD
Explanation : Shows processes associated with the current terminal session.

⸻

Command Name : ps -ef
Purpose : Display all running processes with detailed information.
Syntax : ps -ef
Example : ps -ef
Sample Output : UID PID PPID C STIME TTY TIME CMD
Explanation : Shows all system processes along with their PID, parent PID, user and command.

⸻

Command Name : top
Purpose : Monitor running processes and system resources in real time.
Syntax : top
Example : top
Sample Output : Displays CPU, memory and process information continuously.
Explanation : Helps identify processes consuming high CPU or memory. Press q to exit.

⸻

Command Name : htop
Purpose : Display and manage processes interactively.
Syntax : htop
Example : htop
Sample Output : Interactive process list with CPU and memory information.
Explanation : Provides a more user-friendly interface for monitoring processes than top.

⸻

Command Name : kill
Purpose : Stop a process using its PID.
Syntax : kill PID
Example : kill 2456
Sample Output : (No output if successful)
Explanation : Sends a termination signal to the specified process.

⸻

Command Name : killall
Purpose : Stop processes using their process name.
Syntax : killall process_name
Example : killall sleep
Sample Output : (No output if successful)
Explanation : Terminates processes matching the specified name.

⸻

Command Name : jobs
Purpose : Display jobs running or stopped in the current shell.
Syntax : jobs
Example : jobs
Sample Output : [1]+ Running sleep 300 &
Explanation : Shows background and suspended jobs started from the current terminal.

⸻

Command Name : bg
Purpose : Resume a stopped job in the background.
Syntax : bg
Example : bg
Sample Output : [1]+ sleep 300 &
Explanation : Continues a suspended job while allowing the terminal to remain usable.

⸻

Command Name : fg
Purpose : Bring a background job to the foreground.
Syntax : fg
Example : fg
Sample Output : sleep 300
Explanation : Moves a background or suspended job back to the active terminal.

⸻

Command Name : nohup
Purpose : Keep a command running after logging out or closing the terminal.
Syntax : nohup command &
Example : nohup python3 app.py &
Sample Output : nohup: ignoring input and appending output to ‘nohup.out’
Explanation : Runs a process so that it can continue after the terminal session ends.
