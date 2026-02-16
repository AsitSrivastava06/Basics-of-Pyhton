# ==============================================================
#                     PRACTICAL – 7 
#         Control Structures & Logical Programming in Python
# ==============================================================


"""
----------------------------------------------------------------
1. AIM
----------------------------------------------------------------
To study and implement the following concepts in Python:

• While loop and control statements
• For loop and range function
• Nested loops
• Matrix display and matrix multiplication
• Armstrong number program
• Prime number generation
• Pattern printing techniques
"""


"""
----------------------------------------------------------------
2. THEORY
----------------------------------------------------------------

2.1 WHILE LOOP
--------------
A while loop repeatedly executes a block of statements as long 
as the given condition evaluates to True.

General Working:
1. Initialize control variable
2. Check condition
3. Execute statements
4. Update control variable

Control Statement:
• continue → Skips the current iteration and moves to the next.


2.2 FOR LOOP
------------
A for loop is used for iterating over a sequence of values.

General Syntax Concept:
for variable in range(start, stop, step)

• range() generates numeric sequences.
• The stop value is excluded.


2.3 NESTED LOOPS
----------------
A nested loop is a loop inside another loop.

Applications:
• Matrix operations
• Pattern printing
• Combinational logic

Rule:
Outer loop  → Controls rows
Inner loop  → Controls columns


2.4 MATRIX THEORY
-----------------
A matrix is represented as a 2D list in Python.

Matrix Multiplication Rule:

If A is of order (m × n)
and B is of order (n × p),

Then Result will be of order (m × p)

Mathematical Formula:

Result[i][j] = Σ A[i][k] × B[k][j]

Where:
i → Row index
j → Column index
k → Summation index


2.5 ARMSTRONG NUMBER
--------------------
A number is called an Armstrong number if:

Sum of (each digit)^(number of digits)
= Original number

Example Concept:
153 = 1³ + 5³ + 3³


2.6 PRIME NUMBER
----------------
A prime number has exactly two factors:
1 and the number itself.

Logic:
• Check divisibility from 2 to n-1.
• If divisible → Not Prime.
• Otherwise → Prime.


2.7 PATTERN PRINTING
--------------------
Pattern printing uses nested loops.

Outer loop → Controls number of rows
Inner loop → Controls symbols per row

Patterns included:
• Pyramid
• Inverted Pyramid
• Floyd’s Triangle
• Right Angle Triangle
• Inverted Right Angle Triangle
"""


"""
----------------------------------------------------------------
3. ALGORITHMS
----------------------------------------------------------------

3.1 Printing Numbers Using While Loop
-------------------------------------
1. Initialize counter.
2. Check loop condition.
3. If value equals skipped number → continue.
4. Print value.
5. Increment counter.


3.2 Printing Even / Odd Numbers
-------------------------------
1. Use range() with appropriate step value.
2. Iterate through sequence.
3. Print required numbers.


3.3 Sum of First N Numbers
--------------------------
1. Input integer n.
2. Initialize sum = 0.
3. Loop from 1 to n.
4. Add each number to sum.
5. Display final sum.


3.4 Matrix Display
------------------
1. Store matrix in 2D list.
2. Use nested loops.
3. Print element at index [i][j].


3.5 Matrix Multiplication
-------------------------
1. Initialize result matrix with zeros.
2. Use three nested loops.
3. Multiply corresponding elements.
4. Accumulate values.
5. Display result matrix.


3.6 Armstrong Number
--------------------
1. Input number.
2. Determine number of digits.
3. Initialize total = 0.
4. Extract each digit.
5. Raise digit to power of digit count.
6. Add to total.
7. Compare total with original number.


3.7 Prime Numbers in Range
--------------------------
1. Start from 2.
2. For each number:
   a) Check divisibility.
   b) If divisible → break.
   c) Else → print as prime.


3.8 Pattern Printing
--------------------
1. Define number of rows.
2. Use outer loop for rows.
3. Use inner loop for symbols.
4. Print formatted output.
"""


"""
----------------------------------------------------------------
4. FLOWCHART DESCRIPTION
----------------------------------------------------------------

4.1 WHILE LOOP FLOW
--------------------
Start
 ↓
Initialize variable
 ↓
Check condition
 ↓
If True → Execute statements → Update variable → Repeat
If False → End


4.2 MATRIX MULTIPLICATION FLOW
-------------------------------
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
Display Result
 ↓
End


4.3 ARMSTRONG NUMBER FLOW
--------------------------
Start
 ↓
Input number
 ↓
Count digits
 ↓
Initialize total = 0
 ↓
For each digit
   Raise to power
   Add to total
 ↓
Compare total with original number
 ↓
If equal → Armstrong
Else → Not Armstrong
 ↓
End


4.4 PRIME NUMBER FLOW
----------------------
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
----------------------------------------------------------------
5. LEARNING OUTCOMES
----------------------------------------------------------------
After completing this practical, the student will be able to:

• Understand and implement loop structures
• Work with nested loops effectively
• Perform matrix operations
• Solve number-based logical problems
• Design structured pattern programs
• Develop algorithmic thinking skills
"""


"""
----------------------------------------------------------------
6. CONCLUSION
----------------------------------------------------------------
This practical strengthens foundational programming concepts 
including loops, matrices, number logic, and structured 
pattern generation.

These concepts form the basis for advanced programming,
data structures, and algorithm development.
----------------------------------------------------------------


