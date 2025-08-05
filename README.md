Name: Prathyush Nimmagadda  
PRN: 24070123064  
Batch: ENTC A3  

# C++ Programs: Bitwise Operators and Bit Manipulation

## Overview

This document presents two C++ programs showcasing practical applications of bitwise operators. The first program explores fundamental bitwise operations like AND, OR, NOT, XOR, left shift, and right shift. The second program demonstrates bit manipulation techniques for setting and clearing specific bits within an integer. These programs help students grasp low-level data processing and efficient binary handling through bitwise logic.

## Program 1: Demonstration of Basic Bitwise Operations

### Purpose  
To illustrate the effect of essential bitwise operators on integer operands at the binary level.

### Concepts Covered  
- Bitwise AND (&): Produces 1 only when both corresponding bits are 1.  
- Bitwise OR (|): Produces 1 if any one of the bits is 1.  
- Bitwise NOT (~): Inverts every bit of the operand.  
- Bitwise XOR (^): Produces 1 only when bits differ.  
- Left Shift (>): Shifts bits right by a specified count, effectively halving the number per shift.  

### Logic Summary  
- Two integers are defined and initialized.  
- Bitwise operations are applied between these operands.  
- The program outputs the results of each operation for demonstration.  

### Learning Outcome  
- Enhances insight into binary manipulation of integer data.  
- Explains how computers use bit-level operations to process information.  
- Lays the groundwork for advanced topics such as encryption algorithms, data compression, and hardware communication.  

### Sample Output:
```
AND : 1
OR : 7
NOT : -6
XOR : 6
LEFT_SHIFTED : 12
RIGHT_SHIFTED : 2
```

## Program 2: Bit Manipulation – Setting and Clearing Particular Bits

### Purpose  
To demonstrate modifying specific bits in an integer by selectively setting or resetting bits using bitwise techniques.

### Concepts Covered  
- Bit Setting: Applies bitwise OR with a left-shifted mask that sets the target bit to 1.  
- Bit Clearing: Uses bitwise AND with the negation of a shifted mask to reset the target bit to 0.  
- Interactive Input: Receives bit positions from the user to dynamically modify the bits.  

### Logic Summary  
- User inputs the position of the bit to be set.  
- The program sets the specified bit using OR with an appropriate mask.  
- User inputs the position of the bit to be cleared.  
- The program clears that bit using AND with the inverted mask.  

### Learning Outcome  
- Demonstrates practical bit masking techniques.  
- Encourages thinking in terms of binary representation and memory bits.  
- Provides key skills useful in embedded systems programming, code optimization, and graphics processing.  

### Sample Output:
```
Enter bit to be set: 3
Enter bit to be reset: 2
Your number is: 30
Your number is: 26
```

## Conclusion

These programs serve as an important introduction to bitwise arithmetic and bit-level data manipulation in C++. They enable learners to:

- Perform direct binary operations on integers.  
- Utilize bit shifts for multiplication and division by powers of two.  
- Manipulate individual bits through masks for precise control.  

Proficiency with these concepts is vital for tasks involving low-level programming, high-performance applications, and technologies such as cryptography, digital signal processing, and device interfacing.
