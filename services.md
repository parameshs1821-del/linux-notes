SERVICES

Command Name : systemctl status
Purpose : Check the current status of a service.
Syntax : systemctl status service_name
Example : systemctl status ssh
Sample Output : Active: active (running)
Explanation : Shows whether a service is running, stopped or failed.

⸻

Command Name : systemctl start
Purpose : Start a service.
Syntax : sudo systemctl start service_name
Example : sudo systemctl start ssh
Sample Output : (No output if successful)
Explanation : Starts the specified service immediately.

⸻

Command Name : systemctl stop
Purpose : Stop a running service.
Syntax : sudo systemctl stop service_name
Example : sudo systemctl stop ssh
Sample Output : (No output if successful)
Explanation : Stops the specified service.

⸻

Command Name : systemctl restart
Purpose : Restart a service.
Syntax : sudo systemctl restart service_name
Example : sudo systemctl restart ssh
Sample Output : (No output if successful)
Explanation : Stops and starts the service again, commonly after configuration changes.

⸻

Command Name : systemctl reload
Purpose : Reload a service configuration without a full restart when supported.
Syntax : sudo systemctl reload service_name
Example : sudo systemctl reload ssh
Sample Output : (No output if successful)
Explanation : Reloads configuration while minimizing service interruption.

⸻

Command Name : systemctl enable
Purpose : Configure a service to start automatically during boot.
Syntax : sudo systemctl enable service_name
Example : sudo systemctl enable ssh
Sample Output : Created symlink …
Explanation : Makes the service start automatically when Linux boots.

⸻

Command Name : systemctl disable
Purpose : Prevent a service from automatically starting during boot.
Syntax : sudo systemctl disable service_name
Example : sudo systemctl disable ssh
Sample Output : Removed …
Explanation : Disables automatic startup without necessarily stopping the currently running service.

⸻

Command Name : systemctl is-active
Purpose : Check whether a service is currently running.
Syntax : systemctl is-active service_name
Example : systemctl is-active ssh
Sample Output : active
Explanation : Quickly reports the current running state of a service.

⸻

Command Name : systemctl is-enabled
Purpose : Check whether a service starts automatically at boot.
Syntax : systemctl is-enabled service_name
Example : systemctl is-enabled ssh
Sample Output : enabled
Explanation : Shows whether automatic startup is configured.

⸻

Command Name : journalctl
Purpose : View system and service logs.
Syntax : journalctl [options]
Example : journalctl -u ssh
Sample Output : SSH service log entries.
Explanation : Used for troubleshooting system and service problems by examining logs.
