# Lesson 1 — Your first C++ program

## Goal

Compile and run a C++ program, understand its basic structure, and make a small change yourself.

## What each part means

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello, C++!" << '\n';
    return 0;
}
```

- `#include <iostream>` makes standard input/output tools available.
- `int main()` is where the program starts.
- `{ ... }` marks the body of the function.
- `std::cout` writes output to the terminal.
- `<<` sends a value to the output stream.
- `'\n'` prints a newline.
- `return 0;` signals that the program completed successfully.
- C++ statements generally end in `;`.

## Run it

From the repository root:

```bash
g++ -std=c++20 -Wall -Wextra -Wpedantic -g lessons/01_first_program.cpp -o first_program
./first_program
```

Use `clang++` instead of `g++` if that is the compiler installed on your Mac.

## Exercises

1. Change the program so it prints your own short introduction on three separate lines.
2. Print the result of `17 + 25` using `std::cout`.
3. Print the words `C++`, `is`, and `compiled` on one line with spaces between them.
4. Remove the semicolon from one output statement, compile again, and read the compiler error. Put the semicolon back.
5. Add a comment explaining what `main` does.

## Check your understanding

Answer these in `notes/lesson-01.md` using your own words:

- What does `#include <iostream>` provide?
- Where does execution begin?
- What does `std::cout` do?
- Why does the compiler complain when a statement is missing its semicolon?

## Completion rule

Do not move on just because the example runs. Make at least three changes yourself, compile after each meaningful change, and explain the program without reading this file.
