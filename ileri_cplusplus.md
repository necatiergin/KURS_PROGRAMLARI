# Advanced C++

## copy elision
- temporary materialization 
- prvalue xvalue conversion
- unmaterialized object passing 
- return value optimization (rvo) & named return value optimization (nrvo)
- scenarios blocking copy elision 
- throwing by value 
- catching by value
- mandatory copy elision
- typical mistakes & misconceptions, guidelines

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
- auto return type _type deduction in lambda expressions 
- type deductions in function & class templates

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
- lambda expressions in C++20/23
- template parameter lists on lambdas (C++20)
- new lambda captures (C++20)
- lambda expressions in unevaluated context - C++20 
- lambda init capture pack expansions (C++20, 
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
- ctad
- meta functions and standard type_traits library 
- static_assert declarations
- std::type_identity 
- tag dispatch 
- if constexpr (static if) 
- variadic templates 
- sizeof... operator 
- pack expansion patterns 
- fold expressions
- unary_fold
- binary_fold
- sfinae 
- std::enable_if 
- std::void_t 
- std::declval 
- C++20/23 additions


## concepts (C++20)
_constraints_, _requires clauses_, _requires expressions_, _type requirements_, _compound requirements_, _nested requirements_, _concepts_, _type constraints and auto_, _standard concepts_ 

## exception handling (advanced level)
_exception guarantees in details, noexcept specifier, noexcept operator, when to throw when to catch, what to throw what to catch, std::exception_ptr, std::nested_exception, std::rethrow_exception_, _polymorphic_exception_, _exception_dispatcher_

.

## spaceship operator (C++20) 
_comparison categories_, _strong ordering_, _weak ordering_, _partial ordering_, _spaceship operator in STL._

## std::format (C++20)
_std::format_, 
_std::format_to_, 
_std::format_to_n_, 
_std::formatted_size_, 
_std::print_

## C++ idioms and techniques
_ADL + fallback_, 
_attorney - client_, 
_biased distribution (std::discrete_distribution_), 
_clamp_,
_construction_tracker_
_copy & swap idiom_, 
_container idioms_, 
_exception dispatcher_, 
_factories_, 
_gather algorithm_, 
_guarded_suspension_, 
_hidden friends_, 
_IIFE (immediatly invoked lambda expression)_, 
_implementation class_, 
_local buffer optimization_, 
_memory ownership_, 
_mixin classes_, 
_named parameter_, 
_nifty_counter_,
_non virtual interface (NVI)_,
_pimpl & fast pimpl_, 
_positive lambda_, 
_propagate_const_, 
_proxy_, 
_raii_, 
_scope guards_, 
_reference counting_, 
_return_type_resolver_,
_scope_guard_
_slide algorithm_.
_strong types_, 
_swap functions_, 
_tag dispatch_, 
_thread_safe_interface_,
_type erasure_, 
_variant_overloader_,
_virtual constructor_, 
_virtual friend_

<!---
## compiler optimizations
_automatic vectorization_, _common subexpression elimination (CSE)_, _constant folding_, _constant propagation_, _dead code elimination_, _function inlining_, _interprocedural analysis and optimization_, _loop-invariant dode motion_, _loop inversion_, _loop unrolling_, _memory to register promotion_, _procedure integration_, _register allocation_      
--->                                                  
## std::regex
_regex grammer_, _std::basic_regex_, _std::sub_match_, _std::match_results_, _regex_match_, _regex_search_, _regex_replace_, _std::regex_iterator_, _std::regex_token_iterator_

## std::ranges (C++20)
_basics_, _range access_, _range primitives_, _range concepts_, _range_factories_, _range adaptors_

## coroutines (C++20)
_basics_, promise_type, awaitables and awaiters, _co_await_, _co_yield_, _co_return_, _promise_, _generators_, tasks, cooperative multitasking.

## new library components
_std::string_view_, 
_std::optional_, 
_std::variant_, 
_std::any_, 
_file_system_library_, 
_std::span (C++20)_, 
_std::expected(C++23)_, 
_std::mdspan(C++23)_, 
_std::print(C++23)_, 
_std::flat_set (C++23)_, 
_std::flat_map(C++23)_
 
## concurrency in C++
_std::thread_, 
_std::this_thread namespace_, 
_std::jthread (C++20)_, 
_std::stop_token_, 
_thread_local storage_, 
_std::async_, 
_mutex classes_, 
_race condition_ & data race, 
_std::lock_guard_, 
_std::unique_lock_, 
_std::scoped_lock_, 
_deadlocks_, 
_std::once_flag & std::call_once_, 
_std::future_, 
_std::promise_, 
_std::shared_future_, 
_std::packaged_task_, 
_std::condition_variable_, 
_std::atomic_, 
_thread pools_, 
_sequential consistency_,
_acquire release semantics_,
_std::counting_semaphore_,
_std::binary_semaphore_, 
_paralel STL algorithms_,
_concurrency idioms & techniques_. 
