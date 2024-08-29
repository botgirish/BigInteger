# BigInteger
In C/C++ the number of digits a long long int can have is a maximum of 20. And the question is to store the 22 digit number which is not easy to store in any kind of primitive type.so i designed a datatype called "BIGINT", a few basic operations are being implemented on the new data type.
This project is an implementation of a **Big Integer** class in C++ that can handle very large numbers, far exceeding the standard data types in C++. The code defines a custom class `BigInt` that supports a wide range of arithmetic operations like addition, subtraction, multiplication, division, modulo, exponentiation, and even more complex functions like calculating Fibonacci numbers, Catalan numbers, and factorials.

Here's a summary of how the code works:

1. **BigInt Class Construction**: The `BigInt` class can be constructed from various types of inputs, including strings, integers, and other `BigInt` objects. It stores the digits of the number in reverse order to simplify arithmetic operations.

2. **Arithmetic Operations**: The class overloads many operators (e.g., `+`, `-`, `*`, `/`, `==`, `<`, etc.) to perform arithmetic operations between big integers. These operators are carefully implemented to handle the unique challenges of working with large numbers.

3. **Increment/Decrement Operations**: The class supports pre and post-increment (`++`) and decrement (`--`) operations, allowing for easy manipulation of the numbers.

4. **Advanced Functions**: The code includes functions for computing the square root, power, Fibonacci sequence, Catalan numbers, and factorials using `BigInt`. These functions demonstrate the power and flexibility of the class, enabling calculations that would be impossible with standard data types.

5. **Input/Output Operations**: The class includes functions for reading from and writing to streams, making it easy to input large numbers from the user or print them to the console.

6. **Driver Code**: The `main` function includes examples of how to use the `BigInt` class. It shows how to perform various operations, compare numbers, and compute advanced mathematical functions. This part of the code is crucial for testing and demonstrating the capabilities of the `BigInt` class.

