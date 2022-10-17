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

## lambda İfadeleri C++11/14/17/20 
lambda expressions & type deduction, mutable lambdas, lambda expressions & constexpr, generalized lambda expressions, lambda init capture, lambda expressions & perfect forwarding, pack expansions in lambda expressions, lambda expressions & STL algorithms, recursive lambda, lambda expressions in member functions, lambda expressions for functional programming, template parameter lists on lambdas (C++20), new lambda captures (C++20), lambda expressions in unevaluated context - C++20, lambda init capture pack expansions (C++20), default constructible and assignable stateless lambdas (C++20)

