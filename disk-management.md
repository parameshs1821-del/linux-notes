DISK MANAGEMENT

Command Name : df
Purpose : Display disk space usage of file systems.
Syntax : df [options]
Example : df -h
Sample Output : Filesystem Size Used Avail Use% Mounted on
Explanation : Shows total, used and available disk space. The -h option displays sizes in a human-readable format such as GB and MB.

⸻

Command Name : du
Purpose : Display disk space used by files or directories.
Syntax : du [options] filename/directory
Example : du -sh Documents
Sample Output : 25M Documents
Explanation : Shows how much storage a file or directory is using. -s gives the total and -h makes the size human-readable.

⸻

Command Name : lsblk
Purpose : Display disks and partitions.
Syntax : lsblk
Example : lsblk
Sample Output : NAME SIZE TYPE MOUNTPOINTS
Explanation : Lists storage devices, their partitions, sizes and mount points.

⸻

Command Name : mount
Purpose : Make a filesystem accessible through a directory.
Syntax : sudo mount device mount_point
Example : sudo mount /dev/sdb1 /mnt
Sample Output : (No output if successful)
Explanation : Connects a filesystem on a storage device to a directory such as /mnt so its files can be accessed.

⸻

Command Name : umount
Purpose : Unmount a mounted filesystem.
Syntax : sudo umount mount_point
Example : sudo umount /mnt
Sample Output : (No output if successful)
Explanation : Safely disconnects a mounted filesystem from its mount point.

⸻

Command Name : fdisk
Purpose : View or manage disk partitions.
Syntax : sudo fdisk [options]
Example : sudo fdisk -l
Sample Output : Disk and partition information
Explanation : fdisk -l lists available disks and their partition information.
