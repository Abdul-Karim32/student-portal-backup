Student Marks Program - Clean Code Version

Assignment Goal
Refactor a messy student grading program into clean, readable, and maintainable C code using "Clean Code Principles" and manage the changes using "Git version control".

# Clean Code Improvements
The following improvements were made step-by-step:

1. **Original Messy Code Added**
   - Poor formatting, bad variable names, and no modularity.
   
2. **Refactored Structure and Indentation**
   - Proper indentation and spacing for readability.
   
3. **Renamed Variables**
   - Used meaningful names (e.g., `a` → `marks`, `i` → `studentIndex`).

4. **Modularized Code**
   - Extracted logic into functions:
     - `calculateAverage()`
     - `calculateTotal()`
     - `getGrade()`

5. **Added Comments and Formatting**
   - Descriptive comments for functions and logic
   - Clean output formatting with labels and spacial

# Files Included

- `Abc.c` — Final refactored C code
- `README.md` — This file
- `git-log.txt` — Git history output (see below)

# How to Compile and Run

bash
gcc Abc.c -o student_grades
./student_grades

