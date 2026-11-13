# Study plan

## Weekly cadence

Five sessions per week, 30–45 minutes each. Take days off when needed.

### Week 1 — Foundations
- Day 1: compile/run, `main`, output, comments
- Day 2: variables, primitive types, arithmetic
- Day 3: input, conditions, boolean logic
- Day 4: loops
- Day 5: functions and a tiny calculator

### Week 2 — Working with data
- `std::string`
- `std::vector`
- loops over collections
- references and `const`
- small text/data-processing exercises

### Week 3 — C++ memory model
- stack vs heap (conceptually)
- pointers and references
- object lifetime and scope
- RAII
- `std::unique_ptr` and `std::shared_ptr`

### Week 4 — Object-oriented C++
- structs and classes
- constructors
- access control and encapsulation
- composition
- destructors and resource ownership

### Week 5 — Standard library
- iterators
- algorithms (`sort`, `find`, `count_if`)
- lambdas
- maps and sets
- file input/output

### Week 6 — Modern C++
- `auto`
- range-based loops
- enums
- templates (intro)
- `std::optional` and `std::variant`

### Week 7 — Real project structure
- multiple `.cpp` and `.hpp` files
- header/source separation
- CMake
- compiler warnings
- debugger and sanitizers
- basic unit tests

### Week 8 — Deeper C++ concepts
- copy vs move
- move semantics
- const correctness
- error handling
- performance basics

### Weeks 9–10 — Concurrency and robotics preparation
- threads, mutexes, race conditions
- representing vectors, positions, and sensor readings
- update loops and state
- a small sensor-data simulator

### Weeks 11–12 — Robotics bridge (optional)
- install ROS 2 in a supported Linux environment
- write a simple C++ ROS 2 publisher/subscriber
- explore PX4 architecture and uORB concepts
- use Gazebo only after the C++ basics feel comfortable

## Milestones

1. Write a small program from a blank file without following a tutorial.
2. Explain the difference between a value, a reference, and a pointer.
3. Explain why RAII and smart pointers matter.
4. Build a multi-file C++ project with CMake.
5. Write a small class-based sensor simulator.
6. Read and make a small change to a simple ROS 2 C++ node.

Do not rush into ROS 2 or PX4 on day one. A solid C++ base will make those tools much easier.
