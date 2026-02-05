# SCRIPT4.SH - Code Debugs and Fixes

---

## ERROR #1 (Type Logical): Line 24 --> Calculating the word count average by dividing with a denominator value of zero (0).

**1. Original Code:**

![Erro01](./image/error1.PNG)

**2. Fix: Calculate the average using the ***line_count*** variable instead**

![Fix01](./image/fix1.PNG)

---

## ERROR #2 (Type Syntax): Line 43 --> Missing closing curly backet for function `find_longest()` 

**1. Original Code:**

![Erro02](./image/error2.PNG)

**2. Fix: Apply `}` at end of the function**

![Fix02](./image/fix2.PNG)

---

## ERROR #3 (Type Logical): Line 64 --> Counter variable increasing by 1, instead of decreasing by 1

**1. Original Code:**

![Erro03](./image/error3.PNG)

**2. Fix: Change operator symbal to `-` from `+`**

![Fix03](./image/fix3.PNG)

---

## ERROR #4 (Type Syntax):  Line 74 --> Malformed `if-else` statement block

**1. Original Code:**

![Erro04](./image/error4.PNG)

**2. Fix: Added missing `; then` expression in the conditional statement block**

![Fix04](./image/fix4.PNG)

---
---

## FIXED CODE OUTPUT

Below is the output result of the corrected Shell 

![CodeResult](./image/code_output.PNG)
