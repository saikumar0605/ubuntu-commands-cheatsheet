# Ubuntu Commands Cheatsheet

## File and Directory Management
- `ls` - List directory contents
- `cd <directory>` - Change directory
- `pwd` - Print working directory
- `mkdir <directory>` - Create a new directory
- `rm <file>` - Remove a file
- `rm -r <directory>` - Remove a directory and its contents
- `cp <source> <destination>` - Copy files or directories
- `mv <source> <destination>` - Move or rename files or directories

## File Viewing
- `cat <file>` - View file contents
- `less <file>` - View file contents one screen at a time
- `head <file>` - View the first 10 lines of a file
- `tail <file>` - View the last 10 lines of a file

## User Management
- `whoami` - Show current user
- `id` - Show user ID and group ID
- `adduser <username>` - Add a new user
- `passwd <username>` - Change user password
- `deluser <username>` - Delete a user

## Process Management
- `ps` - Display active processes
- `top` - Show real-time processes
- `kill <PID>` - Kill a process by PID
- `killall <name>` - Kill processes by name

## Package Management (APT)
- `sudo apt update` - Update package lists
- `sudo apt upgrade` - Upgrade installed packages
- `sudo apt install <package>` - Install a package
- `sudo apt remove <package>` - Remove a package
- `sudo apt autoremove` - Remove unused packages

## Networking
- `ping <host>` - Test network connectivity
- `ifconfig` - Show network interfaces
- `curl <URL>` - Fetch content from a URL
- `wget <URL>` - Download files from a URL

## Disk Usage
- `df -h` - Show disk space usage
- `du -h <directory>` - Show directory size
- `mount` - Mount a filesystem
- `umount <device>` - Unmount a filesystem

## System Information
- `uname -a` - Show system information
- `hostname` - Show or set the hostname
- `uptime` - Show system uptime
- `free -h` - Show memory usage

## Permissions
- `chmod <permissions> <file>` - Change file permissions
- `chown <user>:<group> <file>` - Change file ownership

## Searching
- `find <directory> -name <name>` - Search for files by name
- `grep <pattern> <file>` - Search for a pattern in a file

## Archiving and Compression
- `tar -cvf <archive.tar> <files>` - Create a tar archive
- `tar -xvf <archive.tar>` - Extract a tar archive
- `gzip <file>` - Compress a file
- `gunzip <file.gz>` - Decompress a file

## Miscellaneous
- `echo <text>` - Print text to the terminal
- `date` - Show current date and time
- `clear` - Clear the terminal screen

This cheatsheet provides a quick reference to commonly used Ubuntu commands. Feel free to contribute additional commands!