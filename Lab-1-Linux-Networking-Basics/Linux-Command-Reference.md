# Linux & Networking Command Reference

---

## 1. User Information Commands

- `whoami` - Displays currently logged-in user
- `id` - Shows user ID (UID), group ID (GID), and groups
- `hostname` - Displays system hostname

---

## 2. Directory Navigation Commands

- `pwd` - Shows present working directory
- `ls` - Lists files and directories
- `ls -la` - Lists all files including hidden files with detailed permissions
- `cd` - Changes current directory
- `cd ..` - Moves one directory back
- `clear` - Clears terminal screen

---

## 3. File & Directory Management

- `mkdir cyberlab` - Creates a new directory
- `touch notes.txt` - Creates an empty file
- `cp notes.txt backup.txt` - Copies a file
- `mv backup.txt backup2.txt` - Renames or moves files
- `rm backup2.txt` - Deletes a file
- `rmdir test` - Removes empty directory

---

## 4. File Viewing & Editing

- `cat notes.txt` - Displays file content
- `nano notes.txt` - Opens Nano text editor
- `head notes.txt` - Displays first 10 lines of file
- `tail notes.txt` - Displays last 10 lines of file

---

## 5. Networking Commands

- `ip a` - Displays IP address and network interfaces
- `ping google.com` - Tests internet connectivity
- `netstat -tulnp` - Displays active listening ports and services
- `ss -tulnp` - Displays socket statistics and listening ports
- `ifconfig` - Displays network interface configuration
- `hostname -I` - Displays system IP address

---

## 6. Process Management Commands

- `ps aux` - Displays running processes
- `top` - Real-time process monitoring
- `kill PID` - Terminates a process using Process ID
- `htop` - Interactive process viewer

---

## 7. User & Group Management

- `sudo adduser student` - Creates a new user
- `sudo useradd student2` - Creates a user using low-level utility
- `passwd student` - Changes password for user
- `su student` - Switches user account
- `groups` - Displays groups of current user
- `sudo userdel student` - Deletes a user

---

## 8. Permission Management

- `ls -l` - Displays file permissions
- `ls -ltr` - Displays files sorted by modification time
- `chmod 777 notes.txt` - Gives read, write, execute permissions to everyone
- `chmod +x script.sh` - Makes script executable
- `chown kali:kali notes.txt` - Changes file ownership

---

## 9. System Information Commands

- `uname -a` - Displays kernel and system information
- `df -h` - Displays disk usage
- `free -h` - Displays memory usage
- `uptime` - Shows system running time
- `history` - Displays previously executed commands

---

## 10. Package Management

- `sudo apt update` - Updates package lists
- `sudo apt upgrade` - Upgrades installed packages
- `sudo apt install net-tools` - Installs net-tools package
- `sudo apt remove package_name` - Removes installed package

---

# Important Interview Questions

## 1. What is the difference between adduser and useradd?

`adduser` is an interactive command used for creating users easily.  
`useradd` is a low-level utility command mostly used in scripting and automation.

---

## 2. What is the difference between ls -l and ls -ltr?

`ls -l` displays detailed file information.  
`ls -ltr` displays files sorted by modification time.

---

## 3. What is the difference between kill, kill -9 and kill -3?

`kill` gracefully terminates a process.  
`kill -9` forcefully kills the process.  
`kill -3` sends SIGQUIT signal and may generate a core dump.

---

## 4. What is the difference between cp and mv?

`cp` copies files/directories.  
`mv` moves or renames files/directories.

---

## 5. What is the difference between su and sudo?

`su` switches to another user account.  
`sudo` executes commands with superuser privileges.
