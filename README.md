# Logic Box – Pattern Generator and Number Analyzer

## Description
A Python console application that generates a right-angled triangle pattern and analyzes a range of numbers (odd/even and sum). Demonstrates control structures, loops, `range()`, and control statements (`break`, `continue`, `pass`).

## Features
- Menu-driven interface.
- Pattern generation using nested loops.
- Number analysis with odd/even check and sum.
- Input validation and error handling.
- Use of `break`, `continue`, and `pass`.

## Assumptions
- Triangle pattern uses `*` characters.
- Range analysis includes both start and end.
- Invalid inputs return to the main menu.

## How to Run
1. Ensure Python 3.x is installed.
2. Clone the repository.
3. Run: `python logic_box.py`

## Sample Output
============================================================
Welcome to the Pattern Generator and Number Analyzer!
============================================================
This program can generate a right-angled triangle pattern
and analyze a range of numbers (odd/even and sum).

==================================================
Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit
==================================================
Enter your choice: 1

--- Pattern Generator ---
Enter the number of rows for the pattern: 5

Pattern:
*
**
***
****
*****

==================================================
Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit
==================================================
Enter your choice: 2

--- Number Analyzer ---
Enter the start of the range: 10
Enter the end of the range: 15

Number 10 is Even
Number 11 is Odd
Number 12 is Even
Number 13 is Odd
  (Skipping 13 as a demonstration of continue)
Number 14 is Even
Number 15 is Odd

Sum of all numbers from 10 to 15 is: 75

==================================================
Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit
==================================================
Enter your choice: 3

Exiting the program. Goodbye!
Thank you for using the Pattern Generator and Number Analyzer.

## Author
Rahi Sarvaiya
