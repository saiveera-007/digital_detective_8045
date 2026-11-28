# 1. Mission 4 - ***How program run***

## 2. Task/Objective 

Run a simple Python program and compare how compilers and interpreters translate or execute programs.

## 3. Work Completed 

### Task 4.1 — Create and run a Python program

I created `hello.py` with a line of Python code that displays a message. I ran it in Terminal with `python3 mission-04-programs/hello.py`, and it displayed `Hello from Python`.

### Task 4.2 — Compare a compiler and an interpreter.

| **Point** | **Compiler** | **Interpreter** |
|---|---|---|
| ***When it works*** | Translates the program before it runs. | **Reads and executes program instructions while it runs.** |
| ***Typical output*** | Often creates a separate executable or object file. | **Often runs through the interpreter without creating a separate executable.** |
| ***Example*** | C | **Python** |
| ***One advantage*** | The translated program can run quickly. | **It’s convenient to run and test code while developing.** |

A compiler usually translates a program before it runs, often creating another file. An interpreter reads and carries out instructions while a program runs. C is commonly used as a compiler example, while Python is commonly used as an interpreter example. Real language implementations can combine both approaches.

## 4. Commands / tools used

- VS Code — used to create and edit the files.
- `python3 mission-04-programs/hello.py` — ran the Python program.

## 5. My understanding

A compiler usually translates a program before it runs. An interpreter carries out instructions while the program runs. The two approaches can have different advantages, and real language implementations may combine them.

## 6. Difficulties faced

At first, I used the wrong filename and the file contained plain text instead of Python code, so running it displayed no message.

## 7. How I resolved them

I renamed the file to `hello.py`, added the `print` instruction, saved it, and ran it again.

## 8. Evidence / files

- `mission-04-programs/README.md`
- `mission-04-programs/hello.py`

## 9. Commit details

Commit message: Run Python and compare compilers and interpreters.