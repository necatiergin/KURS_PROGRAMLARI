# Online C++ Kursu İçeriği

## C++ Dilinin Genel Tanıtımı
+ C++ dilinin tarihçesi
+ C++ dili ve programlama paradigmaları
+ C++ dili standartları
+ C++98 – 03
+ C++11
+ C++14
+ C++17
+ C++20
+ eski C++ ve modern C++

## C Dili ve C++ İçindeki C Dili _(C in C++)_
+ C dilinden C++ diline geçiş
+ işlev bildirimleri ve tanımlamalarına ilişkin farklılıklar
+ türlere ve tür dönüşümlerine ilişkin farklılıklar
+ C’de geçerli C++’da geçersiz durumlar
+ C99 ve C++

## Temel Kavramlar _(Basic Concepts)_
+ tamamlanmış ve eksik türler `(complete & incomplete types)`
+ tek tanımlama kuralı `(one definition rule)`
+ ifadelerin değer kategorileri `(value categories)`
+ tanımsız davranış `(undefined behavior)`
+ derleyiciye bağlı davranışlar. `(implementation defined & implementaion specified)`
+ derleyici eklentileri `(compiler extensions)`
+ kapsam `(scope)` ve isim arama `(name lookup)`
+ erişim kontrolü `(access control)`
+ çift anlamlılık hatası `(ambiguity)`

## İlk Değer Verme _(Initialization)_
+ eş biçimli ilk değer verme `(uniform initialization)`
  + daraltıcı dönüşümler `(narrowing conversions)`
  + `most vexing parse`
+ doğrudan ilk değer verme `(direct intialization)`
+ değerle başlatma `value initialization`
+ kopyalama ile ilk değer verme `(copy initialization)`
+ varsayılan ilk değer verme `(default initialization)`
+ bileşiklere ilk değer verme `(aggregate initialization)`

## Tür Çıkarımı _(Type Deduction)_
+ auto belirteci ile tür çıkarımı `(auto type deduction)`
+ decltype belirteci ile tür çıkarımı `(decltype type deduction)`
+ sonradan gelen geri dönüş türü `(trailing  return type)`
+ auto geri dönüş değeri türü `(auto return type)`

## enum Sınıfları _(enum Classes)_
+ geleneksel enum türleri `(conventional enum types)`
+ baz tür seçimi `(underlying type)'
+ tür dönüşümleri `(type conversions)`
+ enum sınıfları ve kapsam `(enum classes & scope)`

## Sabit İfadeleri _(Constant Expressions)_
+ const anahtar sözcüğü ve const semantiği
+ const nesneler
+ constexpr anahtar sözcüğü
+ constexpr işlevler

## İşlevlerin Varsayılan Argüman Alması _(Default Arguments)_

## Referans Semantiği (Reference Semantics)
+ sol taraf referansları `(L value references)`
+ sağ taraf referansları `(R value references)`
+ referanslar ve const semantiği `(references & const semantics)`
+ referanslar ile göstericilerin `(pointer)` karşılaştırılması
+ parametresi referans olan işlevler
+ referans döndüren işlevler

## İşlev Yüklemesi _(Function Overloading)_
+ genel kurallar
+ yüklenmiş işlev çözümlenmesi `(function overload resolution)`
+ const yüklemesi `(const overloading)`
+ extern “C” bildirimi
+ işlev yüklemesinde dikkat edilmesi gereken durumlar

## Tür Dönüştürme Operatörleri _(Type-cast Operators)_
+ static_cast<> operatörü
+ const_cast<> operatörü
+ reinterpret_cast<> operatörü
+ dynamic_cast<> operatörü `(kalıtım başlığı altında)`

## Sınıflara giriş _(Introduction to Classes)_
+ sınıf kapsamı `(class scope)`
sınıflar ve isim arama `(name lookup)`
+ erişim kontrolü `(access control)` ve veri gizleme `(data hiding)`
  + public öğeler `(public members)`
  + private öğeler `(private members)`
  + protected öğeler `(protected members)`
+ sınıfların öğeleri `(class members)`
  + sınıfların veri öğeleri `(data members)`
    + non-static veri öğeleri
    + mutable veri öğeleri
    + static veri öğeleri
  + sınıfların üye işlevleri
    + non-static üye işlevler
    + const üye işlevler
    + static üye işlevler
  + this göstericisi ve \*this
  + sınıfların tür öğeleri `(type members)`
+ sınıfların kurucu işlevleri `(constructors)`
  + kurucu işlev ilk değer verme listesi `(constructor initializer list)`
  + delege eden kurucu işlevler `(delegating constructors)`
  + explicit kurucu işlevler `(explicit constructors)`
+ sınıfların sonlandırıcı işlevleri `(destructors)`
+ üye işlevlerin çağrılması
+  sınıflar ve const doğruluğu `(classes & const correctness)`
  + const sınıf nesneleri `(const objects)`
  + const üye fonksiyonlar `(const member fuctions)`
+ geçici sınıf nesneleri `(temporary objects)`
+ otomatik tür dönüşümleri `(implicit type conversions)` 
+ mutable anahtar sözcüğü
+ friend bildirimi `(friend declarations)` 
  + friend bildirimi ve veri gizleme
  + global işlevlere friend bildirimi
  + sınıfların üye işlevlerine friend bildirimi
  + sınıflara friend bildirimi
  + attorney client idiyomu

## Sınıfların Özel Üye İşlevleri ve Kopyalama İşlemleri _(Special Member Functions & Copy Control)_
+ sınıfların özel işlevleri
  + default constructor `(varsayılan kurucu işlev)`
  + destructor `(sonlandırıcı işlev)`
  + copy constructor `(kopyalayan kurucu işlev)`
  + move constructor `(taşıyan kurucu işlev)`
  + copy assignment `(kopyalayan atama işlevi)`
  + move assignment `(taşıyan atama işlevi)`
+ özel işlevlerin default edilmesi
+ özel işlevlerin delete edilmesi
+ sınıflar ve taşıma semantiği `(move semantics)`
+ `rule of zero`
+ `rule of five`
+ kopyala takas et idiyomu `(copy & swap idiom)`
+ kopyalamanın eliminasyonu `(copy elision)`
  + zorunlu kopyalama eliminasyonu `(mandatory copy elision)`

## Operatör Yüklemesi _(Operator Overloading)_
+ operatör yüklemesine ilişkin genel kurallar
+ üye operatör fonksiyonları
+ global operatör fonksiyonları
+ aritmetik operatörlerin yüklenmesi
+ karşılaştırma operatörlerinin yüklenmesi
+ "++" ve "--" operatörlerinin yüklenmesi
+ ok operatörü ve içerik operatörlerinin yüklenmesi
+ [] operatörünün yüklenmesi
+ fonksiyon çağrı operatörünün yüklenmesi
+ tür dönüştürme operatör fonksiyonları `(type-cast operator functions)`
+ programcının tanımladığı sabitler `(user-defined literals)`

## Dinamik Ömürlü Nesneler _(Dynamic Objects)_
+ new ve delete ifadeleri `(new & delete expressions)` 
+ new[] ve delete [] ifadeleri
+ operator new işlevleri
+ operator delete işlevleri
+ operator new ve operator delete işlevlerinin yüklenmesi
+ std::bad_alloc
+ std::set_new_handler ve std::get_new_handler
+ placement new operatörleri
+ nothrow new

## Tür Eş İsimleri _(Type Alias)_
+ typedef bildirimleri
+ using bildirimleri

## İsim Alanları _(Namespaces)_
+ isim alanlarının oluşturulması
+ isim alanları ve isim arama `(namespaces & name lookup)` 
+ çözünürlük operatörü ve isim alanları `(scope resoşution operator & namespaces)` 
+ using bildirimi `(using declaration)`
+ using namespace direktifi `(using namespace directive)` 
+ argümana bağlı isim arama `(argument dependent lookup)`
+ isimsiz isim alanı `(unnamed namespace)`
+ içsel isim alanları `(nested namespaces)`
+ inline isim alanları `(inline namespaces)`
+ isim alanı eş ismi `(namespace alias)`
+ işlev yüklemesi ve isim alanları `(function overloading & namespaces)` 

## Sınıflar ve Kalıtım _(Classes & Inheritance)_
+ nesne yönelimli programlama ve kalıtım `(OOP & inheritance)`
+ public kalıtımı `(public inheritance)`
+ çalışma zamanı çok biçimliliği `(runtime polymorphism)`
  + sanal işlevler `(virtual function)`
  + saf sanal işlevler `(pure virtual function)`
  + sanal sonlandırıcı işlev `(virtual destructor)`
  + sanal kurucu işlev idiyomu `(virtual constructor idiom)`
  + override bağlamsal anahtar sözcüğü
  + nesne dilimlenmesi `(object slicing)`
  + sanal olmayan arayüz idiyomu `(non-virtual interface idiom)`
+ final bağlamsal anahtar sözcüğü `(final contextual keyword)` 
  + final sınıflar `(final classes)`
  + `final override`
+ çoklu kalıtım `multiple inheritance)`
  + çoklu kalıtımda kapsam ve isim arama`(multiple inheritance & name lookup)` 
  + çoklu kalıtımda sınıfın özel işlevleri
  + elmas formasyonu `(diamond formation)`
  + sanal kalıtım `(virtual inheritance)`
  + çoklu kalıtım ve kalıtımla alınan kurucu işlevler
  + çoklu kalıtımda kopyalama ve taşıma işlemleri
+ private kalıtımı `(private inheritance)`
+ protected kalıtımı `(protected inheritance)`
+ sınıf içi using bildirimi 
+ kalıtımla alınan kurucu işlevler `(inherited constructors)`

## Olağan Dışı Durumların İşlenmesi _(Exception Handling)_
+ exception güvenliği `(exception safety) `
+ hata nesnelerinin gönderilmesi `(throwing exception objects)`
  + throw deyimi `(throw statement)`
  + rethrow deyimi `(rethrow statement)`
+ try blokları
+ catch blokları
  + catch all
+ yakalanamayan hata nesnesi `(uncaught exception)`
+ std::terminate
+ std::set_terminate
+ hata nesnesinin yeniden gönderilmesi `(rethrow statement)`
+ yığının geri sarımı `(stack unwinding)`
+ kurucu işlevlerden exception gönderimi
+ sonlandırıcı işlevler ve hata gönderimi
+ exception handling ve kalıtım `(eception handling & inheritance)`
+ exception handling ve dinamik ömürlü sınıf nesneleri `(eception handling & dynamic objects)`
+ exception  güvenliği için akıllı göstericilerin kullanımı `(eception handling & smart pointers)`
+ işlev try blokları `(function try block)`
+ noexcept belirleyicisi `(noexcept specifier)`
+ beklenmeyen hata nesnesi `(unexpected excetion)`
+ std::unexpected_exception
+ std::exception sınıfı ve hiyerarşisi
  + std::exception sınıfı ve what sanal fonksiyonu
  + std::logic_error
    + std::invalid_argument
    + std::domain_error
    + std::length_error
    + std::out_of_range
    + std::future_error
  + std::runtime_error
    + std::range_error
    + std::overflow_error
    + std::underflow_error
  + std::system_error
  + std::regex_error
  + std::bad_alloc
  + std::bad_typeid
  + std::bad_cast
  + std::bad_exception
  + std::bad_weak_ptr
  + std::bad_function_call
+ kendi hata sınıflarımızı oluşturmak
+ exception garantileri `(eception guarantees)`
  + `basic exception guarantee`
  + `strong exception gurantee`
  + `no throw gurantee`
+ std::current_exception
+ std::exception_ptr
+ std::rethrow_exception

## Çalışma Zamanında Tür Belirlenmesi _(RTTI)_
+ dynamic_cast operatörü
+ typeid operatörü
+ std::typeinfo sınıfı
+ std::bad_typeid

## std::string sınıfı
+ genel kavramlar
+ string::size_type
+ string::npos
+ arama işlevleri
+ set işlemleri
+ erişim işlemleri
+ karşılaştırma işlevleri
+ sayısal dönüşüm işlevleri
+ small string optimization

## Bileşik Nesneler _(Composition)_
+ öğe olan nesneler ve özel işlevler, kopyalama kontrolü.
+ öğe olan nesneler ve erişim kontrolü
+ bileşik nesnelerin kullanıldığı temalar

## İçsel türler _(Type Members)_
+ sınıf içinde yapılan eş isim bildirimleri
+ içsel sınıflar `(nested classes)`
+ `pimpl` idiyomu

## Şablonlar _(Templates)_
+ şablon tür parametreleri `(template type parameters)`
+ şablon sabit parametreleri `(template non-type parameters)`
+ şablon şablon parametreleri `(template template parameters)`
+ şablon argümanları `(template arguments)`
+ şablonlardan kod üretimi `(template instantiation)`
+ fonksiyon şablonları `(function templates)`
  + fonksiyon şablonlarında tür çıkarımı `(function template argument deduction)`
  + fonksiyon şablonlarının yüklenmesi `(function template overloading)`
+ sınıf şablonları `(class templates)`
+ kurucu işlev ile tür çıkarımı `(CTAD)`
+ üye şablonlar `(member templates)`
+ şablonların özelleştirilmesi `(template specialization)`
  + tam özelleştirme `(explicit/full specialization)`
  + kısmi özelleştirme `(partial specialization)`
+ `sfinae`
+ değişken sayıda parametreli şablonlar `(variadic templates)`
+ mükemmel gönderim `(perfect forwarding)`
+ katlama ifadeleri `(fold expressions)`
+ `if constexpr`
+ değişken şablonları `(variable templates)`
+ eş isim şablonları `(alias templates)`

## İteratörler _(Iterators)_
+ aralık kavramı `(ranges)`
+ iteratörlerin kategorileri `(iterator categories)`
  + input iterator
  + output iterator
  + forward iterator
  + bidirectional iterator
  random access iterator
+ kapların begin ve end işlevleri
+ global begin ve end işlevleri
+ iterator işlevleri
  + std::next
  + std::prev
  + std::iter_swap
  + std::advance
  + std::distance
+ iterator uyumlandırıcıları `(iterator adaptors)`
  + akım iteratörleri `(stream iterators)`
    + istream_iterator
    + ostream_iterator
    + istreambuf_iterator
    + ostreambuf_iterator
  + reverse iterators
  + move iterators
  + insert iterators
    + back_insert_iterator
    + front_insert_iterator
    + insert_iterator
+ iterator traits

## Kaplar _(Containers)_
+ STL kapları ve veri yapıları `(STL containers & data structures) `
+ sıralı kaplar `(sequence containers)`
  + std::vector
  + std::deque
  + std::string
  + std::array
  + std::list
  + std::forward_list
+ ilişkisel kaplar `(associative containers)`
  + std::set
  + std::multiset
  + std::map
  + std::multimap
+ sırasız ilişkisel kaplar `(unordered containers)`
  + std::unordered_set
  + std::unordered_multiset
  + std::unordered_map
  + std::unordered_multimap
+ kapların tür öğeleri `(type members of containers)`
+ kapların emplace işlevleri

## Kap Uyumlandırıcıları _(Container Adaptors)_
+ stack
+ queue
+ priority_queue

## Algoritmalar _(Algorithms)_
+ algoritmaların temel özellikleri ve genel ilkeler
+ salt okuyan algoritmalar `non-modifying algorithms)`
+ kap öğelerini değiştiren algoritmalar `(modifying algorithms)`
+ kap öğelerini konumlandıran algoritmalar `(mutating algorithms)`
+ sıralama ile ilgili algoritmalar `(sorting algorithms)`
+ sıralanmış aralıklar üzerinde koşturulan algoritmalar `(sorted range algorithms)`
+ nümerik algoritmalar `(numeric algorithms)`
+ algoritmaların lambda ifadelerini kullanması

## Lambda İfadeleri _(Lambda Expressions)_
+ kapanış türleri ve kapanış nesneleri `(closure types and closure objects)`
+ lambda ifadeleri ve tür çıkarımı `(lambda expressions and type deduction)`
+ lambda yakalama ifadeleri `(lambda captures)`
+ `lambda init capture`
+ capture this 
+ capture `*this`
+ mutable lambdalar
+ trailing return type
+ genelleştirilmiş lambda ifadeleri `(generalized lambda expressions)`
+ algoritmalarda lambda ifadelerinin kullanımı
+ lambda ifadeleri C++11/14/17/20
+ lambda isiyomları

## Akıllı Gösterici Sınıfları _(Standard Smart Pointer Classes)_
+ unique_ptr sınıfı
  + std::make_unique işlev şablonu
  + std::default_delete ve custom deleters
  + tipik hatalar
+ shared_ptr sınıfı
  + referans sayımı `(reference counting)`
  + std::make_shared işlev şablonu
  + weak_ptr sınıfı

## Standart Giriş Çıkış Kütüphanesi _(iostream Library)_
+ giriş çıkış akımlarına ilişkin standart sınıflar `(standard stream classes)`
+ global akım nesneleri 
+ formatlı giriş çıkış işlemleri `(formatted input output)`
+ << ve >> operatörlerinin yüklenmesi `(inserter & extractors)`
+ formatlama ve formatlama işlemleri `(formatting)`
+ manipülatörler `(manipulators)`
+ akımın durumu `(condition states)`
+ string akımları `(stringstreams)`
+ dosya işlemleri `(file operations)`
+ formatsız giriş ve çıkış işlemleri `(unformatted input output)`
+ bellek üstünde yapılan giriş çıkış işlemleri

## Bazı önemli STL Öğelerinin Tanıtımı
+ std::pair
+ std::tuple
+ std::initializer_list
+ std::bitset
+ std::regex
+ type_traits kütüphanesi
+ std::allocator
+ std::ratio
+ std::chrono
+ standart random kütüphanesi
+ std::string_view sınıfı
+ std::optional sınıfı
+ std::variant sınıfı
+ std::any sınıfı
+ std::byte
+ std::invoke

## Tamamlayıcı Araçlar ve Sentaks Öğeleri
+ static_assert 
+ decltype(auto)
+ declval
+ üye fonksiyon göstericileri `(member function pointers)`
+ ham string sabitleri `(raw string literals)`
+ ikilik sayı sisteminde yazılan sabitler `(binary literals)`
+ basamak ayırıcısı `(digit seperator)`
+ ilk değer vermeli if deyimi `(if with initializer)`
+ ilk değer vermeli switch  deyimi `(if with initializer)`
+ alignas belirteci `(alignas specifier)`
+ alignof operatörü `(alignof operator)`
+ yapısal bağlama `(structural binding) (C++17)`
+ attribute’lar

## Concurrency
+ memory model
+ thread’ler ve thread yönetimi
+ std::this_thread isim alanı
+ data race kavramı ve data_race’den kaçınma
+ standart mutex sınıfları ve mutex işlemleri
+ lock_guard ve unique_lock sınıfları
+ std::condition_variable sınıfı
+ std::future ve std::promise sınıfları
+ std::async işlevi
+ atomik türler `(atomic types)`
+ görev tabanlı `(task based)` programlama
+ std::packaged_task sınıfı
+ paralel STL algoritmaları
