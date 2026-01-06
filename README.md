   `Here is a ready-to-use README.md for your cgpa_calculator.cpp file.
​
​

text
# CGPA Calculator (C++)

A simple **console** application in C++ that calculates a student's Cumulative Grade Point Average (CGPA) based on subject grades and their corresponding credits. 

## Features

- Accepts the number of subjects from the user.
- Takes grade and credit for each subject as input.
- Calculates total grade points and total credits.
- Computes and displays the final CGPA.
- Prints each subject’s grade and credit details along with a final congratulatory message.

## How It Works

1. The program asks for the number of subjects.  
2. For each subject:
   - User enters the grade (as a numeric value, e.g., 8.5).  
   - User enters the credit for that subject (e.g., 3 or 4).  
3. The program multiplies grade × credit for each subject and sums them up.  
4. CGPA is calculated as:  
   text{CGPA} = {Total Grade Point}{Total Credits}
 
5. The program displays the CGPA and a congratulatory message.

## Requirements

- C++ compiler supporting basic STL (e.g., `g++`, `clang++`).
- Standard Template Library `vector` header (used in the program).

## Compilation and Execution

Using `g++` from the terminal:

```bash
g++ cgpa_calculator.cpp -o cgpa_calculator
./cgpa_calculator
