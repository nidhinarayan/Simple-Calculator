# 🧮 Simple Calculator (C)

A command-line calculator written in C. It can add, subtract, multiply and divide two numbers, and you can keep calculating until you choose to quit.

## Features
- Supports `+`, `-`, `*` and `/`
- Works with decimal numbers
- Shows an error for division by zero
- Shows an error for an invalid operator
- Asks if you want to calculate again

## How to run

Make sure you have GCC installed, then:

```bash
gcc main.c -o calculator
./calculator
```

On Windows:

```bash
gcc main.c -o calculator.exe
calculator.exe
```

## Sample output

```
=== Simple Calculator ===

Enter first number: 12
Enter operator (+, -, *, /): *
Enter second number: 4
Result: 12.00 * 4.00 = 48.00

Do you want to calculate again? (y/n): n

Thank you for using the calculator!
```

## What I learned
- Taking input with `scanf` (and why `" %c"` needs a space before it)
- Using `switch-case` for choosing an operation
- Using `do-while` to repeat the program
- Handling errors like division by zero

## Ideas to improve
- [ ] Add more operations (modulus, power, square root)
- [ ] Check if the user typed a valid number
- [ ] Move each operation into its own function
