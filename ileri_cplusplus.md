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
