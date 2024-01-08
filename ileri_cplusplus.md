# Advanced C++

## kopyalama eliminasyonu (copy elision)
Kopyalama eliminasyonu çok iyi hakim olmamız gereken bir konu. Bu bölümde _kopyalama eliminasyonunu_ önce temel düzeyde tekrar edecek daha sonra kopyalama eliminasyonuna yönelik tipik durumları ayrıntılı olarak ele alacağız. _C++17_ Standardı ile dile eklenen _"mandatory copy elision"_ ve 
_copy elision_'ı engelleyen senaryolara da değineceğiz. Tipik yapılan hataları ve yanlış anlamaları _(misconceptions)_ konuşacağız. <br><br>
_temporary materialization, prvalue xvalue conversion, unmaterialized object passing, return value optimization (rvo), named return value optimization (nrvo), scenarios blocking copy elision, throwing by value, catching by value, mandatory copy elision, typical mistakes & misconceptions, guidelines_

## taşıma semantiği (move semantics)
Taşıma semantiği Modern C++'a güç katan en önemli yapılardan biri. Bu bölümde taşıma semantiğini önce temel düzeyde tekrar edecek sonra ileri düzey bilgiler edineceğiz. Bu konuda yapılan tipik hataları ve kullanılan idiyomatik yapıları da ele alacağız. <br><br> 
_basic features of move semantics, std::move, move semantics & special member functions,  how to use move semantics, reference qualifiers & move semantics, moved-from state,  move semantics & exception guarantees, move semantics in STL, move only types, STL moving algorithms, typical mistakes & misconceptions, guidelines_

## tür çıkarımı (type deduction)
Bu bölümde Modern C++'ın neredeyse tüm araçlarına nüfuz etmiş olan tür çıkarımı konusunu ileri düzeyde ele alacağız. <br> 
_auto type deduction, decltype specifier, decltype(auto), trailing return type, auto return type, type deduction in lambda expressions_

## sabit ifadeleri (constant expressions)
C++ diline güç katan en temel araçlardan biri sabit ifadeleri ve derleme zamanında yapılan hesaplamalar. Bu bölümde bu konuya yönelik bazı araçları ileri düzeyde ele alacağız. _C++20 ve C++23_ standartları ile dile yapılan eklemeleri de inceleyeceğiz.<br><br>
_constexpr variables, constexpr functions, constexpr constructors, literal types, consteval & immediate functions, constinit, constexpr virtual functions, constexpr lambda functions, user defined literals_

## (advance) namespaces
Bu bölümde isim alanlarını ileri düzeyde inceleyeceğiz. İsim alanları konusunda _C++17/20/23_ standartları ile gelen önemli eklentileri ve bunların sağladığı faydaları ele alacağız.

## türden bağımsız programlama (generic programming)
Bu bölümde C++ dilinin türden bağımsız programlama _(generic programming)_ araçları kapsamlı bir şekilde ve ileri düzeyde ele alacağız. Önce temel kursta öğrendiğimiz araçları hızlı bir şekilde tekrar edecek sonra ileri düzey araçları, yeni standartlarla gelen eklentileri ve bazı önemli teknikleri ve idiyomları öğreneceğiz. C++20 standartları ile gelen eklemeler de konu başlıklarımız arasında olacak<br><br>
_template terminology, function templates,  class templates, variable templates, alias templates, member templates, template parameters, type parameters, non-type parameters, auto non-type parameters, template template parameters, function templates & overloading, explicit specialization, partial specialization, template instantiation, template arguments, template argument deduction, dependent & non-dependent names, templates & friendship, ctad , meta functions and standard type_traits library, static_assert declarations & templates, std::type_identity, tag dispatch, if constexpr (static if), variadic templates, sizeof... operator, pack expansion patterns, fold expressions, sfinae, std::enable_if, std::void_t, std::declval, C++20 additions_

## mükemmel gönderim (perfect forwarding)
Modern _C++_'ın kazandırdığı en önemli araçlardan biri _"perfect forwarding"_. Bu bölümde _"perfect forwarding"_ tüm yönleriyle ele alnacak. <br> <br>
_forwarding (universal) references, forwarding reference vs R value reference, std::forward, auto && for perfect forwarding, decltype(auto) and perfect forwarding, perfect forwarding of return values, perfect forwarding in STL, typical mistakes & misconceptions, guidelines._

## concepts (C++20)
_concept'ler_ _C++20_ standardı ile dile eklenen en önemli araçlardan biri. _Concept_'ler ile türden bağımsız programlama, daha kolay ve daha güvenli olarak gerçekleştirilebiliyor. Bu başlık altında _concept_'lere yönelik özellikleri ve standart kütüphane öğelerini ayrıntılı olarak ele alacağız.<br><br>
_constraints, requires clauses, requires expressions, type requirements, compound requirements, nested requirements, concepts, type constraints and auto, standard concepts_ 

## olağan dışı durumların işlenmesi (advanced exception handling)
Bu başlık altında _"exception handling"_ konusunda temel kursta ele almadığımız bazı ileri konuları inceleyecek _(exception handling)_ konusunda daha derin bir bakış açısına sahip olacağız. _Exception handling'e_ ilişkin kullanılan teknikleri ve idiyomları da öğreneceğiz. _exception handling_ konusunda bilmediğimiz hiçbir şey kalmayacak.<br><br>
_exception guarantees in details, noexcept specifier, noexcept operator, when to throw when to catch, what to throw what to catch, std::exception_ptr, std::nested_exception, std::rethrow_exception_

## lambda ifadeleri (lambda expressions C++11/14/17/20/23)
Modern _C++'_ın olmazsa olmaz araçlarından biri de _lambda_ ifadeleri. Bu konu başlığı altında lambda ifadelerine ilişkin bilmediğimiz hiçbir şey kalmayacak. C++ dilinin her yeni standardıyla lambda ifadelerinin kapsamı genişledi, yeni yeni özellikler, araçlar eklendi. Önce temel düzeyde hızlı bir tekrar yapacak daha sonra ileri düzeyde bilgiler edineceğiz. Lambda ifadelerine ilişkin kullanılan idiyomları ve teknikleri de ayrıntılı olarak ele alacağız.
_lambda expressions and type deductions, lambda expressions & constexpr, generalized lambda expressions, lambda init capture, lambda expressions & perfect forwarding, pack expansions in lambda expressions, lambda expressions & STL algorithms, recursive lambda, lambda expressions in member functions, lambda expressions for functional programming, lambda expressions in C++20/23, template parameter lists on lambdas (C++20), new lambda captures (C++20), lambda expressions in unevaluated context - C++20, lambda init capture pack expansions (C++20), default constructible and assignable stateless lambdas (C++20), multiple lambda, IIFE, lambda call once, type distinction through lambda.

## spaceship operator (C++20) 
_C++20_ ile eklenen önemli araçlardan biri. Artık bu operatör ile karşılaştrıma işlemleri çok daha kolay.<br><br>
_comparison categories, strong ordering, weak ordering, partial ordering, spaceship operator in STL._

## std::format (C++20)
_C++20_ Standardı ile dile eklenen _std::format_ kütüphanesini detaylı olarak öğreneceğiz. Artık formatlı çıkış işlemleri daha hızlı, daha esnek ve daha kolay.<br><br>
_std::format, td::format_to, std::format_to_n, std::formatted_size_, std::print

## C++ idioms and techniques
Bu bölümde üretimde sık kullanılan C++ idiyomlarını ve tekniklerini mercek altına alacağız. Bazı konu başlıklarımız şunlar olacak: <br><br>
_RAII_, swap functions, copy & swap idiom, scope guards, strong types, tag dispatch, hidden friends, ADL + fallback, virtual constructor, virtual friend,
factories, proxy, memory ownership, pimpl & fast pimpl, attorney - client, local buffer optimization, implementation class, non virtual interface (NVI), isimlendirilmiş parametre (named parameter), tür silme _(type erasure)_, IIFE (immediatly invoked lambda expression), referans sayımı (reference counting), positive lambda, exception dispatcher, biased dağılımı (biased distribution), _gather_ algorithm, _slide_ algorithm.

## derleyici optimizasyonları (compiler optimizations)
Bu bölümde tipik bir C++ derleyicisinin gerçekleştirdiği optimizasyon faaliyetleri üstünde duracağız.<br><br>
_dead code elimination, loop unrolling, loop inversion, constant folding, constant propagation, function inlining, register allocation, Common Subexpression Elimination (CSE), common subexpression elimination (CSE), loop-invariant dode motion, automatic vectorization, memory to register promotion, procedure integration, interprocedural analysis and optimization_                                                            

## std::regex
Önce programlama dilinden bağımsız olarak _regex_ notasyonunu ayrıntılı olarak ve örneklerle ele alacağız. Daha sonra _std::regex_ kütüphanesini öğreneceğiz.

## std::ranges (C++20)
_C++20_ standardı ile dile eklenen _std::ranges_ kütüphanesi standart kütüphanemizin en önemli öğelerinden biri haline geldi. STL'de değişti, yenilendi. STL2.0'ı ayrıntılı olarak ele alacağız.

## coroutines (C++20)
_C++20_ Standardı ile dile eklenen ve _C++23_ Standardı ile yapılan eklemeler ile daha güçlü hale gelen _coroutin_'leri detaylı olarak ele alacağız.

## yeni kütüphane öğeleri (new library components)
Bu bölümde _C++17, C++20, C++23_ standartları ile dile eklenen önemli kütüphane öğelerine odaklanacağız.<br><br>
std::string_view, _std::optional, std::variant, std::any, file_system_library, std::span (C++20), std::expected(C++23), std::mdspan(C++23), std::print(C++23), std::flat_set (C++23), std::flat_map(C++23)_
 
## concurrency in C++
Bu bölümde Modern C++ ile dile eklenen yeni bellek modeli ve _concurrency_ kütüphanesini detaylı olarak ele alacağız. <br><br>
std::thread, std::this_thread namespace, std::jthread (C++20), thread_local storage, std::async, shared objects & mutex classes, race condition & data race, 
std::lock_guard, std::unique_lock, std::scoped_lock, deadlocks, std::once_flag & std::call_once, std::future, std::promise, std::shared_future, std::packaged_task, std::condition_variable, std::atomic, thread pools, std::counting_semaphore, paralel STL algorithms, concurrency idioms. 
