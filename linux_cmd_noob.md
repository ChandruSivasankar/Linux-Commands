# Linux Command Line for Noobs

## A cheat sheet of commands

# Common Linux Commands

This document provides a quick reference for common Linux commands.

## Basic Commands

| Command | Description                                   | Example                                                     |
| ------- | --------------------------------------------- | ----------------------------------------------------------- |
| `ls`    | List directory contents.                      | `ls -l` (long listing), `ls -a` (show hidden files)         |
| `cd`    | Change directory.                             | `cd /home/user/documents`, `cd ..` (go up one directory)    |
| `pwd`   | Print working directory.                      | `pwd`                                                       |
| `mkdir` | Create a directory.                           | `mkdir new_directory`                                       |
| `rmdir` | Remove an empty directory.                    | `rmdir empty_directory`                                     |
| `rm`    | Remove files or directories.                  | `rm file.txt`, `rm -r directory` (recursive removal)        |
| `cp`    | Copy files or directories.                    | `cp file.txt new_file.txt`, `cp -r directory new_directory` |
| `mv`    | Move or rename files or directories.          | `mv file.txt new_location/`, `mv old_name.txt new_name.txt` |
| `touch` | Create an empty file or update its timestamp. | `touch new_file.txt`                                        |
| `cat`   | Display file contents.                        | `cat file.txt`                                              |
| `less`  | View file contents page by page.              | `less file.txt`                                             |
| `head`  | Display the first few lines of a file.        | `head -n 10 file.txt` (first 10 lines)                      |
| `tail`  | Display the last few lines of a file.         | `tail -f file.txt` (follow file for updates)                |
| `echo`  | Display a line of text.                       | `echo "Hello, world!"`                                      |

## File Manipulation

| Command | Description                                        | Example                                                                          |
| ------- | -------------------------------------------------- | -------------------------------------------------------------------------------- |
| `grep`  | Search for patterns in files.                      | `grep "pattern" file.txt`, `grep -i "pattern" file.txt` (case-insensitive)       |
| `find`  | Search for files and directories.                  | `find . -name "file.txt"`, `find . -type d` (find directories)                   |
| `wc`    | Count words, lines, and bytes in a file.           | `wc file.txt`                                                                    |
| `sort`  | Sort lines of text files.                          | `sort file.txt`                                                                  |
| `cut`   | Remove sections from each line of files            | `cut -d ',' -f 1 file.csv` (extract the first field from a comma separated file) |
| `sed`   | Stream editor for filtering and transforming text. | `sed 's/old/new/g' file.txt` (replace all occurrences of "old" with "new")       |
| `awk`   | Pattern scanning and text processing language.     | `awk '{print $1}' file.txt` (print the first column)                             |
| `diff`  | Compare files line by line.                        | `diff file1.txt file2.txt`                                                       |

## System Information and Control

| Command    | Description                                          | Example                                     |
| ---------- | ---------------------------------------------------- | ------------------------------------------- |
| `uname`    | Print system information.                            | `uname -a` (all information)                |
| `df`       | Display disk space usage.                            | `df -h` (human-readable format)             |
| `du`       | Estimate file space usage.                           | `du -sh` (summarized human-readable format) |
| `top`      | Display dynamic real-time view of running processes. | `top`                                       |
| `ps`       | List running processes.                              | `ps aux`                                    |
| `kill`     | Terminate a process.                                 | `kill PID` (process ID)                     |
| `shutdown` | Shut down the system.                                | `shutdown -h now` (halt now)                |
| `reboot`   | Reboot the system.                                   | `reboot`                                    |
| `whoami`   | Print current username                               | `whoami`                                    |
| `sudo`     | Execute a command as another user (usually root).    | `sudo apt update`                           |

## Networking

| Command              | Description                                                                                                           | Example                                      |
| -------------------- | --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| `ping`               | Test network connectivity.                                                                                            | `ping google.com`                            |
| `ifconfig` or `ip a` | Configure network interfaces.                                                                                         | `ip a` (show interfaces), `ifconfig eth0 up` |
| `netstat` or `ss`    | Display network connections, routing tables, interface statistics, masquerade connections, and multicast memberships. | `ss -tulnp`                                  |
| `ssh`                | Secure Shell for remote login.                                                                                        | `ssh user@host`                              |
| `wget`               | Download files from the web.                                                                                          | `wget https://example.com/file.txt`          |
| `curl`               | Transfer data with URLs.                                                                                              | `curl https://example.com`                   |
