

# Simple Calculator Program

This is a simple calculator program written in C++ that performs basic arithmetic operations and factorial calculation. It allows the user to perform calculations, store results in memory, and repeat operations as desired.

## Features

- Addition (`+`), subtraction (`-`), multiplication (`*`), division (`/`), exponentiation (`^`), and factorial (`!`) operations are supported.
- Memory functionality to store and recall results.
- User-friendly command line interface.

## Usage

1. **Compilation**:
   - Compile the program using a C++ compiler (e.g., g++).
   ```bash
   g++ calculator.cpp -o calculator
   ```

2. **Execution**:
   - Run the compiled executable.
   ```bash
   ./calculator
   ```

3. **Input Format**:
   - Enter the first number, followed by the operator (`+`, `-`, `*`, `/`, `^`, `!`).
   - For factorial operation (`!`), enter only one number.
   - For binary operations (`+`, `-`, `*`, `/`, `^`), enter the second number.
   - After calculating, choose from the following options:
     - `mi` to insert the result into memory.
     - `mc` to clear memory.
     - `restart` to start from the beginning.
     - `reuse` to reuse the result.
     - `mr` to reuse the number in memory.
     - `quit` to exit the program.

4. **Example**:
   ```
   + to add, - to subtract, * to multiply, / to divide, ^ to power, ! to factorial

   5
   *
   3
   =15

   Type 'mi' to insert the number into memory, or 'mc' to clear memory
   mi

   Type 'restart' to start again from the beginning, 'reuse' to use the result, 
   'mr' to reuse the number in the memory, or 'quit' to quit: 
   reuse
   15
   ```

## Notes

- **Goto Statement**: The use of `goto` in the code is for demonstration purposes. In real-world applications, it is generally discouraged due to readability and maintainability concerns.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Make sure to include the `LICENSE` file in your repository containing the actual license text (e.g., MIT License) and any additional information relevant to your project. This README provides a clear and concise overview of what the calculator program does, how to use it, and additional considerations for potential users or contributors.
