# 1. Mission 5 - ***Numbers and Data***

## 2. Task/Objective

Convert decimal, binary and hexadecimal values, verify results with Python, build a small converter
and explain text encoding.

## 3. Work Completed 

### Task 5.1 — Convert numbers by hand

**Convert decimal 13 to binary**

13 ÷ 2 = 6 [remainder 1]  
6 ÷ 2 = 3 [remainder 0]  
3 ÷ 2 = 1 [remainder 1]  
1 ÷ 2 = 0 [remainder 1]  

`Read the remainders from bottom to top`: **13₁₀ = 1101₂**.

**Convert decimal 25 to binary**

25 ÷ 2 = 12 [remainder 1]  
12 ÷ 2 = 6 [remainder 0]  
6 ÷ 2 = 3 [remainder 0]  
3 ÷ 2 = 1 [remainder 1]  
1 ÷ 2 = 0 [remainder 1]  

`Read the remainders from bottom to top`: **25₁₀ = 11001₂**.

**Convert binary 1010 to decimal**

1 × 8 + 0 × 4 + 1 × 2 + 0 × 1 = 8 + 2 = **10**.

**Convert binary 1101 to decimal**

1 × 8 + 1 × 4 + 0 × 2 + 1 × 1 = 8 + 4 + 1 = **13**.

**Convert hexadecimal A to decimal**

A represents 10 in hexadecimal, so **A₁₆ = 10₁₀**.

**Convert hexadecimal 1F to decimal**

F represents 15.  
1 × 16 + 15 × 1 = 16 + 15 = **31**.

**Convert binary 1111 to hexadecimal**

1111₂ = 8 + 4 + 2 + 1 = 15₁₀.  
15 is F in hexadecimal, so **1111₂ = F₁₆**.

### Task 5.2 — Verify using Python

| **Expression** | **Python result** | **Matches my manual answer?** |
|---|---|---|
| ***`bin(13)`*** | `0b1101` | **Yes** |
| ***`bin(25)`*** | `0b11001` | **Yes** |
| ***`int("1010", 2)`*** | `10` | **Yes** |
| ***`int("1101", 2)`*** | `13` | **Yes** |
| ***`hex(10)`*** | `0xa` | **Yes** |
| ***`hex(31)`*** | `0x1f` | **Yes** |
| ***`int("A", 16)`*** | `10` | **Yes** |
| ***`int("1F", 16)`*** | `31` | **Yes** |
| ***`hex(int("1111", 2))`*** | `0xf` | **Yes** |

### Task 5.3 — Number converter tests

| **Decimal input** | **Binary output** | **Hexadecimal output** |
|---:|---|---|
| ***207*** | `0b11001111` | **`0xcf`** |
| ***13*** | `0b1101` | **`0xd`** |
| ***25*** | `0b11001` | **`0x19`** |

The program uses `input()` to get the number, `int()` to convert the typed text into an integer, `bin()` to make the binary form, and `hex()` to make the hexadecimal form. Python adds `0b` and `0x` to label the output bases.

### Task 5.4 — How is text stored?

- ASCII decimal code for uppercase `A`: 65
- ASCII decimal code for lowercase `a`: 97
- Computers need an encoding standard to represent text as numbers, so they can store and interpret characters consistently.
- An example of a character outside basic ASCII is `₹`.

 ## 4. Commands / tools used

- `python3` — opened Python’s interactive environment.
- `bin()` — converted decimal integers to binary.
- `int()` — converted binary and hexadecimal text to decimal integers.
- `hex()` — converted integers to hexadecimal.
- `python3 mission-05-numbers-data/number_converter.py` — ran the number converter.
- VS Code — used to edit the README and Python file.

## 5. My understanding

Binary represents numbers using 0 and 1, while hexadecimal uses sixteen symbols, including A to F. Python’s built-in functions helped me check my conversions. Text-encoding standards let computers represent characters as numbers.

## 6. Difficulties faced

Calculating the values and conversion took a lot of time , and how places got stuck and not able understand we did I go wrong . 

## 7. How I resolved them

Trying again and agian , also you AI for learning and debugging my mistakes .

## 8. Evidence / files

- `mission-05-numbers-data/README.md`
- `mission-05-numbers-data/number_converter.py`
- The three converter test results recorded above.

## 9. Commit details

Commit message: Build number converter and practise data representation.