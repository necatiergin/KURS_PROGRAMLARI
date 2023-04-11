# Advanced C++

## kopyalama eliminasyonu (copy elision) (4 saat)
Kopyalama eliminasyonu çok iyi hakim olmamız gereken bir konu. Bu bölümde _kopyalama eliminasyonunu_ önce temel düzeyde tekrar edecek daha sonra kopyalama eliminasyonuna yönelik tipik durumları ayrıntılı olarak ele alacağız. C++17 Standardı ile dile eklenen _"mandatory copy elision"_ ve _copy elision_'ı engelleyen senaryolara da değineceğiz. Tipik yapılan hataları ve yanlış anlamaları _(misconceptions)_ konuşacağız. <br>
_(temporary materialization, prvalue xvalue conversion, unmaterialized object passing, return value optimization (rvo), named return value optimization (nrvo), scenarios blocking copy elision, throwing by value, catching by value, mandatory copy elision, typical mistakes & misconceptions, guidelines)_

## taşıma semantiği (move semantics) (16 saat)
Taşıma semantiği Modern C++'ın öne çıkardığı çok önemli bir konu. Bu bölümde taşıma semantiğini önce temel düzeyde tekrar edecek sonra ileri düzey bilgiler edineceğiz.<br>
_(basic features of move semantics, std::move, move semantics & special member functions,  how to use move semantics, referans qualifiers & move semantics, moved-from state,  move semantics & exception guarantees, move semantics in STL, move only types, STL moving algorithms, typical mistakes & misconceptions, guidelines)_

## tür çıkarımı (type deduction) (8 saat)
Bu bölümde Modern C++'ın neredeyse tüm araçlarına nüfuz etmiş olan tür çıkarımı konusunu ileri düzeyde ele alacağız. <br> 
_(auto type deduction, decltype specifier, decltype(auto), trailing return type, auto return type, type deduction in lambda expressions)_

## sabit ifadeleri (constant expressions) (8 saat)
C++ diline güç katan en temel araçlardan biri sabit ifadeleri ve derleme zamanında yapılan hesaplamalar. Bu bölümde bu konuya yönelik bazı araçları ileri düzeyde ele alacağız. <br>
_(constexpr variables, constexpr functions, constexpr constructors, literal types, consteval & immediate functions, constinit, constexpr virtual functions, constexpr lambda functions, user defined literals)_

## türden bağımsız programlama (generic programming) (24 saat)
Bu bölümde C++ dilinin türden bağımsız programlama araçları kapsamlı bir şekilde ve ileri düzeyde ele alacağız. Önce temel kursta öğrendiğimiz araçları hızlı bir şekilde tekrar edecek sonra ileri düzey araçları, yenilikleri ve teknikleri öğreneceğiz.<br>
_(template terminology, function templates,  class templates, variable templates, alias templates, member templates, template parameters, type parameters, non-type parameters, auto non-type parameters, template template parameters, function templates & overloading, explicit specialization, partial specialization, template instantiation, template arguments, template argument deduction, dependent & non-dependent names, templates & friendship, ctad , meta functions and standard type_traits library, static_assert declarations & templates, std::type_identity, tag dispatch, if constexpr (static if), variadic templates, sizeof... operator, pack expansion patterns, fold expressions, sfinae, std::enable_if, std::void_t, std::declval, C++20 additions_

## mükemmel gönderim (perfect forwarding) (8 saat)
Modern C++'ın kazandırdığı en önemli araçlardan biri _"perfect forwarding"_. Bu bölümde "perfect forwarding" tüm yönleriyle ele alnacak. <br> 
_(forwarding (universal) references, forwarding reference vs R value reference, std::forward, auto && for perfect forwarding, decltype(auto) & perfect forwarding, perfect forwarding of return values, perfect forwarding in STL, typical mistakes & misconceptions, guidelines.)_

## olağan dışı durumların işlenmesi (advanced exception handling) (3 saat)
Bu başlık altında _"exception handling"_ konusunda temel kursta ele almadığımız bazı ileri konuları inceleyecek _(exception handling)_ konusunda daha derin bir bakış açısına sahip olacağız.

## lambda ifadeleri (lambda expressions C++11/14/17/20/23) (10 saat)
Modern C++'ın en önemli araçlarından biri de _lambda_ ifadeleri. Bu konu başlığı altında lambda ifadelerine ilişkin bilmediğimiz hiçbir şey kalmayacak. C++ dilinin her yeni standardıyla lambda ifadelerinin kapsamı genişledi, yeni yeni özellikler, araçlar eklendi. Önce temel düzeyde hızlı bir tekrar yapacak daha sonra ileri düzeyde bilgiler edineceğiz.<br> 
_(lambda expressions and type deductions, lambda expressions & constexpr, generalized lambda expressions, lambda init capture, lambda expressions & perfect forwarding, pack expansions in lambda expressions, lambda expressions & STL algorithms, recursive lambda, lambda expressions in member functions, lambda expressions for functional programming, lambda expressions in C++20/23, template parameter lists on lambdas (C++20), new lambda captures (C++20), lambda expressions in unevaluated context - C++20, lambda init capture pack expansions (C++20), default constructible and assignable stateless lambdas (C++20), lambda idioms.)_

## spaceship operator (C++20) (3 saat)
C++ 20 ile eklenen önemli araçlardan biri. Artık bu operatör ile karşılaştrıma işlemleri çok daha kolay.<br>
_(comparison categories, strong ordering, weak ordering, partial ordering, spaceship operator in STL.)_

## std::format (4 saat)
C++20 Standardı ile dile eklenen _std::format_ kütüphanesini detaylı olarak öğreneceğiz. Artık formatlı çıkış işlemleri daha hızlı, daha esnek ve daha kolay.
_(std::format, td::format_to, std::format_to_n, std::formatted_size)_

## C++ idioms and techniques (20 saat)
Bu bölümde üretimde sık kullanılan C++ idiyomlarını ve tekniklerini mercek altına alacağız. Bazı konu başlıklarımız şunlar olacak: <br>

## std::ranges (12 saat)
C++20 standardı ile dile eklenen std::ranges kütüphanesi standart kütüphanemizin en önemli öğelerinden biri haline geldi. STL'de değişti, yenilendi. STL2.0'ı öğreneceğiz.

## coroutines (C++20) (10 saat)

## Yeni kütüphane öğeleri (New library components) (20 saat)
Bu bölümde _C++17, C++20, C++23_ standartları ile dile eklenen önemli kütüphane öğelerine odaklanacağız.
 
## Concurrency in C++ (20 saat)
Bu bölümde Modern C++ ile dile eklenen yeni bellek modeli ve _concurrency_ kütüpanesini ele alacağız.

