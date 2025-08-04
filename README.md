# macOS Terminal Commands — Beginner to Pro

A structured reference of macOS terminal commands from beginner (Level 1) to advanced (Level 5), organized by category.

---

## Level 1 — Noobie

### Navigation

| Command            | Description                      |
|--------------------|--------------------------------|
| `pwd`              | Print current directory path    |
| `ls`               | List files and directories      |
| `cd Desktop`       | Change to Desktop directory     |
| `cd ..`            | Go up one directory             |
| `cd ~`             | Go to home directory            |
| `clear`            | Clear terminal screen           |

### File Management

| Command            | Description                      |
|--------------------|--------------------------------|
| `mkdir test`       | Create directory named 'test'   |
| `touch file.txt`   | Create an empty file             |
| `mv file.txt new.txt` | Rename file                   |
| `cp file.txt copy.txt` | Copy file                    |
| `rm file.txt`      | Delete file                     |

### Viewing/Editing Files

| Command            | Description                      |
|--------------------|--------------------------------|
| `cat file.txt`     | View file content               |
| `open file.txt`    | Open file with default app     |
| `nano file.txt`    | Edit file in terminal           |

### Searching

| Command            | Description                      |
|--------------------|--------------------------------|
| `find . -name file.txt` | Find file in current directory tree |

### System Info

| Command            | Description                      |
|--------------------|--------------------------------|
| `whoami`           | Show current username           |
| `date`             | Show current date and time      |
| `uptime`           | System uptime                   |

### Permissions

| Command            | Description                      |
|--------------------|--------------------------------|
| `chmod +x script.sh` | Make script executable          |

### Fun/Surprise Commands

| Command            | Description                      |
|--------------------|--------------------------------|
| `say "Hello world"` | Speak text aloud                |

---

## Level 2 — Beginner

### Navigation

| Command            | Description                      |
|--------------------|--------------------------------|
| `ls -la`           | List all files with details      |
| `cd ~/Documents`   | Navigate to Documents folder     |

### File Management

| Command            | Description                      |
|--------------------|--------------------------------|
| `rm -r folder/`    | Delete folder and contents       |
| `cp -R folder/ backup/` | Copy folder and contents     |

### Viewing/Editing Files

| Command            | Description                      |
|--------------------|--------------------------------|
| `less file.txt`    | Scrollable file viewer           |
| `head -n 10 file.txt` | First 10 lines                |
| `tail -n 10 file.txt` | Last 10 lines                 |

### Searching

| Command            | Description                      |
|--------------------|--------------------------------|
| `grep "text" file.txt` | Search for text in file       |

### System Info

| Command            | Description                      |
|--------------------|--------------------------------|
| `top`              | Real-time system usage           |
| `df -h`            | Disk space in human-readable     |

### Permissions

| Command            | Description                      |
|--------------------|--------------------------------|
| `ls -l`            | Show permissions on files        |
| `chmod 755 script.sh` | Set rwxr-xr-x permissions       |

### Fun/Surprise Commands

| Command            | Description                      |
|--------------------|--------------------------------|
| `cal`              | Show current month calendar      |

---

## Level 3 — Intermediate

### Navigation

| Command            | Description                      |
|--------------------|--------------------------------|
| `pushd dir/`       | Save current dir and go to new one |
| `popd`             | Return to previous dir           |

### File Management

| Command            | Description                      |
|--------------------|--------------------------------|
| `mv *.txt backup/` | Move all .txt files to folder    |
| `rm *.log`         | Delete all .log files            |

### Viewing/Editing Files

| Command            | Description                      |
|--------------------|--------------------------------|
| `vi file.txt`      | Open file in vi editor           |
| `diff file1.txt file2.txt` | Compare files              |

### Searching

| Command            | Description                      |
|--------------------|--------------------------------|
| `grep -r "text" .` | Recursive search                |
| `find / -name "file"` | Search from root (slow)       |

### System Info

| Command            | Description                      |
|--------------------|--------------------------------|
| `env`              | Show environment variables       |
| `uname -a`         | Show system information          |

### Permissions

| Command            | Description                      |
|--------------------|--------------------------------|
| `chown user:staff file` | Change ownership             |

### Fun/Surprise Commands

| Command            | Description                      |
|--------------------|--------------------------------|
| `yes "macOS"`      | Repeat string until stopped (Ctrl+C) |

---

## Level 4 — Advanced

### Navigation

| Command            | Description                      |
|--------------------|--------------------------------|
| `alias ..="cd .."` | Shortcut for going up            |
| `dirs`             | List directory stack             |

### File Management

| Command            | Description                      |
|--------------------|--------------------------------|
| `tar -czf archive.tgz folder/` | Create compressed archive |
| `unzip file.zip`   | Unzip archive                   |

### Viewing/Editing Files

| Command            | Description                      |
|--------------------|--------------------------------|
| `sed 's/foo/bar/g' file.txt` | Replace text in file       |
| `awk '{print $1}' file.txt` | Print first column         |

### Searching

| Command            | Description                      |
|--------------------|--------------------------------|
| `grep -i "text" file.txt` | Case-insensitive search     |
| `grep -v "skip" file.txt` | Exclude lines              |

### System Info

| Command            | Description                      |
|--------------------|--------------------------------|
| `ps aux`           | List all processes              |
| `kill -9 PID`      | Force-kill a process            |

### Permissions

| Command            | Description                      |
|--------------------|--------------------------------|
| `chmod -R 755 folder/` | Recursive permission change   |

### Fun/Surprise Commands

| Command            | Description                      |
|--------------------|--------------------------------|
| `cowsay "Use the terminal"` | ASCII cow speech (requires cowsay installed) |

---

## Level 5 — Pro

### Navigation

| Command            | Description                      |
|--------------------|--------------------------------|
| `for d in */; do echo "$d"; done` | List subdirectories using loop |

### File Management

| Command            | Description                      |
|--------------------|--------------------------------|
| `rsync -av folder/ backup/` | Sync folders efficiently  |
| `ln -s target link` | Create symbolic link             |

### Viewing/Editing Files

| Command            | Description                      |
|--------------------|--------------------------------|
| `tail -f log.txt`  | Follow live updates to a log file |
| `vim file.txt`     | Open file in vim editor          |

### Searching

| Command            | Description                      |
|--------------------|--------------------------------|
| `grep -E "foo|bar" file.txt` | Extended regex search     |

### System Info

| Command            | Description                      |
|--------------------|--------------------------------|
| `system_profiler SPHardwareDataType` | Detailed system hardware info |

### Permissions

| Command            | Description                      |
|--------------------|--------------------------------|
| `sudo chmod 000 file.txt` | Deny all access             |

### Fun/Surprise Commands

| Command            | Description                      |
|--------------------|--------------------------------|
| `telnet towel.blinkenlights.nl` | Watch Star Wars in ASCII  |

---

```sh
# End of file. Keep practicing and use man pages for full command details:
man [command]         # Get help for any command
