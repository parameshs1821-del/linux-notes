BASH SCRIPTING

Command/Concept Name : #!/bin/bash
Purpose : Specify Bash as the script interpreter.
Syntax : #!/bin/bash
Example : #!/bin/bash
Sample Output : (No output)
Explanation : Called a shebang. It is normally placed on the first line of a Bash script.

⸻

Command Name : echo
Purpose : Display text or variable values.
Syntax : echo “text”
Example : echo “Hello Linux”
Sample Output : Hello Linux
Explanation : Prints information to the terminal.

⸻

Command Name : read
Purpose : Accept input from the user.
Syntax : read variable_name
Example : read name
Sample Output : (Waits for user input)
Explanation : Reads input and stores it in the specified variable.

⸻

Concept Name : Variable
Purpose : Store data that can be used later in the script.
Syntax : variable=value
Example : name=“Param esh”
Sample Output : (No output)
Explanation : Stores a value under a variable name. Do not put spaces around =.

⸻

Concept Name : $variable
Purpose : Access the value stored in a variable.
Syntax : $variable_name
Example : echo “$name”
Sample Output : Paramesh
Explanation : $ tells Bash to retrieve the value stored in the variable.

⸻

Concept Name : Comment
Purpose : Add notes or explanations to a script.
Syntax : # comment
Example : # This script displays a message
Sample Output : (No output)
Explanation : Bash ignores comments when executing the script.

⸻

Concept Name : if / elif / else
Purpose : Make decisions based on conditions.
Syntax : if [ condition ]; then … fi
Example : if [ “$age” -ge 18 ]; then echo “Adult”; else echo “Minor”; fi
Sample Output : Adult
Explanation : Executes different commands depending on whether a condition is true or false.

⸻

Concept Name : for loop
Purpose : Repeat commands for multiple values.
Syntax : for variable in values; do commands; done
Example : for i in 1 2 3; do echo “$i”; done
Sample Output : 1 2 3
Explanation : Repeats the commands once for each supplied value.

⸻

Concept Name : while loop
Purpose : Repeat commands while a condition remains true.
Syntax : while [ condition ]; do commands; done
Example : while [ “$count” -le 5 ]; do echo “$count”; ((count++)); done
Sample Output : 1 2 3 4 5
Explanation : Continues executing commands until the condition becomes false.

⸻

Concept Name : case
Purpose : Handle multiple possible choices.
Syntax : case value in pattern) commands ;; esac
Example : case “$choice” in 1) echo “Start” ;; 2) echo “Stop” ;; esac
Sample Output : Depends on the selected option
Explanation : Provides a clean way to handle several possible values.

⸻

Concept Name : Function
Purpose : Create a reusable block of commands.
Syntax : function_name() { commands; }
Example : greet() { echo “Hello”; }
Sample Output : Hello
Explanation : Allows the same block of commands to be called multiple times.

⸻

Concept Name : Command-Line Arguments
Purpose : Pass values to a script when running it.
Syntax : ./script.sh argument1 argument2
Example : ./hello.sh Paramesh
Sample Output : Depends on the script
Explanation : $1 represents the first argument, $2 the second and $@ represents all arguments.

⸻

Command Name : chmod +x
Purpose : Make a Bash script executable.
Syntax : chmod +x script.sh
Example : chmod +x hello.sh
Sample Output : (No output if successful)
Explanation : Adds execute permission so the script can be run directly.

⸻

Command Name : ./script.sh
Purpose : Execute a script from the current directory.
Syntax : ./script.sh
Example : ./hello.sh
Sample Output : Depends on the script
Explanation : Runs an executable script located in the current directory.
