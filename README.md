# C++ Learning Roadmap

A practical, Git-friendly C++ learning track focused on becoming comfortable with modern C++ and eventually applying it to robotics, PX4, ROS 2, and simulation.

## How to use this repository

1. Work through one lesson at a time.
2. Put your solutions in `projects/` (or make a folder for each exercise).
3. Write short notes in `notes/` when something is confusing.
4. Commit your work regularly. Small, honest commits are a useful progress record.
5. Do not copy solutions before attempting the exercises.

## Daily routine (30–45 minutes)

- 5 min: review yesterday's code and notes.
- 10–15 min: learn one concept.
- 15–20 min: write code yourself.
- 5 min: test, explain what the code does, and commit.

Aim for 5 days per week. If you only have 15 minutes, do the coding exercise and stop. Consistency matters more than marathon sessions.

## Roadmap

| Stage | Focus | Target |
|---|---|---|
| 0 | Setup, compiler, Git workflow | Compile and run a small program |
| 1 | Variables, types, input/output, conditions, loops, functions | Write small programs without copying |
| 2 | `std::string`, `std::vector`, arrays, references, `const`, scope | Manipulate collections safely |
| 3 | Pointers, stack vs heap, RAII, smart pointers | Understand ownership and lifetime |
| 4 | Classes, constructors, destructors, encapsulation | Model a small system with classes |
| 5 | STL algorithms, iterators, lambdas, exceptions, file I/O | Write idiomatic modern C++ |
| 6 | Templates, `auto`, move semantics, `std::optional`, `std::variant` | Read and write modern C++ |
| 7 | Build systems, debugging, testing, sanitizers | Build a maintainable project |
| 8 | Concurrency and performance basics | Understand threads and data races |
| 9 | Robotics bridge: coordinate types, sensor data, state updates | Prepare for ROS 2 / PX4 C++ work |

Suggested pace: roughly 8–12 weeks at 30–45 minutes a day, 5 days a week. Go faster or slower as needed. Do not add LeetCode to this plan yet.

## Recommended tools

- Compiler: `g++` or `clang++`
- Language standard: C++20
- Editor: VS Code, CLion, or your preferred editor
- Build system later: CMake
- Version control: Git + a private or public GitHub repository

On macOS, install Apple's command-line developer tools with:

```bash
xcode-select --install
```

Then check:

```bash
clang++ --version
git --version
```

On Ubuntu:

```bash
sudo apt update
sudo apt install build-essential gdb git cmake
```

Then check:

```bash
g++ --version
git --version
```

## Compile a file

From the repository root:

```bash
g++ -std=c++20 -Wall -Wextra -Wpedantic -g lessons/01_first_program.cpp -o first_program
./first_program
```

On macOS, `clang++` can be used in place of `g++`.

## Git workflow

Create a repository on GitHub, then from this folder:

```bash
git init
git add .
git commit -m "Start C++ learning roadmap"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/cpp-learning-roadmap.git
git push -u origin main
```

After each session:

```bash
git status
git add .
git commit -m "Complete lesson 01 exercises"
git push
```

Replace the remote URL with your actual GitHub repository URL. Never commit passwords, API keys, tokens, private keys, or personal credentials.

## Progress checklist

- [ ] Stage 0: setup and first compile
- [ ] Stage 1: fundamentals
- [ ] Stage 2: strings, vectors, references
- [ ] Stage 3: pointers, memory, RAII
- [ ] Stage 4: classes and object lifetime
- [ ] Stage 5: STL and practical C++
- [ ] Stage 6: modern C++ features
- [ ] Stage 7: CMake, debugging, tests
- [ ] Stage 8: concurrency
- [ ] Stage 9: robotics mini-project

## The rule

Understand the code you write. You do not need to memorize every syntax detail. Learn how to reason about types, lifetime, ownership, and behavior, and get comfortable looking things up.
