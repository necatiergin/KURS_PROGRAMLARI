# Advanced C++

## kopyalama eliminasyonu (copy elision)
Kopyalama eliminasyonu çok iyi hakim olmamız gereken bir konu. Bu bölümde _kopyalama eliminasyonunu_ önce temel düzeyde tekrar edecek daha sonra kopyalama eliminasyonuna yönelik tipik durumları ayrıntılı olarak ele alacağız. _C++17_ Standardı ile dile eklenen _"mandatory copy elision"_ ve 
_copy elision_'ı engelleyen senaryolara da değineceğiz. Tipik yapılan hataları ve yanlış anlamaları _(misconceptions)_ konuşacağız. <br><br>
_temporary materialization_, 
_prvalue xvalue conversion_, 
_unmaterialized object passing_, 
_return value optimization (rvo)_, 
_named return value optimization (nrvo)_, 
_scenarios blocking copy elision_, 
_throwing by value_, 
_catching by value_, 
_mandatory copy elision_, 
_typical mistakes & misconceptions, guidelines_

## taşıma semantiği (move semantics)
Taşıma semantiği Modern C++'a güç katan en önemli yapılardan biri. Bu bölümde taşıma semantiğini önce temel düzeyde tekrar edecek sonra ileri düzey bilgiler edineceğiz. Bu konuda yapılan tipik hataları ve kullanılan idiyomatik yapıları da ele alacağız. <br><br> 
_basic features of move semantics_,
_std::move_, 
_move semantics & special member functions_, _how to use move semantics_, _reference qualifiers & move semantics_, _moved-from state_,  _move semantics & exception guarantees_, _move semantics in STL_, _move only types_, _STL moving algorithms_, _typical mistakes & misconceptions_, _guidelines_

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
_template terminology_, 
_function templates_,  
_class templates_, 
_variable templates_, 
_alias templates_, 
_member templates_, 
_template parameters_, 
_type parameters_, 
_non-type parameters_, 
_auto non-type parameters_, 
_template template parameters_, 
_function templates & overloading_, 
_explicit specialization_, 
_partial specialization_, 
_template instantiation_, 
_template arguments_, 
_template argument deduction_, 
_dependent & non-dependent names_, templates & friendship, ctad , 
_meta functions and standard type_traits library_, 
_static_assert declarations_,
_std::type_identity_, 
_tag dispatch_, 
_if constexpr (static if)_, 
_variadic templates, 
_sizeof... operator_, 
_pack expansion patterns_, 
_fold expressions_
_unary_fold_,
_binary_fold_
_sfinae_, 
_std::enable_if_, 
_std::void_t_, 
_std::declval_, 
_C++20/23 additions_

## mükemmel gönderim (perfect forwarding)
Modern _C++_'ın kazandırdığı en önemli araçlardan biri _"perfect forwarding"_. Bu bölümde _"perfect forwarding"_ tüm yönleriyle ele alnacak. <br> <br>
_forwarding (universal) references, forwarding reference vs R value reference, std::forward, auto && for perfect forwarding, decltype(auto) and perfect forwarding, perfect forwarding of return values, perfect forwarding in STL, typical mistakes & misconceptions, guidelines._

## concepts (C++20)
_concept'ler_ _C++20_ standardı ile dile eklenen en önemli araçlardan biri. _Concept_'ler ile türden bağımsız programlama, daha kolay ve daha güvenli olarak gerçekleştirilebiliyor. Bu başlık altında _concept_'lere yönelik özellikleri ve standart kütüphane öğelerini ayrıntılı olarak ele alacağız.<br><br>
_constraints, requires clauses, requires expressions, type requirements, compound requirements, nested requirements, concepts, type constraints and auto, standard concepts_ 

## olağan dışı durumların işlenmesi (advanced exception handling)
Bu başlık altında _"exception handling"_ konusunda temel kursta ele almadığımız bazı ileri konuları inceleyecek _(exception handling)_ konusunda daha derin bir bakış açısına sahip olacağız. _Exception handling'e_ ilişkin kullanılan teknikleri ve idiyomları da öğreneceğiz. _exception handling_ konusunda bilmediğimiz hiçbir şey kalmayacak.<br><br>
_exception guarantees in details, noexcept specifier, noexcept operator, when to throw when to catch, what to throw what to catch, std::exception_ptr, std::nested_exception, std::rethrow_exception_, _polymorphic_exception_, _exception_dispatcher_

## lambda ifadeleri (lambda expressions C++11/14/17/20/23)
Modern _C++'_ın olmazsa olmaz araçlarından biri de _lambda_ ifadeleri. Bu konu başlığı altında lambda ifadelerine ilişkin bilmediğimiz hiçbir şey kalmayacak. C++ dilinin her yeni standardıyla lambda ifadelerinin kapsamı genişledi, yeni yeni özellikler, araçlar eklendi. Önce temel düzeyde hızlı bir tekrar yapacak daha sonra ileri düzeyde bilgiler edineceğiz. Lambda ifadelerine ilişkin kullanılan idiyomları ve teknikleri de ayrıntılı olarak ele alacağız.<br>
_lambda expressions and type deductions_, 
_lambda expressions & constexpr_, 
_generalized lambda expressions_, 
_lambda init capture_, 
_lambda expressions & perfect forwarding_, 
_pack expansions in lambda expressions_, 
_lambda expressions & STL algorithms_, 
_recursive lambda_, 
_lambda expressions in member functions_, 
_lambda expressions for functional programming_, 
_lambda expressions in C++20/23_, 
_template parameter lists on lambdas (C++20)_, 
_new lambda captures (C++20)_, 
_lambda expressions in unevaluated context - C++20_, 
_lambda init capture pack expansions (C++20, 
_default constructible and assignable stateless lambdas (C++20)_, 
_multiple lambda_, 
_IIFE_, 
_lambda call once_, 
_type distinction through lambda_.

## spaceship operator (C++20) 
_C++20_ ile eklenen önemli araçlardan biri. Artık bu operatör ile karşılaştrıma işlemleri çok daha kolay.<br><br>
_comparison categories, strong ordering, weak ordering, partial ordering, spaceship operator in STL._

## std::format (C++20)
_C++20_ Standardı ile dile eklenen _std::format_ kütüphanesini detaylı olarak öğreneceğiz. Artık formatlı çıkış işlemleri daha hızlı, daha esnek ve daha kolay.<br><br>
_std::format, td::format_to, std::format_to_n, std::formatted_size_, std::print

## C++ idioms and techniques
Bu bölümde üretimde sık kullanılan C++ idiyomlarını ve tekniklerini mercek altına alacağız. Bazı konu başlıklarımız şunlar olacak: <br><br>
_ADL + fallback_, 
_attorney - client_, 
_biased distribution (std::discrete_distribution_), 
_clamp_,
_construction_tracker_
_copy & swap idiom_, 
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

## derleyici optimizasyonları (compiler optimizations)
Bu bölümde tipik bir C++ derleyicisinin kullandığı optimizasyon teknikleri üstünde duracağız.<br><br>
_automatic vectorization_, 
_common subexpression elimination (CSE)_, 
_constant folding_, 
_constant propagation_, 
_dead code elimination_, 
_function inlining_, 
_interprocedural analysis and optimization_       
_loop-invariant dode motion_, 
_loop inversion_, 
_loop unrolling_, 
_memory to register promotion_, _procedure integration_, 
_register allocation_                                                        

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
