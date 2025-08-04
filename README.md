
Name: Prathyush Nimmagadda  
PRN: 24070123064
Batch: ENTC A3  

# C++ Programs: Bitwise Operators and Bit Manipulation

## Overview

This document provides a theoretical explanation of two C++ programs that demonstrate the use of bitwise operators. The first program covers basic bitwise operations such as AND, OR, NOT, XOR, left shift, and right shift. The second program focuses on bit manipulation tasks such as setting and resetting specific bits in an integer. These programs are designed to introduce students to low-level data manipulation using bitwise logic.

---

## Program 1: Basic Bitwise Operations

### Purpose
The objective of this program is to demonstrate how fundamental bitwise operations work on integer values at the binary level.

### Concepts Covered
- Bitwise AND (&): Compares each bit of two operands; the result bit is 1 only if both bits are 1.  
- Bitwise OR (|): Result bit is 1 if at least one corresponding bit is 1.  
- Bitwise NOT (~): Inverts all bits of the operand.  
- Bitwise XOR (^): Result bit is 1 if bits are different.  
- Left Shift (<<): Shifts bits to the left by a specified number of positions, effectively multiplying the number by 2 for each shift.  
- Right Shift (>>): Shifts bits to the right by a specified number of positions, effectively dividing the number by 2 for each shift.  

### Logic Summary
- Two integers are initialized.  
- Bitwise operations are performed between them.  
- Results are computed using bitwise operators and displayed to the user.  

### Educational Value
- Reinforces understanding of how binary operations affect integers.  
- Demonstrates how computers process data at the bit level.  
- Builds foundation for more advanced topics like encryption, compression, and hardware interfacing.  

### Output:
```
AND : 1
OR : 7
NOT : -6
XOR : 6
LEFT_SHIFTED : 12
RIGHT_SHIFTED : 2
```

---

## Program 2: Bit Manipulation – Set and Reset Specific Bits

### Purpose
This program demonstrates how to set and reset individual bits of an integer using bitwise manipulation techniques.

### Concepts Covered
- Setting a Bit: Uses the bitwise OR operation combined with a left shift to turn a specific bit to 1.  
- Resetting a Bit: Uses bitwise AND with the negated bit mask to turn a specific bit to 0.  
- User Interaction: Allows the user to input the positions of bits they wish to set and reset.  

### Logic Summary
- The user inputs the bit position they want to set.  
- The target integer is modified using the OR operation with a bitmask that has a 1 at the desired bit.  
- The user inputs the bit position they want to reset.  
- The value is modified using the AND operation with the negation of a bitmask.  

### Educational Value
- Introduces bit masking techniques.  
- Encourages thinking about memory and data in binary form.  
- Provides foundational skills useful in embedded systems, optimization, and graphics programming.  

### Output:
```
Enter bit to be set: 3
Enter bit to be reset: 2
Your number is: 30
Your number is: 26
```

---

## Conclusion

These programs serve as an introduction to bitwise operations and manipulation in C++. They help learners understand how to:

- Perform binary-level operations on integers.  
- Use logical shifts to multiply or divide by powers of two.  
- Set and clear specific bits in a binary representation of a number.  

Mastering these skills is essential for low-level programming tasks, performance-critical systems, and domains like cryptography, signal processing, and device control.
