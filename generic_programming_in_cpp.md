# Advanced Generic Programming with Modern C++ (C++11/14/17/20/23)

**Duration:** 60 Hours  
**Level:** Advanced  

---

# Prerequisites

Participants are expected to have:

- Strong C knowledge
- Intermediate / Advanced Modern C++
- References and value categories
- Move semantics
- Function overloading
- Classes and inheritance
- Lambdas
- Basic familiarity with the standard library

---

# Course Goals

After completing this course participants will:

- Understand generic programming philosophy
- Master template mechanics and language rules
- Understand template instantiation and specialization mechanisms
- Learn compile-time programming techniques
- Understand STL design philosophy
- Learn modern constraints and concepts
- Design reusable generic libraries
- Understand advanced metaprogramming techniques
- Learn real-world generic design patterns

---

# Module 1 — Generic Programming Fundamentals

**Duration:** 2 Hours

## Generic Programming

- What is Generic Programming?
- Generic Programming vs Object-Oriented Programming
- Static polymorphism
- Runtime polymorphism
- Compile-time polymorphism
- Zero-overhead abstraction principle
- Generic libraries
- Compile-time vs runtime design decisions
- STL philosophy and design goals

## Historical Perspective

- Alexander Stepanov
- STL origins
- Andrei Alexandrescu
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
- overload set
- template-id
- template-name
- template parameter
- template argument
- point of instantiation

## Translation Model

- template compilation model
- point of instantiation
- two-phase translation

---

# Module 3 — Function Templates

**Duration:** 3 Hours

- Function templates
- Function template overloading
- Explicit template arguments
- Template argument deduction
- Non-deduced contexts
- Function templates and overload resolution
- Explicit specialization of function templates

## Forwarding

- forwarding references
- reference collapsing rules
- perfect forwarding

Example:

```cpp
template<typename T>
void foo(T&& x);
```

---

# Module 4 — Class Templates

**Duration:** 3 Hours

- Class templates
- Member templates
- Nested templates
- Templated constructors
- Variable templates
- Alias templates

---

# Module 5 — Template Parameters

**Duration:** 3 Hours

## Type Parameters

- typename
- class

## Non-Type Parameters

- integral parameters
- pointer parameters
- reference parameters

## Auto Non-Type Parameters

```cpp
template<auto N>
```

## Structural Types (C++20)

## Template Template Parameters

```cpp
template<
    typename T,
    template<typename> typename Container>
```

---

# Module 6 — Template Instantiation Model

**Duration:** 2 Hours

- Implicit instantiation
- Explicit instantiation
- extern template
- Code bloat
- ODR implications
- Point of instantiation

---

# Module 7 — Template Specialization

**Duration:** 3 Hours

## Explicit Specialization

## Partial Specialization

## Variable Template Specialization

## Alias Template Limitations

Example:

```cpp
template<typename T>
using ptr_t = T*;
```

Discussion:

Why alias templates cannot be partially specialized

---

# Module 8 — Dependent Names and Two-Phase Lookup

**Duration:** 4 Hours

- Dependent names
- Non-dependent names
- Current instantiation
- Injected-class-name
- typename keyword
- template keyword
- Name lookup rules
- Two-phase lookup

Example:

```cpp
T::value
```

---

# Module 9 — Friendship and Templates

**Duration:** 1 Hour

- Friend function templates
- Friend class templates
- Template friendship
- Hidden friend idiom
- ADL interaction

---

# Module 10 — Variadic Templates

**Duration:** 4 Hours

- Variadic templates
- Parameter packs
- Pack expansion
- Expansion patterns
- sizeof...
- Nested expansions
- Empty packs

---

# Module 11 — Fold Expressions

**Duration:** 2 Hours

- Unary fold
- Binary fold
- Left fold
- Right fold

Example:

```cpp
(sum + ...)
```

---

# Module 12 — Compile-Time Programming Fundamentals

**Duration:** 3 Hours

- compile-time programming philosophy
- constexpr
- consteval
- constinit
- std::integral_constant
- std::bool_constant
- std::type_identity

---

# Module 13 — Type Traits and Metafunctions

**Duration:** 4 Hours

## Metafunction Design

- metafunctions
- compile-time type manipulation
- type transformations

## Standard Type Traits

- remove_cv
- remove_reference
- conditional
- common_type
- invoke_result
- type_identity
- decay

## Detection Traits

- custom traits
- detection traits

---

# Module 14 — SFINAE

**Duration:** 5 Hours

- SFINAE fundamentals
- substitution failure
- immediate context
- std::enable_if
- std::void_t
- detection idiom
- std::declval

Example:

```cpp
has_begin<T>
```

---

# Module 15 — Compile-Time Dispatch Techniques

**Duration:** 3 Hours

- Tag dispatch
- Priority tag
- Expression SFINAE
- if constexpr
- Overload ranking techniques

---

# Module 16 — Class Template Argument Deduction (CTAD)

**Duration:** 2 Hours

- CTAD
- implicit deduction guides
- user-defined deduction guides
- deduction behavior

---

# Module 17 — Concepts

**Duration:** 6 Hours

## Concept Fundamentals

- Concept syntax
- Constraint system

## Requires Clauses

## Requires Expressions

- simple requirements
- type requirements
- compound requirements
- nested requirements

## Constrained Templates

- type constraints
- constrained auto
- abbreviated templates

## Standard Concepts

- same_as
- derived_from
- integral
- regular
- invocable
- predicate
- sortable
- ranges concepts

---

# Module 18 — Concepts vs SFINAE

**Duration:** 2 Hours

- Historical evolution
- SFINAE to concepts migration
- Equivalent examples
- Readability comparison
- Diagnostics quality comparison

---

# Module 19 — Generic Library Design

**Duration:** 3 Hours

- Generic interface design
- Traits-based design
- Policy-based design
- CRTP
- Hidden friend idiom
- Type erasure vs templates
- Compile-time interfaces
- Design tradeoffs

---

# Module 20 — Modern Generic Programming Ecosystem

**Duration:** 5 Hours

## Generic Callable Infrastructure

- std::invoke
- invoke_result
- Callable entities

## Generic Lambdas

- Generic lambdas
- Templated lambdas
- NTTP lambdas

## Tuple Utilities

- tuple protocol
- std::apply
- make_from_tuple
- tuple-like interfaces

## Variant Utilities

- std::variant
- visitation

## Ranges Overview

- ranges
- views
- projections

## Customization Point Objects

- CPO design philosophy

## Formatter Customization

- std::formatter specialization

---

# Workshop Projects

Mini projects integrated throughout the course:

- Generic printer
- Tuple algorithms
- Compile-time parser
- Generic serialization library
- Type-safe factory
- Variant visitor framework
- Compile-time units library
- Mini ranges implementation

---

# Final Project

**Duration:** Last 4 Hours

Implementation of a mini generic utility library:

```cpp
namespace nec
{
    // traits
    // concepts
    // invoke
    // tuple
    // algorithms
    // optional
}
```

Project Goals:

- Apply generic design principles
- Apply compile-time techniques
- Apply concepts and constraints
- Build reusable components

---
