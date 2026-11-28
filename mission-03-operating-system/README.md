# 1. Mission 3 - ***Understand the operating system***

## 2. Task/Objective 

Explore how the operating system manages processes, storage, files, paths, and permissions, and explain its main responsibilities.

## 3. Work Completed

### Task 3.1 — ***System observations***

| **Information explored** | **What it tells me** | **My privacy-safe observation** |
|---|---|---|
| ***Operating system*** | Which operating system my computer uses. | **My computer runs macOS, version 27.2.1.** |
| ***Current account*** | Which account is active in Terminal. | **The command showed my account name; I redacted it.** |
| ***Storage*** | How much space is used and available. | **The main data volume showed about 926 GiB total, 107 GiB used, and 793 GiB available.** |
| ***System activity*** | A snapshot of processes and system use. | **At the time of my snapshot, 680 processes were listed: 4 running and 676 sleeping.** |

### Task 3.2 — ***Processes***

A process is a program that is currently running. The PID is the number the operating system uses to identify a process; it can change when the process runs again. In my snapshot, I saw background processes named `mdworker_shared` and `com.apple.iCloud`.

### Task 3.3 — ***Paths and permissions***

An absolute path starts from the root of the computer and gives the full location. A relative path starts from the current folder. My absolute-path example is `/Users/[redacted]/Desktop/digital_detective_8045/mission-02-terminal`. From the project folder, the relative path to that mission folder is `mission-02-terminal`.

The detailed listing for `original.txt` began with `-rw-r--r--@`. The owner’s permission letters are `rw-`, which means the owner can read and write the file but cannot execute it. I did not change any permissions.

| **Permission** | **Meaning** | **Example** |
|---|---|---|
| ***`r` — Read*** | Allows a file’s contents to be read. | **Opening a text file.** |
| ***`w` — Write*** | Allows a file to be changed. | **Editing a text file.** |
| ***`x` — Execute*** | Allows a file to be run; on a folder, allows access to it. | **Running a script.** |

### Task 3.4 — ***Operating-system responsibilities***

| **Responsibility** | **What it means** | **Example** |
|---|---|---|
| ***Process management*** | The OS manages programs while they are running. | **It lets a browser and Terminal run at the same time.** |
| ***Memory management*** | The OS gives programs memory to use and keeps track of it. | **An open app uses some of the computer’s RAM.** |
| ***Device management*** | The OS helps software communicate with hardware. | **It sends keyboard input to the computer.** |
| ***File management*** | The OS organizes files and folders and helps save and open them. | **It lets me save and reopen my README.** |
| ***User interface / shell*** | The OS provides ways for people to interact with the computer. | **I use the desktop or Terminal to give it instructions.** |
| ***Security and permissions*** | The OS controls who can access or change files. | **File permissions can allow reading or writing.** |

## 4. Commands / tools used

- `sw_vers` — checked the macOS version.
- `whoami` — checked which account was active; I redacted the username.
- `df -h` — checked used and available storage.
- `top -l 1` — took a snapshot of system activity.
- `top -l 1 -n 5` — displayed process information, including PIDs.
- `pwd` and `cd` — checked and changed the current folder.
- `ls -l` — checked file details and permissions.

## 5. My understanding

A process is a program that is running, and its PID is the number used to identify it. The operating system manages memory, files, devices, and running programs. An absolute path gives the full location, while a relative path starts from the current folder. File permissions show whether a user can read, write, or execute a file.

## 6. Difficulties faced

At first, I found it difficult to understand paths, process information, and the permission letters.

## 7. How I resolved them

I checked the command output and got help understanding what the path and permission symbols meant. I replaced my account name with `[redacted]` in my public notes.

## 8. Evidence / files

- `mission-03-operating-system/README.md`
- `terminal-practice/original.txt` — file whose permissions I inspected

## 9. Commit details

- `4b51521 (HEAD -> main, origin/main) Added table for 3.3 task`
- `276e12f Added task 3.3 processes`
- `666557e adding table 3.1 and tile for the readme`
- `eb1468e Correct the style of the tile again`
- `be98408 Correct the style of the tile`
- `9c96ee4 Completing the table of mission3`
- `4ce3e66 Correcting the readme table`
- `d616cf9 Complete Terminal and file management mission`
- `d4c37bc Final time changing this readme hopefully`
- `be5a3da Updating readme.md file 2nd time`
- `02542d8 Updating the mission 1 readme.md file`