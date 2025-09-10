# 🐧 Linux Commands 
Learn and master Linux! 📘
This repository contains a clean and organized reference of commonly used commands for everyday tasks and advanced system operations.
---

## 📂 File & Directory
| Command | Description |
|---------|-------------|
| `pwd` | Show current path |
| `ls -l -a -h` | List files (detailed, hidden, human-readable) |
| `cd dir/` | Change directory |
| `mkdir dir/` / `mkdir -p nested/dir/` | Create directory(s) |
| `rm file` / `rm -rf dir/` | Delete file/dir |
| `cp src dest` / `cp -r dir/ dest/` | Copy file/dir |
| `mv src dest` | Move or rename |
| `touch file.txt` | Create empty file |

---

## 📄 File Content
| Command | Description |
|---------|-------------|
| `cat file` | View file |
| `less file` | Scrollable view |
| `head -n 10 file` / `tail -n 10 file` | First/last lines |
| `wc file` | Count lines, words, chars |
| `cut -c 5-15 file` | Extract characters |
| `awk '{print $2}' file.csv` | Print column |
| `sed 's/old/new/g' file` | Replace text |

---

## 🔑 Permissions & Ownership
| Command | Description |
|---------|-------------|
| `ls -l` | Show permissions |
| `chmod 755 file.sh` | Change perms (rwxr-xr-x) |
| `chmod u+x file.sh` | Add execute (user) |
| `chown user file` | Change file owner |
| `chgrp group file` | Change group ownership |
| `umask` | Show default permission mask |

---

## 💻 System Info
| Command | Description |
|---------|-------------|
| `date` / `cal` | Show date & calendar |
| `uptime` | System uptime + load |
| `df -h` | Disk usage |
| `du -sh dir/` | Directory size |
| `free -h` | Memory usage |
| `ps aux` | All processes |
| `top` / `htop` | Live monitoring |
| `history` | Command history |

---

## 🌐 Networking
| Command | Description |
|---------|-------------|
| `ssh user@host` | Remote login |
| `scp file user@host:/path/` | Copy file to remote |
| `scp -r dir/ user@host:/path/` | Copy directory |
| `ftp server.com` | FTP session |

---

## 🔍 Search
| Command | Description |
|---------|-------------|
| `find . -name "*.txt"` | Find files |
| `find /home -size +100M` | Find files >100MB |
| `grep "error" file.log` | Search text in file |
| `grep -r "error" .` | Recursive search |
| `locate file.txt` | Locate file (index) |
| `which cmd` | Show path of command |
| `whereis cmd` | Binary, source, man page |

---

## ⚙️ Process Management
| Command | Description |
|---------|-------------|
| `kill PID` | Kill process by PID |
| `killall name` | Kill by process name |
| `pkill -9 name` | Force kill by name |

---

## 🚀 Advanced
| Command | Description |
|---------|-------------|
| `tail -n 50 -f log.txt` | Monitor last 50 lines of log |
| `watch -n 2 df -h` | Run command every 2s |
| `rsync -avh src/ dest/` | Sync directories (preserve perms) |
| `touch -t 202501151430 file.txt` | Change file timestamp |

- Use `man <command>` or `<command> --help` for details.  
- ⚠️ Be careful with destructive commands like `rm -rf`.  
- ⚠️ Always experiment in a safe environment (like a VM or WSL) before running commands on real systems.  

---
