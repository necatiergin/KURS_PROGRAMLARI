# İleri C++ Kursu İçeriği

## kopyalamanın eliminasyonu (copy elision)
+ temporary materialization _(Prvalue Xvalue conversion)_
+ unmaterialized object passing
+ geri dönüş değeri optimizasyonu _(return value optimization (RVO))_
+ isimlendirilmiş geri dönüş değeri optimizasyonu _(named return value optimization (NRVO))_
+ kopyalama eliminasyonunu engelleyen durumlar
+ değerle _throw_ etmek _(throwing by value)_
+ değerle yakalamak _(catching by value)_
+ garanti edilmiş kopyalama eliminasyonu _(mandatory copy elision C++17)_

## taşıma semantiği (move semantics) 
+ sağ taraf referansları (R Value references) (hızlı tekrar)
+ taşıma semantiğinin temel nitelikleri
+ std::move
+ taşıma semantiği ve sınıfların özel üye fonksiyonları _(move semantics & special member functions)_
+ taşıma semantiğinden faydalanma biçimleri
+ referans niteleyicileri _(reference qualifiers)_
  + referans niteleyecileri ve işlev yüklemesi _(function overloading)_
  + referans niteleyicileri ve taşıma semantiği
+ taşınmış nesne durumu _(moved-from states)_
+ taşıma semantiği ve _noexcept_ belirleyicisi 
+ standart kütüphane ve taşıma semantiği _(standard library and move semantics)_
  + salt taşınabilir türler _(move only types)_
  + taşıyan algoritmalar _(moving algorithms)_
  + taşıma iteratörleri _(move iterators)_
+ tipik hatalar _(typical mistakes)_
+  temel ilkeler

## mükemmel gönderim _(perfect forwarding)_
+ forwarding reference (universal references)
+ forwarding reference ve sağ taraf referansı
+ std::forward fonksiyon şablonu
+ mükemmel gönderim ve _auto &&_ kullanımı
+ _decltype(auto)_
+ geri dönüş değerinin mükemmel gönderimi _decltype(auto)_
+ mükemmel gönderim ve standart kütüphane _(perfect forwarding & standard library)_

## sabitler ve sabit ifadeleri C++11/14/17/20
+ constexpr
+ constexpr işlevler _(constexpr functions)_
+ constexpr kurucu işlevler _(constexpr constructors)_
+ literal types
+ consteval & immediate functions(C++20)
+ constinit (C++20)
+ constexpr sanal işlevler C++20 _(constexpr virtual functions C++20)_
+ constexpr lambda functions
+ user defined literals

## şablonlar ve türden bağımsız programlama - İleri (templates & generic programming - advanced)
+ temel kavramların kısa tekrarı
  + fonksiyon şablonları (function templates)
  + sınıf şablonları (class templates)
  + değişken şablonları (variable templates )
  + tür eş isim şablonları (alias templates )
  + member templates
  + template parameters
    + type parameters
    + non-type parameters
    + template parameters
  + function templates & overloading
  + explicit specialization
  + partial specialization
  + template instantiation
  + template arguments
  + template argument deduction
+ dependent & non-dependent names
+ templates & friendship
+ auto parameter type (C++17)
+ CTAD (class template argument deduction)
+ meta fonksiyonlar (meta functions)
  + tür elde eden meta fonksiyonlar
  + değer elde eden meta fonksiyonlar
+ type traits kütüphanesi
+ static_assert ve şablonlar
+ std::type_identity
+ tag dispatch
+ if constexpr (C++17)
+ variadic şablonlar _(variadic templates)_
  + sizeof... operatörü
  + pack expansions
+ katlama ifadeleri C++17 _(fold expressions C++17)_
  + unary right fold
  + unary left fold
  + binary right fold
  + binary left fold
+ sfinae
+ enable_if
+ void_t
+ declval
+ std::invoke
+ std::apply
+ C++20 eklemeleri 
    + string literals template parameters (C++20)
    + typename anahtar sözcüğünün kullanılma zorunluluğu olmayan durumlar (C++20)

## önemli C++ idiyomları ve teknikleri
+ RAII
+ swap functions
+ copy & swap idiom
+ scope guards
+ strong types
+ tag dispatch
+ hidden friends
+ virtual constructor
+ virtual friend
+ factories
+ proxy
+ memory ownership
+ pimpl & fast pimpl
+ attorney - client idiom
+ local buffer optimization
+ implementation class
+ non virtual interface (NVI)
+ isimlendirilmiş parametre _(named parameter)_
+ tür silme _(type erasure)_
+ IIFE _(immediatly invoked lambda expression)_
+ referans sayımı _(reference counting)_
+ positive lambda
+ exception dispatcher
+ biased dağılımı _(biased distribution)_
+ gather algoritması _(gather algorithm)_
+ slide algoritması _(slide algorithm)_

## lambda İfadeleri C++11/14/17/20 
+ lambda ifadeleri ve tür çıkarımı
+ mutable lambdas
+ lambda ifadeleri ve constexpr 
+ genelleştirilmiş lambda ifadeleri _(generalized lambda expressions)_
+ lambda init capture
+ lambda ifadeleri ve mükemmel gönderim
+ lambda ifadelerinde _pack expansion_
+ lambda ifadeleri ve STL algoritmaları
+ recursive lambdalar
+ üye fonksiyonlar içinde lambda ifadelerinin kullanımı
+ lambda ifadeleri ve fonksiyonel programlama
+ C++20 extensions
	+ template parameter lists on lambdas (C++20)
	+ \[=, this] as a lambda capture (C++20)
	+ işlem kodu üretilmeyen bağlamlardaki lambda ifadeleri C++20 _(lambda expressions in unevaluated context - C++20)_
	+ lambda init capture pack expansions (C++20)
	+ default constructible and assignable stateless lambdas (C++20)

