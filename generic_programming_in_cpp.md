# Advanced Generic Programming with Modern C++ (C++11/14/17/20/23)

**Duration:** 60 Hours  
**Level:** Advanced  

## Prerequisites

- Strong C knowledge
- Intermediate/Advanced Modern C++
- Templates at beginner level
- References, move semantics, overload resolution, lambdas
- Basic familiarity with the standard library

---

# Module 1 — Generic Programming Fundamentals
**Duration:** 2 Hours

## Generic Programming

- What is Generic Programming?
- Generic Programming vs Object-Oriented Programming
- Static polymorphism vs runtime polymorphism
- Zero-overhead abstraction principle
- Generic libraries
- Compile-time vs runtime design decisions
- STL philosophy and design goals

## Historical Perspective

- Alexander Stepanov and STL
- Andrei Alexandrescu
- Evolution of templates
- Evolution of generic programming in C++

---

# Module 2 — Template Terminology and Mechanics
**Duration:** 3 Hours

## Terminology

- primary template
- specialization
- explicit specialization
- partial specialization
- instantiation
- substitution
- dependent context
- deduction
- template-id
- template-name
- overload set
- point of instantiation
- template parameter
- template argument
- template parameter list

## Translation Model

- two-phase translation
- template compilation model
- point of instantiation

---

# Module 3 — Function Templates
**Duration:** 3 Hours

- Function templates
- Template argument deduction
- Explicit template arguments
- Non-deduced contexts
- Function template overloading
- Function templates and overload resolution
- Explicit specialization of function templates
- Forwarding references
- Reference collapsing rules
- Perfect forwarding

Examples:

```cpp
template<typename T>
void foo(T&& x);
