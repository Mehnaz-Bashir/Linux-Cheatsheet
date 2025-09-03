# 🐧 Linux Cheatsheet for Beginners

## 1. Unix vs Linux
- **Unix**: Proprietary OS developed in the 1970s, mainly used in servers and mainframes.
- **Linux**: Open-source Unix-like OS, widely used on servers, desktops, and embedded systems.

---

## 2. CLI vs GUI
- **CLI (Command Line Interface):** Text-based, powerful, faster for system tasks.
- **GUI (Graphical User Interface):** User-friendly, mouse-based, easier for beginners.

---

## 3. File Paths
- **Absolute Path:** Starts from root (`/`). Example: `/home/user/Documents/file.txt`
- **Relative Path:** Starts from current directory. Example: `Documents/file.txt`

📂 **Linux Directory Tree (simplified):**

<pre> /
├── bin       (essential commands)
├── boot      (boot loader files)
├── dev       (device files)
├── etc       (config files)
├── home      (user directories)
│   └── user  (your files)
├── lib       (libraries)
├── tmp       (temporary files)
├── usr       (applications, binaries)
└── var       (logs, cache)</pre>


---

## 4. Users in Linux
- **Regular User:** Limited permissions, home directory (`/home/username`).
- **Root (Superuser):** Admin, full permissions. Denoted by `#`.
- **Service Users:** Created by the system for running services (e.g., `www-data`, `mysql`).

---

## 5. File & Directory Commands
- `ls` → List directory contents.  
- `ls -a` → Show hidden files.  
- `ls -l` → Detailed listing.  
- `ls -lart` → List all, sorted by time.  
- `ls -R` → Recursive list.  

- `pwd` → Print working directory.  
- `cd <dir>` → Change directory.  
- `cd /` → Go to root.  
- `cd ..` → Move up one directory.  
- `cd Downloads` → Enter `Downloads` folder.  

- `mkdir myfolder` → Create a directory.  
- `cd myfolder` → Move into that directory.  

- `touch file.txt` → Create empty file.  
- `touch .hiddenfile` → Create hidden file.  

- `cp file.txt backup/` → Copy file.  
- `mv file.txt myfolder/` → Move file.  
- `rm file.txt` → Delete file.  
- `rm -r foldername` → Delete folder.  

---

## 6. File Viewing & Editing
- `cat file.txt` → View file.  
- `less file.txt` → Scroll content.  
- `head file.txt` → First 10 lines.  
- `tail file.txt` → Last 10 lines.  
- `nano file.txt` → Simple editor.  
- `vim file.txt` → Advanced editor.  

📝 **Vim Basics**:  
- Press `i` → Insert mode.  
- Press `Esc` → Exit insert mode.  
- Type `:wq` → Save & quit.  

---

## 7. System Update & Permissions
- `sudo apt-get update` → Update package lists.  
- `sudo apt-get upgrade` → Upgrade installed packages.  

- `chmod 582 file.txt` → Change permissions.  
- `ls -l` → Check permissions.  

🔑 **File Permission Representation:**

<pre> -rwxr-xr--
│ │ │ │
│ │ │ └── Others
│ │ └──── Group
│ └────── Owner
└──────── File type (- file, d directory)
 </pre>
---

## 8. System Monitoring & Processes
- `top` → Show running processes.  
- `ps` → Show current shell processes.  
- `ps -a` → Show all user processes.  
- `ps -ef` → Show all system processes.  
- `kill <PID>` → Kill process with given ID.  

---

## 9. Other Useful Commands
- `clear` → Clear the terminal.  
- `history` → Show command history.  
- `echo "Hello World"` → Print text.  
- `printf "Linux Cheatsheet\n"` → Print formatted text.  
- **Case Sensitivity:** `FILE.txt` ≠ `File.txt`.  

---

✅ **Learning Flow**  
1. Navigate (`pwd`, `cd`, `ls`)  
2. Create files/folders (`mkdir`, `touch`)  
3. Manage files (`cp`, `mv`, `rm`)  
4. View/edit (`cat`, `nano`, `vim`)  
5. System operations (`sudo`, `chmod`)  
6. Monitor processes (`top`, `ps`, `kill`)  
7. Miscellaneous (`clear`, `history`, `echo`)  

---

