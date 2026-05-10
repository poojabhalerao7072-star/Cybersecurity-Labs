==============================
1. USER INFORMATION COMMANDS
==============================

whoami - Displays currently logged-in user

id - Shows user ID (UID), group ID (GID), and groups

hostname - Displays system hostname


==============================
2. DIRECTORY NAVIGATION COMMANDS
==============================

pwd - Shows present working directory

ls - Lists files and directories

ls -la - Lists all files including hidden files with detailed permissions

cd - Changes current directory

cd .. - Moves one directory back

clear - Clears terminal screen


==============================
3. FILE & DIRECTORY MANAGEMENT
==============================

mkdir cyberlab - Creates a new directory

touch notes.txt - Creates an empty file

cp notes.txt backup.txt - Copies a file

mv backup.txt backup2.txt - Renames or moves files

rm backup2.txt - Deletes a file

rmdir test - Removes empty directory


==============================
4. FILE VIEWING & EDITING
==============================

cat notes.txt - Displays file content

nano notes.txt - Opens Nano text editor

head notes.txt - Displays first 10 lines of file

tail notes.txt - Displays last 10 lines of file


==============================
5. NETWORKING COMMANDS
==============================

ip a - Displays IP address and network interfaces

ping google.com - Tests internet connectivity

netstat -tulnp - Displays active listening ports and services

ss -tulnp - Displays socket statistics and listening ports

ifconfig - Displays network interface configuration

hostname -I - Displays system IP address


==============================
6. PROCESS MANAGEMENT COMMANDS
==============================

ps aux - Displays running processes

top - Real-time process monitoring

kill PID - Terminates a process using Process ID

htop - Interactive process viewer


==============================
7. USER & GROUP MANAGEMENT
==============================

sudo adduser student - Creates a new user

sudo useradd student2 - Creates a user using low-level utility

passwd student - Changes password for user

su student - Switches user account

groups - Displays groups of current user

sudo userdel student - Deletes a user


==============================
8. PERMISSION MANAGEMENT
==============================

ls -l - Displays file permissions

ls -ltr - Displays files sorted by modification time

chmod 777 notes.txt - Gives read, write, execute permissions to everyone

chmod +x script.sh - Makes script executable

chown kali:kali notes.txt - Changes file ownership


==============================
9. SYSTEM INFORMATION COMMANDS
==============================

uname -a - Displays kernel and system information

df -h - Displays disk usage

free -h - Displays memory usage

uptime - Shows system running time

history - Displays previously executed commands


==============================
10. PACKAGE MANAGEMENT
==============================

sudo apt update - Updates package lists

sudo apt upgrade - Upgrades installed packages

sudo apt install net-tools - Installs net-tools package

sudo apt remove package_name - Removes installed package


==============================
11. IMPORTANT INTERVIEW QUESTIONS
==============================

1. What is the difference between adduser and useradd?

adduser is an interactive command used for creating users easily.
It automatically creates the home directory and sets user details.
useradd is a low-level utility command mostly used in scripting and automation.


2. What is the difference between ls -l and ls -ltr?

ls -l displays detailed information about files and directories.
ls -ltr displays files in long listing format sorted by modification time.
It helps identify recently modified files easily.


3. What is the difference between kill, kill -9 and kill -3?

kill sends SIGTERM signal which gracefully terminates a process.
kill -9 forcefully kills the process using SIGKILL signal.
kill -3 sends SIGQUIT signal and may generate a core dump.


4. What is the difference between cp and mv?

cp is used to copy files and directories from one location to another.
mv is used to move or rename files and directories.
cp keeps the original file while mv changes its location/name.


5. What is the difference between su and sudo?

su switches from the current user to another user account.
sudo executes commands with root/superuser privileges.
sudo is considered safer because it gives temporary elevated access.


6. What is the use of chmod 777?

chmod 777 gives read, write, and execute permissions to all users.
It provides full access to owner, group, and others.
It is generally avoided in production systems due to security risks.


7. Why is kill -9 considered forceful termination?

kill -9 sends the SIGKILL signal directly to the process.
The process cannot ignore or handle this signal.
It immediately stops the process forcefully.


8. What is the difference between ps aux and top?

ps aux displays a snapshot of all running processes.
top provides real-time monitoring of CPU, memory, and processes.
top updates continuously while ps aux shows static output.
