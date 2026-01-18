# GDSL Language Specification

## Overview
GDSL (Generic Domain-Specific Language) is designed to provide a simple yet powerful syntax for domain-specific applications. This document outlines the language specifications, syntax examples, and design goals of GDSL.

## Syntax Examples
1. **Basic Structure**
   ```gdsl
   function main() {
       // Your code here
   }
   ```

2. **Variables**
   ```gdsl
   let x = 10;
   let y = 20;
   let sum = x + y;
   ```

3. **Control Structures**
   ```gdsl
   if (x > y) {
       print("x is greater than y");
   } else {
       print("y is greater than or equal to x");
   }
   ```

4. **Loops**
   ```gdsl
   for (let i = 0; i < 10; i++) {
       print(i);
   }
   ```

## Design Goals
- **Simplicity**: The syntax should be easy to read and understand, making it accessible to non-programmers.
- **Flexibility**: GDSL should be adaptable to various domains, allowing users to define custom functions and operations.
- **Performance**: The language should provide efficient execution of scripts, suitable for real-time applications.
- **Extensibility**: Users should be able to extend the language with their own functions and libraries.

## Conclusion
The GDSL language aims to fill the gap for developers looking for a tailored solution in specific domains, balancing expressiveness and simplicity.