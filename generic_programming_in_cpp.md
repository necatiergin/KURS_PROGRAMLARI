# Advanced Generic Programming with Modern C++ (C++11/14/17/20/23)

**Duration:** 60 Hours  
**Level:** Advanced  


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
- Historical Perspective

## Terminology

- primary template
- specialization
- explicit (full) specialization
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

## Template Parameters

- Type Parameters
- Non-Type Parameters
  - integral parameters
  - floating parameters
  - object pointer parameters
  - function pointer parameters
  - reference parameters
  - auto non-type parameters
- Structural Types (C++20)
- Template Template Parameters

## Translation Model
- template compilation model
- point of instantiation
- two-phase translation

---

## Function Templates

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

---

## Class Templates

- Class templates
- Member templates
- Nested templates
- Templated constructors
- Variable templates
- Alias templates

---



---

## Template Instantiation Model

- Implicit instantiation
- Explicit instantiation
- extern template
- Code bloat
- ODR implications
- Point of instantiation

---

## Template Specialization

- Explicit Specialization
- Partial Specialization
- Variable Template Specialization
- Alias Template Limitations

--- 

## Dependent Names and Two-Phase Lookup

- Dependent names / Non-dependent names
- Current instantiation
- Injected-class-name
- typename keyword
- template keyword
- Name lookup rules
- Two-phase lookup

---

## Friendship and Templates

- Friend function templates
- Friend class templates
- Template friendship
- Hidden friend idiom
- ADL interaction

---

## Variadic Templates

- Variadic templates
- Parameter packs
- Pack expansion
- Expansion patterns
- sizeof... operator
- Nested expansions
- handling empty packs

---

## Fold Expressions
- Unary left fold / unary right fold
- Binary left fold / binary right fold
- Fold idioms

## Compile-Time Programming Fundamentals

- compile-time programming philosophy
- constexpr
- consteval
- constinit
- std::integral_constant
- std::bool_constant
- std::type_identity

---

## Type Traits and Metafunctions

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

# SFINAE

- SFINAE fundamentals
- substitution failure
- immediate context
- std::enable_if
- std::void_t
- detection idiom
- std::declval

---

# Compile-Time Dispatch Techniques

- Tag dispatching
- Priority tag
- Expression SFINAE
- if constexpr
- Overload ranking techniques

---

## Class Template Argument Deduction (CTAD)

- CTAD
- implicit deduction guides
- user-defined deduction guides
- deduction behavior

---

## Concepts

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

# Concepts vs SFINAE

- Historical evolution
- SFINAE to concepts migration
- Equivalent examples
- Readability comparison
- Diagnostics quality comparison

---

# Generic Library Design

- Generic interface design
- Traits-based design
- Policy-based design
- CRTP
- Hidden friend idiom
- Type erasure vs templates
- Compile-time interfaces
- Design tradeoffs

---

## Modern Generic Programming Ecosystem

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
- tuple-like interface for structured bindings

## Variant Utilities

- std::variant
- visitation

---



