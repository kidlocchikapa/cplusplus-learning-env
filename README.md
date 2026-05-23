# C++ Learning Environment

A hands-on collection of C++ source files covering core to advanced programming concepts — including OOP, pointers, memory management, header files, and more. Built as a personal learning environment to practice and solidify C++ fundamentals.

---

## File Overview

### Object-Oriented Programming (OOP)

| File | Description |
|------|-------------|
| `Person.h` / `Person.cpp` | Defines a `Person` class — demonstrates class declaration, constructors, and member functions |
| `Box.h` / `Box.cpp` | `Box` class showcasing encapsulation and object instantiation |
| `ClassRectangle.cpp` / `ClassRectangle2.cpp` | Rectangle class examples — likely explores different approaches to class design |
| `Rectangle.h` / `Square.h` / `Triangle.h` | Header files for geometric shapes — lays the groundwork for inheritance or polymorphism |

### Pointers & Memory

| File | Description |
|------|-------------|
| `IntoToPointers.cpp` | Introduction to pointer syntax and basic usage |
| `Pointers.cpp` | Further pointer operations and dereferencing |
| `PointersArray.cpp` | Combining pointers with arrays |
| `SwapValues.cpp` | Swapping values using pointers or references |

### Areas & Geometry

| File | Description |
|------|-------------|
| `Area.cpp` | Basic area calculations |
| `AreaOfShapes.cpp` | Extended area computations for multiple shapes |
| `AreaHeader.h` / `CircleHeader.h` | Header declarations for shape-related functions |

### Arrays & Variables

| File | Description |
|------|-------------|
| `ArrayOfElements.cpp` | Working with arrays in C++ |
| `TrueVar.cpp` | Variable types and boolean logic exploration |

### Control Flow & Utilities

| File | Description |
|------|-------------|
| `RandomNumberGenerator.cpp` | Generating random numbers using `<cstdlib>` / `<ctime>` |
| `RandomNumberWithSwitchStatement.cpp` | Combines random number generation with `switch` statement logic |
| `Main.cpp` | Main entry point / general practice file |

### Header Files

| File | Description |
|------|-------------|
| `Header2.h` | Additional header declarations used across files |

---

## Getting Started

### Prerequisites

- A C++ compiler: [GCC](https://gcc.gnu.org/), [Clang](https://clang.llvm.org/), or [MSVC](https://visualstudio.microsoft.com/)
- Or an IDE like [VS Code](https://code.visualstudio.com/) with the C/C++ extension, [CLion](https://www.jetbrains.com/clion/), or [Code::Blocks](https://www.codeblocks.org/)

### Compiling a File

```bash
g++ FileName.cpp -o output
./output
```

For files that depend on a `.cpp` + `.h` pair (e.g. `Person`):

```bash
g++ Main.cpp Person.cpp -o output
./output
```

---

## Concepts Covered

- Classes and objects
- Constructors and destructors
- Header files and separate compilation
- Pointers, references, and pointer arithmetic
- Arrays and array-pointer relationships
- Control flow (`switch`, conditionals)
- Random number generation
- Geometric calculations and shape modeling

---

## Goals

- Reinforce C++ syntax and standard practices
- Understand memory layout and pointer behavior
- Build confidence with OOP design patterns
- Experiment with header/source file separation

---

## Notes

Files are standalone learning exercises — not a full project. Each `.cpp` file is meant to be compiled and run independently unless it references a corresponding `.h` / `.cpp` pair.

---

## Author

**kidlocchikapa** — Learning C++ one commit at a time.

---

## License

This repository is open for reference and learning. Feel free to fork and build on it.
