## Kurs içeriği yeniden düzenleniyor. Yakında tamamlanacak...

# Advanced C++

## copy elision
temporary materialization, prvalue xvalue conversion, unmaterialized object passing, return value optimization (rvo), named return value optimization (nrvo), blocking copy elision, throwing by value, catching by value, mandatory copy elision.

## move semantics 
R Value references (brush up), taşıma semantiğinin temel nitelikleri, std::move, move semantics & special member functions, taşıma semantiğinden faydalanma biçimleri, 
referans qualifiers & move semantics, moved-from states, move semantics & exception guarantees, move semantics in STL, move only types, moving algorithms, move iterators, typical mistakes, guidelines.

## perfect forwarding
forwarding (universal) references, forwarding reference vs R value reference, std::forward in detail, auto && for perfect forwarding,  decltype(auto) & perfect forwarding, perfect forwarding of return values, perfect forwarding in STL, typical mistakes, guidelines.

## constants and constant expressions C++11/14/17/20
constexpr variables, constexpr functions, constexpr constructors, literal types, consteval & immediate functions, constinit, constexpr virtual functions, constexpr lambda functions, user defined literals.

## templates & generic programming (advanced)
basic concepts, function templates, class templates, variable templates, alias templates, member templates, template parameters, type parameters, non-type parameters
template parameters, function templates & overloading, explicit specialization, partial specialization, template instantiation, template arguments, template argument deduction, dependent & non-dependent names, templates & friendship, auto parameter type, ctad (class template argument deduction), meta functions, value returning meta functions, type returning meta functions, type traits library, static_assert & templates, std::type_identity, tag dispatch, if constexpr, variadic templates, sizeof... operator, pack expansions, fold expressions, unary right fold, unary left fold, binary right fold, binary left fold, sfinae, std::enable_if, std::void_t, std::declval, std::invoke, std::apply, C++20 additions, string literals template parameters, removal of some typename usage restrictions.

## C++ idioms & tecniques
raii, swap functions, copy & swap, scope guards, strong types, tag dispatch, hidden friends, virtual constructor, virtual friend, factories, proxy, memory ownership, pimpl & fast pimpl, attorney - client, local buffer optimization, implementation class, non virtual interface, named parameters, type erasure, immediatly invoked lambda expression, reference counting, positive lambda, exception dispatcher, biased distribution, gather algorithm, slide algorithm. 

## lambda expressions C++11/14/17/20 
lambda expressions & type deduction, mutable lambdas, lambda expressions & constexpr, generalized lambda expressions, lambda init capture, lambda expressions & perfect forwarding, pack expansions in lambda expressions, lambda expressions & STL algorithms, recursive lambda, lambda expressions in member functions, lambda expressions for functional programming, template parameter lists on lambdas (C++20), new lambda captures (C++20), lambda expressions in unevaluated context - C++20, lambda init capture pack expansions (C++20), default constructible and assignable stateless lambdas (C++20).

## advanced exception handling
exception guarantees, basic guarantee, strong guarantee, no throw guarantee, special member functions & noexcept, noexcept specifier vs. noexcept operator, noexcept specifier in type_traits library, std::exception_ptr, std::make_exception_ptr, std::current_exception, std::rethrow_exception, std::nested_exception, exception dispatcher idiom.

## spaceship operator(three ways comparison operator C++20)
comparison categories, strong ordering, weak ordering, partial ordering, spaceship operator in STL.

## concurrency in C++
std::thread, std::this_thread namespace, std::jthread (C++20), thread_local storage, std::async, shared objects & mutex classes, race condition & data race, 
std::lock_guard, std::unique_lock, std::scoped_lock, deadlocks, std::once_flag & std::call_once, std::future, std::promise, std::shared_future, std::packaged_task, std::condition_variable, std::atomic, thread pools, paralel STL algorithms

## type deduction
auto type deduction, decltype specifier, decltype(auto), trailing auto, auto return type, type deduction in lambda expressions.

## vocabulary types
std::optional, std::variant, std::any.

## random library
pseudo-random number generation, random number engines, random number engine adaptors, predefined random number generators, random number distributions.

## std::span

## policy based design

## strong types

## user defined literals

## uninitialized memory & algoritms

## concepts C++20
typesafe meta-programming, advantagous of concepts, usage of concepts, requires clause, trailing requires clause, constrained template parameters, concepts as function paramaters, concepts and classes, concepts & STL, building our own concepts.

## std::ranges library
ranges, standard range algorithms, sentinels, projections, range concepts, views, range adaptors, standard views, range type meta functions, non-deterministic random numbers

## std::format library
std::format, td::format_to, std::format_to_n, std::formatted_size, 

## Other C++20 novelties and library extensions
designated initializers, range-based for loop with initializer, narrowing bool conversion, using enum, new attributes, conditional explicit, std::span, bit header, math constants, std::bit_cast, std::midpoint, std::to_array, starts_with and ends_with member functions of std::string, contains member functions of associative containers, make_shared for arrays, std::is_constant_evaluated



