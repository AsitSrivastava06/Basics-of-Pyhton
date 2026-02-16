# 🧪 EXPERIMENT – 6  
# STUDY OF CONDITIONAL STATEMENTS IN PYTHON  

**Name:** Asit Kumar Srivastava  
**PRN:** 25070123026  
**Batch:** A2  

------------------------------------------------------------

# 🎯 AIM

To study and implement conditional (decision-making) statements in Python and apply them to solve logical and real-world problems.

------------------------------------------------------------

# 🎓 OBJECTIVES

• To understand the concept of decision making in programming  
• To learn different types of conditional statements in Python  
• To apply relational and logical operators in programs  
• To develop problem-solving skills using control flow  

------------------------------------------------------------

# 📚 THEORY

## 🔹 Introduction

In programming, decision-making allows execution of specific blocks of code based on certain conditions.  
Python provides conditional statements to control the flow of execution.

These statements evaluate Boolean expressions (True or False) and execute code accordingly.

------------------------------------------------------------

## 🔹 Types of Conditional Statements in Python

### 1️⃣ if Statement

Used to execute a block only when a condition is True.

Syntax:

if condition:
    statement

------------------------------------------------------------

### 2️⃣ if-else Statement

Used when two possible outcomes exist.

Syntax:

if condition:
    statement1
else:
    statement2

------------------------------------------------------------

### 3️⃣ if-elif-else Ladder

Used when multiple conditions are checked sequentially.

Syntax:

if condition1:
    statement1
elif condition2:
    statement2
else:
    statement3

------------------------------------------------------------

### 4️⃣ Nested if Statement

An if statement inside another if statement.

Syntax:

if condition1:
    if condition2:
        statement

------------------------------------------------------------

## 🔹 Operators Used

Relational Operators:
>   Greater than  
<   Less than  
>=  Greater than or equal to  
<=  Less than or equal to  
==  Equal to  
!=  Not equal to  

Logical Operators:
and  Returns True if both conditions are True  
or   Returns True if at least one condition is True  
not  Reverses the logical result  

------------------------------------------------------------

# 📘 FLOWCHART DESCRIPTIONS

------------------------------------------------------------
## 1️⃣ POSITIVE / NEGATIVE CHECK

START  
↓  
INPUT number  
↓  
Is number > 0 ?  
→ YES → PRINT "Positive"  
→ NO  → PRINT "Negative"  
↓  
END  

------------------------------------------------------------
## 2️⃣ POSITIVE / NEGATIVE / ZERO

START  
↓  
INPUT number  
↓  
Is number > 0 ?  
→ YES → PRINT "Positive"  
→ NO  
      ↓  
      Is number < 0 ?  
      → YES → PRINT "Negative"  
      → NO  → PRINT "Zero"  
↓  
END  

------------------------------------------------------------
## 3️⃣ EVEN / ODD CHECK

START  
↓  
INPUT number  
↓  
Is number % 2 == 0 ?  
→ YES → PRINT "Even"  
→ NO  → PRINT "Odd"  
↓  
END  

------------------------------------------------------------
## 4️⃣ LARGEST OF TWO NUMBERS

START  
↓  
INPUT num1, num2  
↓  
Is num1 > num2 ?  
→ YES → PRINT num1  
→ NO  → PRINT num2  
↓  
END  

------------------------------------------------------------
## 5️⃣ LARGEST AMONG THREE NUMBERS

START  
↓  
INPUT num1, num2, num3  
↓  
Is num1 ≥ num2 AND num1 ≥ num3 ?  
→ YES → PRINT num1  
→ NO  
      ↓  
      Is num2 ≥ num1 AND num2 ≥ num3 ?  
      → YES → PRINT num2  
      → NO  → PRINT num3  
↓  
END  

------------------------------------------------------------
## 6️⃣ GRADE CALCULATION

START  
↓  
INPUT marks of 5 subjects  
↓  
CALCULATE average  
↓  
Is average > 90 ?  
→ YES → PRINT "Grade O"  
→ NO  
      ↓  
      Is average > 80 ?  
      → YES → PRINT "Grade A+"  
      → NO  
            ↓  
            Is average > 70 ?  
            → YES → PRINT "Grade A"  
            → NO  
                  ↓  
                  Is average > 60 ?  
                  → YES → PRINT "Grade B+"  
                  → NO  
                        ↓  
                        Is average > 50 ?  
                        → YES → PRINT "Grade B"  
                        → NO  
                              ↓  
                              Is average > 30 ?  
                              → YES → PRINT "Pass"  
                              → NO  → PRINT "Fail"  
↓  
END  

------------------------------------------------------------
## 7️⃣ LEAP YEAR CHECK

START  
↓  
INPUT year  
↓  
Is year % 400 == 0 ?  
→ YES → PRINT "Leap Year"  
→ NO  
      ↓  
      Is year % 4 == 0 AND year % 100 != 0 ?  
      → YES → PRINT "Leap Year"  
      → NO  → PRINT "Not Leap Year"  
↓  
END  

------------------------------------------------------------
## 8️⃣ DATE VALIDATION & INCREMENT

START  
↓  
INPUT date (dd/mm/yyyy)  
↓  
Is month between 1 and 12 ?  
→ NO  → PRINT "Invalid Date"  
→ YES  
      ↓  
      Determine max days in month  
      ↓  
      Is day valid (1 to max days) ?  
      → NO  → PRINT "Invalid Date"  
      → YES  
            ↓  
            Is day == max days ?  
            → YES  
                  Is month == 12 ?  
                  → YES → day=1, month=1, year+1  
                  → NO  → day=1, month+1  
            → NO  → day+1  
            ↓  
            PRINT incremented date  
↓  
END  

------------------------------------------------------------
## 9️⃣ SALARY CALCULATION

START  
↓  
INPUT basic salary  
↓  
Is basic ≤ 10000 ?  
→ YES → Add 20% + 80%  
→ NO  
      ↓  
      Is basic ≤ 20000 ?  
      → YES → Add 25% + 90%  
      → NO  → Add 30% + 95%  
↓  
PRINT Gross Salary  
↓  
END  

------------------------------------------------------------
## 🔟 INCOME TAX CALCULATION

START  
↓  
INPUT salary  
↓  
Is salary ≤ 250000 ?  
→ YES → Tax = 0  
→ NO  
      ↓  
      Is salary ≤ 500000 ?  
      → YES → Tax = 5% above 250000  
      → NO  
            ↓  
            Is salary ≤ 1000000 ?  
            → YES → Tax = 5% + 20% above 500000  
            → NO  → Tax = 5% + 20% + 30% above 1000000  
↓  
PRINT Tax  
↓  
END  

------------------------------------------------------------

# ✅ RESULT

All conditional statement programs were executed successfully.  
Decision-making logic was verified using structured flowchart representation.

------------------------------------------------------------

