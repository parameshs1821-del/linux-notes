USERS & GROUPS

Command Name : whoami
Purpose : Display the current logged-in user.
Syntax : whoami
Example : whoami
Sample Output : paramesh
Explanation : Shows the username of the user currently using the terminal.

⸻

Command Name : who
Purpose : Display users currently logged into the system.
Syntax : who
Example : who
Sample Output : paramesh tty2 2026-07-28 10:30
Explanation : Shows logged-in users and their terminal sessions.

⸻

Command Name : users
Purpose : Display currently logged-in usernames.
Syntax : users
Example : users
Sample Output : paramesh
Explanation : Shows a simple list of users currently logged into the system.

⸻

Command Name : id
Purpose : Display user ID, group ID and group memberships.
Syntax : id username
Example : id paramesh
Sample Output : uid=1000(paramesh) gid=1000(paramesh) groups=1000(paramesh),27(sudo)
Explanation : Shows the UID, primary GID and groups associated with a user.

⸻

Command Name : groups
Purpose : Display the groups a user belongs to.
Syntax : groups username
Example : groups paramesh
Sample Output : paramesh : paramesh sudo
Explanation : Shows all groups associated with the specified user.

⸻

Command Name : adduser
Purpose : Create a new user.
Syntax : sudo adduser username
Example : sudo adduser john
Sample Output : Adding user ‘john’…
Explanation : Creates a new user account and home directory.

⸻

Command Name : passwd
Purpose : Change or set a user’s password.
Syntax : sudo passwd username
Example : sudo passwd john
Sample Output : passwd: password updated successfully
Explanation : Sets or changes the password of a user account.

⸻

Command Name : su
Purpose : Switch from one user to another.
Syntax : su - username
Example : su - john
Sample Output : john@hostname:~$
Explanation : Opens a login shell using another user’s account.

⸻

Command Name : usermod
Purpose : Modify an existing user account or add a user to a group.
Syntax : sudo usermod -aG groupname username
Example : sudo usermod -aG developers john
Sample Output : (No output)
Explanation : Adds the user to an additional group. -aG keeps the user’s existing supplementary group memberships.

⸻

Command Name : userdel
Purpose : Delete a user account.
Syntax : sudo userdel username
Example : sudo userdel john
Sample Output : (No output)
Explanation : Removes a user account from the system. Use sudo userdel -r john to also remove the user’s home directory.

⸻

Command Name : groupadd
Purpose : Create a new group.
Syntax : sudo groupadd groupname
Example : sudo groupadd developers
Sample Output : (No output)
Explanation : Creates a new Linux group.

⸻

Command Name : groupdel
Purpose : Delete a group.
Syntax : sudo groupdel groupname
Example : sudo groupdel developers
Sample Output : (No output)
Explanation : Removes the specified group from the system.

⸻

Command Name : sudo
Purpose : Run a command with administrator privileges.
Syntax : sudo command
Example : sudo adduser john
Sample Output : Depends on the command being executed.
Explanation : Allows an authorized user to perform administrative tasks with elevated privileges.
