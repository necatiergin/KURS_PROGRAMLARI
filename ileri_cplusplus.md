# Advanced C++

## array type
- pointer to arrays
- array references
- auto type deduction & arrays
- arrays as template arguments
- arrays and explicit specialization
- arrays and partial specialization
- array decay / no array decay
- arrays and type alias declarations

## copy elision

- temporary materialization 
- prvalue to xvalue conversion
- unmaterialized object passing 
- return value optimization (rvo) & named return value optimization (nrvo)
- scenarios blocking copy elision 
- throwing by value 
- catching by value
- mandatory copy elision
- typical mistakes & misconceptions
- guidelines

## move semantics

- basic features of move semantics
- std::move
- move semantics & special member functions
- how to use move semantics
- reference qualifiers & move semantics
- moved-from state
- move semantics & exception guarantees
- move only types
- move semantics in STL
- STL moving algorithms
- typical mistakes & misconceptions
- guidelines

## perfect forwarding

- forwarding (universal) references
- forwarding reference vs R value reference
- std::forward
- auto && for perfect forwarding
- decltype(auto) and perfect returning
- deferred perfect_returning
- perfect forwarding of return values
- perfect forwarding in STL
- typical mistakes & misconceptions
- guidelines

## type deduction (C++11/14/17/20/23)

- auto type deduction 
- decltype specifier 
- decltype(auto) 
- trailing return type
- auto return type type deduction in lambda expressions 
- type deductions in function & class templates
- deduction guides

## constants & constant expressions

- constexpr variables
- constexpr functions
- constexpr constructors
- literal types
- consteval & immediate functions
- constinit
- constexpr virtual functions
- constexpr lambda functions
- user defined literals
- C++20/23 additions

## lambda expressions C++11/14/17/20/23

- lambda expressions and type deductions
- lambda expressions & constexpr 
- generalized lambda expressions
- lambda init capture 
- lambda expressions & perfect forwarding
- pack expansions in lambda expressions 
- lambda expressions & STL algorithms 
- recursive lambda
- lambda expressions in member functions 
- lambda expressions for functional programming
- lambda expressions in (C++20/23)
- template parameter lists on lambdas (C++20)
- new lambda captures (C++20)
- lambda expressions in unevaluated context (C++20)
- lambda init capture pack expansions (C++20)
- default constructible and assignable stateless lambdas (C++20) 
- multiple lambda 
- IIFE
- lambda call once 
- type distinction through lambda

## generic programming

- template terminology 
- function templates 
- class templates 
- variable templates 
- alias templates 
- member templates 
- template parameters 
- type parameters 
- non-type parameters 
- auto non-type parameters 
- template template parameters 
- function templates & overloading 
- explicit specialization 
- partial specialization 
- template instantiation 
- template arguments 
- template argument deduction 
- dependent & non-dependent names templates & friendship
- CTAD
- meta functions and standard type_traits library 
- static_assert declarations
- std::type_identity 
- tag dispatch 
- if constexpr (static if) 
- variadic templates 
   - sizeof... operator 
   - pack expansion patterns 
   - fold expressions / unary_fold / binary_fold
- sfinae / std::enable_if / std::void_t 
- std::declval 
- C++20/23 additions

## concepts (C++20)

- constraints
- requires clauses
- requires expressions
- type requirements
- compound requirements
- nested requirements
- concepts
- type constraints and auto
- standard concepts

## exception handling (advanced level)

- exception guarantees (basic / strong / noexcept)
- noexcept specifier  
- noexcept operator
- when to throw when to catch
- what to throw what to catch
- std::exception_ptr / std::current_exception / std::rethrow_exception
- std::nested_exception
- polymorphic_exception
- exception_dispatcher

## spaceship operator (C++20) 

- comparison categories 
- strong/weak/partial ordering
- partial ordering 
- spaceship operator in STL

## std::format (C++20)

- std::format
- std::format_to 
- std::format_to_n
- std::formatted_size
- std::print (C++23)

## C++ idioms and techniques
- ADL + fallback 
- attorney - client 
- biased distribution (std::discrete_distribution)
- clamp
- construction tracker
- copy & swap idiom 
- container idioms 
- exception dispatcher 
- factories 
- gather algorithm 
- guarded suspension 
- hidden friends 
- IIFE (immediatly invoked lambda expression) 
- implementation class 
- local buffer optimization 
- memory ownership 
- mixin classes 
- named parameter 
- nifty counter
- non virtual interface (NVI)
- pimpl & fast pimpl 
- positive lambda 
- propagate const 
- proxy 
- raii 
- scope guards 
- reference counting 
- return type resolver
- scope guard
- slide algorithm
- strong types 
- swap functions 
- tag dispatch 
- threadsafe interface
- type erasure 
- variant overloader
- virtual constructor 
- virtual friend

## std::regex

- regex grammer
- std::basic_regex
- std::sub_match
- std::match_results
- regex_match
- regex_search
- regex_replace
- std::regex_iterator
- std::regex_token_iterator

## std::ranges (C++20)

- basics
- range access
- range primitives
- range concepts
- range_factories
- range adaptors

## coroutines (C++20)

- basics
- promise_type
- awaitables and awaiters
- co_await
- co_yield
- co_return
- promise
- generators
- tasks
- cooperative multitasking

## new library components

- std::string_view (C++17)
- std::optional (C++ 17)
- std::variant (C++ 17)
- std::any (C++ 17)
- std::span (C++20) 
- std::expected (C++23) 
- std::mdspan (C++23) 
- std::print(C++23) 
- std::flat_set (C++23) 
- std::flat_map (C++23)
 
## concurrency in C++

- memory model
- std::thread
- std::this_thread namespace 
- std::jthread
- std::stop_token
- thread_local storage
- race condition & data race
- standard mutex classes
- std::lock_guard
- std::unique_lock
- std::scoped_lock
- std::shared_lock
- std::condition_variable
- deadlocks
- livelocks 
- std::once_flag & std::call_once
- std::promise
- std::future, std::shared_future
- std::async
- std::packaged_task
- std::atomic
- atomic operations
- sequenced before / happens before / syncronised with
- std::atomic\<shared_ptr>
- thread pools
- sequential consistency
- acquire release semantics
- std::counting_semaphore
- std::binary_semaphore
- paralel STL algorithms
- concurrency idioms & techniques
