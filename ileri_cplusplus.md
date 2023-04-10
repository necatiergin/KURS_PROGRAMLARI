# Advanced C++

## copy elision
+ temporary materialization
+ prvalue xvalue conversion
+ unmaterialized object passing
+ return value optimization (rvo)
+ named return value optimization (nrvo) 
+ scenarios blocking copy elision
+ throwing by value
+ catching by value
+ mandatory copy elision
+ typical mistakes & misconceptions
+ guidelines

## move semantics 
+ basic features of move semantics
+ std::move
+ move semantics & special member functions
+ taşıma semantiğinden faydalanma biçimleri, 
+ referans qualifiers & move semantics
+ moved-from states
+ move semantics & exception guarantees
+ move semantics in STL
+ move only types
+ STL moving algorithms
+ typical mistakes & misconceptions
+ guidelines

## perfect forwarding
+ forwarding (universal) references
+ forwarding reference vs R value reference
+ std::forward
+ auto && for perfect forwarding
+ decltype(auto) & perfect forwarding
+ perfect forwarding of return values
+ perfect forwarding in STL
+ typical mistakes & misconceptions
+ guidelines

## constants and constant expressions C++11/14/17/20/23
+ constexpr variables
+ constexpr functions
+ constexpr constructors
+ literal types, 
+ consteval & immediate functions
+ constinit
+ constexpr virtual functions
+ constexpr lambda functions
+ user defined literals.

## type deduction
+ auto type deduction
+ decltype specifier
+ decltype(auto)
+ trailing return type
+ auto return type
+ type deduction in lambda expressions

## templates & generic programming (advanced)
+ basic concepts
  + function templates
  + class templates
  + variable templates
  + alias templates
+ member templates, 
+ template parameters
  + type parameters
  + non-type parameters 
    + auto non-type parameters
  + template template parameters
  + function templates & overloading
+ explicit specialization
+ partial specialization
+ template instantiation
+ template arguments
+ template argument deduction
+ dependent & non-dependent names
+ templates & friendship
+ ctad 
+ meta functions and standard type_traits library
static_assert declarations & templates
+ std::type_identity
+ tag dispatch
+ if constexpr (static if)
+ variadic templates
+ sizeof... operator
+ pack expansion patterns 
+ fold expressions
+ sfinae
  + std::enable_if
  + std::void_t
  + std::declval
+ C++20 additions

## C++ idioms & tecniques

## concepts (C++20)

## lambda expressions C++11/14/17/20/23 
lambda expressions basics (fast forward)
  + lambda expressions and type deductions
  + lambda expressions & constexpr
  + generalized lambda expressions
  + lambda init capture
  + lambda expressions & perfect forwarding
  + pack expansions in lambda expressions
  + lambda expressions & STL algorithms
+ recursive lambda
+ lambda expressions in member functions
+ lambda expressions for functional programming
+ lambda expressions in C++20/23
  + template parameter lists on lambdas (C++20)
  + new lambda captures (C++20)
  + lambda expressions in unevaluated context - C++20
  + lambda init capture pack expansions (C++20)
  + default constructible and assignable stateless lambdas (C++20).
+ lambda idioms

## standard library (C++17/20/23)
+ random library
+ regex library
+ vocabulary types (C++17)
  + std::optional
  + std::variant
  + std::any
+ std::format (C++20)
+ std::ranges (C++20)
+ std::span

## coroutines


