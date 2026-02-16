# ╔══════════════════════════════════════════════════════════════╗
# ║                    🧪 PRACTICAL – 7 LAB MANUAL              ║
# ║        Control Structures & Logical Programming in Python   ║
# ╚══════════════════════════════════════════════════════════════╝


"""
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🎯 AIM
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
To study and implement:

✔ While loop and control statements
✔ For loop and range function
✔ Nested loops
✔ Matrix display and multiplication
✔ Armstrong number program
✔ Prime numbers in range
✔ Pattern printing (Pyramid, Floyd’s Triangle, etc.)
"""


"""
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📚 THEORY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1️⃣ WHILE LOOP
──────────────────────────────────────────────────────────────────
A while loop executes a block of code repeatedly as long as 
the given condition remains TRUE.

Concept:
• Initialize variable
• Check condition
• Execute statements
• Update variable

Control Statement:
→ continue : Skips current iteration and moves to next iteration.


2️⃣ FOR LOOP
──────────────────────────────────────────────────────────────────
A for loop is used for iterating over a sequence of values.

Concept:
for variable in range(start, stop, step)

• range() generates numbers
• Stop value is excluded


3️⃣ NESTED LOOPS
──────────────────────────────────────────────────────────────────
A loop inside another loop.

Used for:
• Matrix operations
• Pattern printing
• Combinations
• Tables

Rule:
Outer loop → Controls rows
Inner loop → Controls columns


4️⃣ MATRIX THEORY
──────────────────────────────────────────────────────────────────
Matrix is represented as a 2D list.

If A is (m × n)
and B is (n × p)
Then Result is (m × p)

Matrix Multiplication Formula:

Result[i][j] = Σ A[i][k] × B[k][j]

Where:
i → row index
j → column index
k → summation index


5️⃣ ARMSTRONG NUMBER
──────────────────────────────────────────────────────────────────
A number is Armstrong if:

Sum of (each digit) ^ (number of digits)
= Original number

Example Concept:
153 = 1³ + 5³ + 3³


6️⃣ PRIME NUMBER
──────────────────────────────────────────────────────────────────
A prime number:
• Has exactly two factors (1 and itself)

Logic:
• Check divisibility from 2 to n-1
• If divisible → Not Prime
• Else → Prime


7️⃣ PATTERN PRINTING
──────────────────────────────────────────────────────────────────
Uses nested loops.

Outer loop → Controls rows
Inner loop → Controls symbols

Patterns Covered:
• Pyramid
• Inverted Pyramid
• Floyd’s Triangle
• Right Angle Triangle
• Inverted Right Angle Triangle
"""


"""
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📝 ALGORITHMS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

A) PRINT NUMBERS USING WHILE LOOP (SKIP VALUE)
──────────────────────────────────────────────
1. Initialize counter
2. Start loop
3. If value equals skipped number → continue
4. Print value
5. Increment counter


B) PRINT EVEN / ODD NUMBERS
──────────────────────────────────────────────
1. Use range()
2. Set correct step value
3. Print each number


C) SUM OF FIRST N NUMBERS
──────────────────────────────────────────────
1. Input integer n
2. Initialize sum = 0
3. Loop from 1 to n
4. Add each value to sum
5. Display sum


D) MATRIX DISPLAY
──────────────────────────────────────────────
1. Store matrix in 2D list
2. Use two nested loops
3. Print element at index [i][j]


E) MATRIX MULTIPLICATION
──────────────────────────────────────────────
1. Initialize result matrix with zeros
2. Use three nested loops
3. Multiply row elements with column elements
4. Store accumulated result
5. Display result matrix


F) ARMSTRONG NUMBER
──────────────────────────────────────────────
1. Input number
2. Count digits
3. Initialize total = 0
4. Extract each digit
5. Raise digit to power of digit count
6. Add to total
7. Compare with original number


G) PRIME NUMBERS IN RANGE
──────────────────────────────────────────────
1. Start from 2
2. For each number:
   • Check divisibility
   • If divisible → break
   • Else → print as prime


H) PATTERN PRINTING
──────────────────────────────────────────────
1. Decide number of rows
2. Outer loop → rows
3. Inner loop → symbols
4. Print pattern
"""


"""
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🔄 FLOWCHART LOGIC
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🔹 WHILE LOOP FLOW
──────────────────────────────────────────────
Start
 ↓
Initialize variable
 ↓
Check condition
 ↓
True? → Execute → Update → Repeat
False? → End


🔹 MATRIX MULTIPLICATION FLOW
──────────────────────────────────────────────
Start
 ↓
Initialize Result matrix
 ↓
For each row (i)
   ↓
   For each column (j)
      ↓
      For each k
         Multiply A[i][k] × B[k][j]
         Add to Result[i][j]
 ↓
Print Result
 ↓
End


🔹 ARMSTRONG NUMBER FLOW
──────────────────────────────────────────────
Start
 ↓
Input number
 ↓
Find number of digits
 ↓
Initialize total = 0
 ↓
For each digit:
   Raise to power
   Add to total
 ↓
Compare with original number
 ↓
If equal → Armstrong
Else → Not Armstrong
 ↓
End


🔹 PRIME NUMBER FLOW
──────────────────────────────────────────────
Start
 ↓
Select number
 ↓
Check divisibility
 ↓
If divisible → Not Prime
Else → Prime
 ↓
End
"""


"""
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🎓 LEARNING OUTCOMES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

After completing this practical, the student will be able to:

✔ Understand loop control structures
✔ Implement nested loops efficiently
✔ Perform matrix operations
✔ Solve number-based logical problems
✔ Generate pattern programs
✔ Improve algorithmic thinking


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📌 CONCLUSION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

This practical covers fundamental programming concepts 
including loops, matrices, number logic, and pattern generation.

These concepts build a strong foundation for advanced 
programming and algorithm development.

══════════════════════════════════════════════════════════════════
                    END OF LAB MANUAL
══════════════════════════════════════════════════════════════════
"""
