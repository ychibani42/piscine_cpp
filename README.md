## 42 C++ Piscine (Modules 00-09)

The **C++ Piscine** consists of **9 modules (CPP00 → CPP09)** that progressively introduce object-oriented programming, STL, and modern C++ patterns, building on C foundation.

## Module Overview

**CPP00** – C++ Basics  
- `std::cout`, `std::string`, C vs C++ differences (`iostream` vs `stdio`, references, operator overloading).  
- Typical exercises: `PhoneBook` class, basic object manipulation, `.hpp`/`.cpp` file separation.

**CPP01** – Dynamic allocation, references, file I/O  
- `new/delete`, references, member function pointers, `fstream`.  
- Exercises like: zombie management (heap/stack), string replace in files, function pointer handling.

**CPP02** – Orthodox Canonical Form & Fixed-point numbers  
- Canonical form: default ctor, copy ctor, copy assignment, destructor.  
- `Fixed` class implementing fixed-point arithmetic with operator overloading.

**CPP03** – Inheritance  
- Single inheritance, base/derived classes, slicing problems.  
- `ClapTrap`, `ScavTrap`, `FragTrap` class hierarchy with method overriding.

**CPP04** – Polymorphism & Abstract classes  
- `virtual` functions, `override`, virtual destructors, abstract base classes.  
- `Animal`, `Cat`, `Dog`, `Brain` example with proper polymorphism and deep copying.

**CPP05** – Exceptions & Bureaucracy  
- C++ exceptions (`try/catch`, `std::exception`), exception hierarchies.  
- `Bureaucrat` and `Form` classes throwing grade validation exceptions.

**CPP06** – Type casting  
- `static_cast`, `dynamic_cast`, `reinterpret_cast`, `const_cast`.  
- Type conversion exercises, simple structure serialization.

**CPP07** – Templates  
- Function and class templates, generic instantiation.  
- `iter` function template, `Array<T>` container template.

**CPP08** – STL Containers & Algorithms  
- `std::vector`, `std::stack`, `std::map`, iterators, algorithms (`std::find`, etc.).  
- `easyfind`, `Span`, `MutantStack` exercises.

**CPP09** – Complete applications  
- Complex projects combining everything: `Bitcoin exchange`, `RPN calculator`, `PmergeMe`. Parsing, containers, algorithms, exceptions, OOP.

## Evaluation Criteria

1. **Canonical form**: All 4 ctors properly implemented
2. **Memory safety**: No leaks (valgrind), proper deep copy
3. **Polymorphism**: Virtual destructors, correct `override`
4. **STL usage**: Proper iterators, no raw arrays in containers
5. **Template correctness**: Works with multiple types
6. **Exception safety**: No leaks in exception paths

The C++ Piscine transforms C programmers into **proper OOP developers** ready for complex projects like **webserv** (HTTP server), **ft_irc** (IRC server), and **Transcendence** (full-stack web app).

Each module builds incrementally: start with simple classes (CPP00), master resource management (CPP01-02), inheritance/polymorphism (CPP03-04), modern C++ features (CPP05-08), ending with complete applications (CPP09).
