# Advanced C++

## kopyalama eliminasyonu (copy elision) (4 saat)
Kopyalama eliminasyonu çok iyi hakim olmamız gereken bir konu. Bu bölümde _kopyalama eliminasyonunu_ önce temel düzeyde tekrar edecek daha sonra kopyalama eliminasyonuna yönelik tipik durumları ayrıntılı olarak ele alacağız. C++17 Standardı ile dile eklenen _"mandatory copy elision"_ ve _copy elision_'ı engelleyen senaryolara da değineceğiz. Tipik yapılan hataları ve yanlış anlamaları _(misconceptions)_ konuşacağız. 
_(temporary materialization, prvalue xvalue conversion, unmaterialized object passing, return value optimization (rvo), named return value optimization (nrvo), scenarios blocking copy elision, throwing by value, catching by value, mandatory copy elision, typical mistakes & misconceptions, guidelines)_

## taşıma semantiği (move semantics) (16 saat)
Taşıma semantiği Modern C++'ın öne çıkardığı çok önemli bir konu. Bu bölümde taşıma semantiğini önce temel düzeyde tekrar edecek sonra ileri düzey bilgiler edineceğiz. _(basic features of move semantics, std::move, move semantics & special member functions,  how to use move semantics, referans qualifiers & move semantics, moved-from state,  move semantics & exception guarantees, move semantics in STL, move only types, STL moving algorithms, typical mistakes & misconceptions, guidelines)_

## tür çıkarımı (type deduction) (8 saat)
Bu bölümde Modern C++'ın tüm araçlarına nüfuz etmiş olan tür çıkarımı konusunu ileri düzeyde ele alacağız. 
_(auto type deduction, decltype specifier, decltype(auto), trailing return type, auto return type, type deduction in lambda expressions) _

