## Kurs içeriği yeniden düzenleniyor. Yakında tamamlanacak...

# İleri C++ Kursu İçeriği

## copy elision
+ temporary materialization, prvalue xvalue conversion, unmaterialized object passing, return value optimization (RVO), named return value optimization (NRVO), blocking copy elision, throwing by value, catching by value, mandatory copy elision.

## move semantics 
R Value references (brush up), taşıma semantiğinin temel nitelikleri, std::move, move semantics & special member functions, taşıma semantiğinden faydalanma biçimleri, 
referans qualifiers & move semantics, moved-from states, move semantics & exception guarantees 
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

## advanced exception handling
+ _exception_ garanti kategorileri
  + temel hata güvencesi _(basic guarantee)_
  + güçlü hata güvencesi _(strong guarantee)_
  + hata göndermeme güvencesi _(no throw guarantee)_
  + sınıfların özel fonksiyonları ve noexcept
+ noexcept belirleyicisi _(noexcept specifier)_
+ noexcept operatörü _(noexcept operator)_
+ noexcept belirleyicisi ve standart type_traits kütüphanesi
+ _exception\_ptr_ türü
+ _make\_exception_ptr_ fonksiyonu
+ _current\_exception_ fonksiyonu
+ _rethrow\_exception_ fonksiyonu
+ _std::nested\_exception_ sınıfı
+ exception dispatcher idiom

## üç yollu karşılaştırma (spaceship) operatörü - C++20 (three ways comparison operator C++20)
+ karşılaştırma kategorileri
  + strong ordering
  + weak ordering
  + partial ordering
+ Standart kütüphane ve _(spaceship)_ operatörü

## tür çıkarımı (type deduction)
+ _auto_ ile tür çıkarımı _(auto type deduction)_
+ _decltype_ belirleyicisi _(decltype specifier)_
+ _decltype(auto)_ belirleyicisi
+ _auto_ geri dönüş türü _(auto return type)_
+ lambda ifadelerinde tür çıkarımı _(type deduction in lambda expressions)_

## concepts C++20
+ typesafe meta-programming
+ _concept_ nedir? Ne işe yarar?
+ _concept_ kullanımının avantajları
+ _concept_'leri kullanmanın farklı biçimleri
  + requires clause
  + trailing requires clause
  + constrained template parameter
  + concept fonsiyon parametreleri
+ _concept_'ler ve sınıflar
+ _concept_'ler ve standart kütüphane
+ kendi _concept_'lerimizi oluşturmak
+ multiple destructors

## std::ranges kütüphanesi C++20
+ ranges
+ standard range algorithms
+ sentinels
+ projections
+ range concepts
+ views
+ range adaptors
+ standard views
+ range type meta functions

## std::format C++20
+ std::format
+ std::format_to
+ std::format_to_n
+ std::formatted_size

## C++20 diğer yenilikler
+ designated initializers
+ range-based for loop with initializer
+ narrowing bool conversion
+ using enum
+ yeni attribute'lar
+ conditional explicit

## C++20 standart kütüphane eklentileri (C++20 std. library extensions)
+ std::span
+ bit header
+ math constants
+ std::bit_cast
+ std::midpoint
+ std::to_array
+ string sınıfının starts_with ve ends_with işlevleri
+ associative containers contains işlevleri
+ make_shared for arrays
+ std::is_constant_evaluated
