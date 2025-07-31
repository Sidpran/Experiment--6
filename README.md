# 🔁 C++ Loops and Decision-Making Statements

## 🎯 Objective

The objective of this mini-project is to explore and implement **decision-making statements** and **looping constructs** in the C++ programming language. Through a series of structured experiments, we aim to understand how control structures like `for` loops, `if` conditions, and `continue` statements work together to manage flow, repeat operations, and filter logic during runtime. This project provides foundational hands-on experience in structured programming.

---

## 📚 Theory & Algorithm

### 1. ✅ Print Even Numbers from 1 to 10

**Theory**:  
This experiment uses a `for` loop to iterate from 1 to 10. During each iteration, it checks if a number is divisible by 2 using the condition `i % 2 == 0`. If the condition is true, the number is even and is printed.

**Algorithm**:
1. Start the program.
2. Loop variable `i` from 1 to 10.
3. If `i % 2 == 0`, print `i`.
4. Continue until `i` exceeds 10.
5. End program.

---

### 2. ✅ Print “COLLEGE” 5 Times

**Theory**:  
Demonstrates loop repetition for constant output. The loop runs exactly 5 times, printing the word “COLLEGE” on each iteration.

**Algorithm**:
1. Start the program.
2. Loop variable `i` from 0 to 4.
3. Print `(i+1). COLLEGE`.
4. End loop and program.

---

### 3. ✅ Program Using `for` Loop and `continue`

**Theory**:  
This program illustrates the `continue` statement within a loop. It skips the current iteration if a condition is met (in this case, if the number is even), effectively filtering out even numbers and printing only odd ones.

**Algorithm**:
1. Start the program.
2. Loop from 1 to 9.
3. If `i % 2 == 0`, use `continue`.
4. Else, print `i`.
5. End loop and program.

---

### 4. ✅ Left-Aligned Inverse Star Pattern

**Theory**:  
This uses nested `for` loops to print an inverted triangle of stars. The outer loop decreases from 6 to 1, and the inner loop prints stars equal to the current row number.

**Algorithm**:
1. Start the program.
2. Outer loop from 6 to 1.
3. Inner loop prints `*` for current row count.
4. Print newline after inner loop.
5. End program.

---

### 5. ✅ Right-Aligned Star Triangle

**Theory**:  
Prints a triangle of stars aligned to the right. It uses one inner loop to print spaces and another to print stars, demonstrating loop control for visual formatting.

**Algorithm**:
1. Start the program.
2. Loop `i` from 1 to 6.
3. Print `(6 - i)` spaces.
4. Print `i` stars.
5. Move to next line.
6. End program.

---

### 6. ✅ Center-Aligned Triangle (Pyramid)

**Theory**:  
Creates a centered pyramid using stars. It requires calculating both spaces and stars to maintain symmetry. The star count per row follows the formula `(2*i - 1)`.

**Algorithm**:
1. Start the program.
2. Loop `i` from 1 to 6.
3. Print `(6 - i)` spaces.
4. Print `(2*i - 1)` stars.
5. Move to next line.
6. End program.

---

### 7. ✅ Left-Aligned Number Triangle

**Theory**:  
This pattern prints incremental numbers row by row in triangle format. A counter is used to print increasing integers using nested loops.

**Algorithm**:
1. Initialize counter `a = 1`.
2. Outer loop for rows (i = 0 to 3).
3. Inner loop for columns (j = 0 to i).
4. Print value of `a` and increment.
5. Newline after each row.
6. End program.

---

### 8. ✅ Left-Aligned Triangle Using `*`

**Theory**:  
A basic pattern that prints a left-aligned triangle of stars. It helps in understanding how the number of symbols per line grows with each loop.

**Algorithm**:
1. Outer loop from 1 to 6.
2. Inner loop from 1 to `i`.
3. Print `*` per loop.
4. Move to next line.
5. End program.

---

### 9. ✅ Print Numbers from 1 to 20

**Theory**:  
A straightforward loop example that prints numbers sequentially from 1 to 20 using a single loop construct.

**Algorithm**:
1. Start the program.
2. Loop `i` from 1 to 20.
3. Print `i`.
4. End loop and program.

---

### 10. ✅ Password Authentication

**Theory**:  
Demonstrates basic decision-making with user input. The program checks if the entered password matches the predefined one using an `if-else` condition.

**Algorithm**:
1. Define correct password (e.g., "Soham").
2. Prompt user for password input.
3. If input matches, print “Access granted.”
4. Else, print “Access denied.”
5. End program.

---

## ✅ Conclusion

This project provided valuable hands-on experience with **loops**, **conditional logic**, and **pattern generation** in C++. We achieved the following outcomes:

- Applied `for` loops for structured repetition.
- Used `if` and `continue` to implement decision-making and control flow within loops.
- Built visually formatted outputs such as aligned triangles and numeric patterns using nested loops.
- Practiced user interaction through input-based authentication logic.
- Strengthened problem-solving skills by designing algorithms to match expected program behavior.

