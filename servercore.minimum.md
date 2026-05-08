# ServerCore Minimum Requirements

This document defines the minimal tools required to run and maintain the ServerCore environment.

ServerCore is designed for Linux-based systems, focusing on stability, automation, and lightweight server operations.

---

## 🧰 Core Tools

### 🐚 Shell environment
- zsh → interactive shell with better usability

### 📊 System monitoring
- htop → process and resource monitoring

### 🐍 Scripting
- python3 → automation and system scripts support

### 💻 Terminal
A functional terminal emulator is required:
- kitty (recommended)
- xfce4-terminal (fallback)
- xterm (minimal)

### 🔧 Version control
- git → required for ServerHub synchronization

---

## ⚙️ System dependencies (Debian-based)

For ServerCore on Debian systems:
- coreutils
- procps
- util-linux
- curl or wget (for remote operations)

---

## 🧠 Purpose

This minimal setup ensures:

- stable execution of ServerCore
- lightweight system performance
- compatibility with server environments
- reliable automation support

---

## ⚠️ Philosophy

ServerCore follows a strict minimalism approach:

- install only what is necessary
- avoid heavy dependencies
- prioritize stability over features
- keep system predictable and controlled

---

## 🚀 Target environment

- Debian-based systems
- Linux servers
- lightweight desktop environments (optional)

---

## 🔐 Optional Security & Network Stack

These components are not strictly required, but recommended depending on the ServerCore use case.

### 🚫 Fail2ban
Blocks suspicious login attempts and helps protect services like SSH from brute-force attacks.

### 🔥 UFW
A simple firewall for Linux systems that controls incoming and outgoing network traffic.

### 🔑 SSH
Secure Shell access for remote management of the ServerCore environment.

### 🗂️ Samba
File sharing service that allows network access to files between Linux and other systems (like Windows).