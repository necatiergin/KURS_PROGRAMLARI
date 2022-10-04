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
+ sağ taraf referansları(R Value references) (hızlı tekrar)
+ taşıma semantiğinin temel nitelikleri
+ std::move
+ taşıma semantiği ve sınıfların özel üye fonksiyonları _(move semantics & special member functions)_
+ taşıma semantiğinden faydalanma biçimleri
+ referans niteleyicileri _(reference qualifiers)
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
