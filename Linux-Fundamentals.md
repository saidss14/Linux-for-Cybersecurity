# Day 1 - Linux Fundamentals

## What is Linux?

Linux is an operating system (OS) that acts as a bridge between the user and the computer hardware. It manages system resources and allows applications to communicate with the hardware.

### Responsibilities of an Operating System
- File and folder management
- Memory (RAM) management
- CPU scheduling and process management
- User accounts and permissions
- Network communication
- Running applications

---

## Why Linux is Important in Cybersecurity

Linux is widely used in cybersecurity because most servers, cloud systems, and security tools run on Linux.

### Reasons Linux is Popular

### 1. Open Source
Linux is free to use and modify, making it cost-effective for organizations.

### 2. Stability
Linux servers can run for long periods with minimal downtime.

### 3. Performance
Linux consumes fewer system resources compared to many other operating systems.

### 4. Control
Administrators have detailed control over:
- Users
- Permissions
- Services
- Networking
- Security settings

### 5. Security Tools
Many cybersecurity tools are designed primarily for Linux:
- Nmap
- Wireshark
- Suricata
- Wazuh
- Metasploit

### 6. Cloud Computing
A large portion of cloud infrastructure runs on Linux, making Linux knowledge essential for cybersecurity professionals.

---

## Linux Workflow

When a command is entered, it passes through several layers:

```text
User
 ↓
Terminal
 ↓
Shell
 ↓
Kernel
 ↓
Hardware
```

### Terminal
The terminal is the interface where commands are entered.

Examples:

```bash
pwd
ls
```

### Shell
The shell interprets commands and communicates with the operating system.

Common Shells:
- Bash
- Zsh
- Fish

### Kernel
The kernel is the core of Linux.

Functions:
- CPU management
- Memory management
- Process management
- Device communication
- Networking

---

## Linux File System

Linux uses a single directory structure that begins at the root directory:

```bash
/
```
---

## Linux Distributions

A Linux distribution is a customized version of Linux designed for specific users or purposes.

| Distribution | Purpose |
|-------------|----------|
| Ubuntu | Beginners and developers |
| Debian | Stability and servers |
| Kali Linux | Cybersecurity and penetration testing |
| Red Hat Enterprise Linux | Enterprise environments |
| Linux Mint | Easy transition from Windows |
| Ubuntu Server | Servers and cloud systems |

---

# Commands Practiced

## 1. pwd

**Print Working Directory**

Displays the current location in the file system.

```bash
pwd
```

Example Output:

```bash
/home/sai
```

Use Cases:
- Verify current location
- Confirm where files will be created
- Avoid mistakes before running commands

---

## 2. ls

**List**

Lists files and folders in the current directory.

```bash
ls
```

Use Cases:
- View directory contents
- Check whether files exist
- Find folder names

---

## 3. ls -l

**Long Listing Format**

Displays detailed information about files.

```bash
ls -l
```

Shows:
- Permissions
- Owner
- File size
- Modification date
- File name

---

## 4. ls -a

**List All**

Displays all files including hidden files.

```bash
ls -a
```

Hidden files start with a dot (.).

Examples:

```bash
.bashrc
.profile
```

---

## 5. cd ~

**Change Directory to Home**

Returns to the home directory.

```bash
cd ~
```

Useful when navigating through multiple directories.

---

## 6. cd ..

**Move to Parent Directory**

Moves one level up in the directory structure.

```bash
cd ..
```

Example:

Before:

```bash
/ home / sai / Documents
```

After:

```bash
/ home / sai
```

---

## 7. mkdir

**Make Directory**

Creates a new directory.

```bash
mkdir LinuxPractice
```

Use Cases:
- Organizing files
- Creating project folders
- Building lab environments

---

## 8. clear

**Clear Terminal Screen**

Clears terminal output.

```bash
clear
```

Useful when the terminal becomes cluttered.

---

## 9. TAB

**Auto Completion**

Example:

```bash
cd Lin
```

Press `TAB`

```bash
cd LinuxPractice
```

Benefits:
- Faster navigation
- Fewer typing mistakes

---

## 10. Command History

Use `↑` and `↓` arrow keys to access previously executed commands.

Benefits:
- Reuse commands quickly
- Reduce typing effort
- Correct previous commands

---

## Key Takeaways

- Learned the role of Linux in cybersecurity.
- Understood the Linux architecture (Terminal → Shell → Kernel).
- Explored important Linux directories.
- Practiced basic navigation commands.
- Learned how to create directories and navigate the file system.
- Built a foundation for future Linux, SOC Analyst, and cybersecurity studies.