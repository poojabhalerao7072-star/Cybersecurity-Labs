# Linux & Networking Basics Lab

## Objective

The objective of this lab is to learn Linux fundamentals, networking basics, file handling, user management, and permissions using Kali Linux.

---

# Environment Setup

| Component | Details |
|---|---|
| Operating System | Kali Linux |
| Virtualization | VMware / VirtualBox |
| Tools Used | Linux Terminal |

---

# Basic Linux Commands

| Command | Description |
|---|---|
| `whoami` | Displays the currently logged-in user |
| `pwd` | Shows the present working directory |
| `ls` | Lists files and directories |
| `ls -la` | Lists all files including hidden files with detailed permissions |
| `cd` | Changes the current directory |

---

# File and Folder Operations

| Command | Description |
|---|---|
| `mkdir cyberlab` | Creates a new directory named cyberlab |
| `touch notes.txt` | Creates an empty file |
| `cp notes.txt backup.txt` | Copies notes.txt to backup.txt |
| `mv backup.txt backup2.txt` | Renames or moves a file |
| `rm backup2.txt` | Deletes a file permanently |

---

# File Viewing and Editing

| Command | Description |
|---|---|
| `nano notes.txt` | Opens the file in Nano text editor |
| `cat notes.txt` | Displays file contents in terminal |

---

# Networking Commands

| Command | Description |
|---|---|
| `ip a` | Displays IP address and network interfaces |
| `ping google.com` | Tests internet/network connectivity |
| `netstat -tulnp` | Displays active network connections and listening ports |

---

# Process Monitoring Commands

| Command | Description |
|---|---|
| `ps aux` | Displays running processes |
| `top` | Shows real-time system and process monitoring |

---

# User Management Commands

| Command | Description |
|---|---|
| `sudo adduser student` | Creates a new Linux user |
| `su student` | Switches to another user account |

---

# Permission Management

| Command | Description |
|---|---|
| `chmod 777 notes.txt` | Gives read, write, and execute permissions to everyone |
| `ls -l` | Displays file permissions and ownership |

---

# Tasks Performed

- Created directories and files
- Navigated Linux file system
- Edited files using Nano editor
- Checked IP address and connectivity
- Viewed running processes
- Created Linux users
- Modified file permissions

---

# Screenshots

Screenshots are stored inside the `screenshots/` folder.

Example:
- whoami command
- IP address using `ip a`
- Ping test
- File permission changes

---

# Skills Learned

- Linux Command Line Interface (CLI)
- File Management
- Linux Networking Basics
- User & Permission Management
- Process Monitoring

---

# Key Learnings

- Understanding Linux directory structure
- Working with files and folders
- Managing Linux users and permissions
- Monitoring processes and network activity
- Using Linux commands efficiently

---

# Conclusion

This lab provided hands-on experience with Linux and networking fundamentals which are essential for cybersecurity professionals, ethical hackers, and penetration testers.
