# Simple Python Calculator

A basic calculator program written in Python that allows the user to perform continuous arithmetic operations such as **Addition**, **Subtraction**, **Multiplication**, and **Division**.  
It also supports **Continue**, **Restart**, and **Stop** options for flexible usage.



## Features

- Perform the following operations:
  - ➕ Addition  
  - ➖ Subtraction  
  - ✖ Multiplication  
  - ➗ Division (with zero-division check)
- Allows user to:
  - Continue with the current result
  - Restart the calculator from the beginning
  - Stop the program anytime
- Inputs are taken dynamically from the user



## How It Works

1. User enters the first number  
2. User selects:
   - Second number  
   - Operation (1-4)  
3. Calculator performs the operation and prints the updated result  
4. User decides whether to:
   - **C** → Continue (use result as next first number)  
   - **R** → Restart the calculator  
   - **S** → Stop  

The program loops until the user chooses to stop.



##  Code Structure

- `add(a, b)` → Returns a + b  
- `sub(a, b)` → Returns a - b  
- `mul(a, b)` → Returns a * b  
- `div(a, b)` → Returns integer division (a // b)  
- `calculator()` → Main logic that handles user interaction and looping  

