# 1. Mission 2 — ***Become comfortable with the Terminal***

## 2. Task / objective

Practise Terminal commands for navigating folders and managing files. Learn how command options and pipes work, and understand what a package manager does.

## 3. Work completed

I created a `terminal-practice` folder in my assignment repository. Inside it, I created `original.txt`, added two lines, copied it, and renamed the copy. I also compared directory listings, tried a pipe, and checked Homebrew.

| **Operation** | **Command used** | **What it does / what I observed** |
|---|---|---|
| ***Show current folder*** | `pwd` | **Displays the full path of my current folder.** |
| ***List files and folders*** | `ls` | **Shows the names in the current folder.** |
| ***Show a detailed listing*** | `ls -l` | **Shows names plus details such as permissions, size, and date.** |
| ***Move to parent folder*** | `cd ..` | **Moves up one folder; `pwd` showed the changed location.** |
| ***Create a practice folder*** | `mkdir terminal-practice` | **Creates a new folder in the current location.** |
| ***Create an empty file*** | `touch original.txt` | **Creates an empty text file.** |
| ***Add text to a file*** | `echo "This is my practice file." > original.txt` and `echo "This is my second line" >> original.txt` | **`>` writes the first line; `>>` adds another line at the end.** |
| ***Copy a file*** | `cp original.txt backup.txt` | **Creates a separate copy and leaves the original in place.** |
| ***Rename the copy*** | `mv backup.txt renamed-backup.txt` | **Renames the copy because both names are in the same folder.** |
| ***Display file contents*** | `cat original.txt` | **Shows the two lines in the file.** |

## 4. Commands / tools used

- `ls -lah` — displayed a detailed listing, including hidden entries, with readable file sizes.
- `ls -lah | head -n 5` — sent the listing through a pipe to show only its first five lines.
- `brew --version` — checked the Homebrew version, 7.0.12.
- `brew list` — displayed Homebrew’s installed Formulae and Casks.
- VS Code — used to write this README.

## 5. My understanding

The `>` symbol replaces a file’s contents, while `>>` adds text at the end. `cp` makes a separate copy; `mv` can move a file or rename it. `pwd` shows where I am, and `ls` shows what is in a folder. Options such as `-l`, `-a`, and `-h` change how `ls` displays information. The pipe symbol `|` sends one command’s output to another command. A package manager such as Homebrew helps manage software from one place.

## 6. Difficulties faced

At first, I was unsure what command options and the pipe symbol did.

## 7. How I resolved them

I learned what each part of the commands meant, then ran them and observed the results. I used a practice folder so my file exercises stayed inside the assignment repository.

## 8. Evidence / files

- `mission-02-terminal/README.md`
- `terminal-practice/original.txt`
- `terminal-practice/renamed-backup.txt`

## 9. Commit details

Commit message: Complete Terminal and file management mission.  
Pushed to GitHub.