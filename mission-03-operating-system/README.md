# Mission 3 - ***Understand the operating system***

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