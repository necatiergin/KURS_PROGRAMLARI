# Online C++ Programlama Dili Kursu İçeriği

## C++ Dilinin Genel Tanıtımı
✅ C++ dilinin tarihçesi<br>
✅ C++ dili ve programlama paradigmaları<br>
✅ C++ dili standartları<br>
✅ C++98 – 03<br>
✅ C++11<br>
✅ C++14<br>
✅ C++17<br>
✅ C++20<br>
✅ eski C++ ve modern C++<br>

## C Dili ve C++ İçindeki C Dili _(C in C++)_
✅ C dilinden C++ diline geçiş<br>
✅ işlev bildirimleri ve tanımlamalarına ilişkin farklılıklar<br>
✅ türlere ve tür dönüşümlerine ilişkin farklılıklar<br>
✅ C’de geçerli C++’da geçersiz durumlar<br>
✅ C99 ve C++<br>

## Temel Kavramlar _(Basic Concepts)_
✅ tamamlanmış ve eksik türler `(complete & incomplete types)`<br>
✅ tek tanımlama kuralı `(one definition rule)`<br>
✅ ifadelerin değer kategorileri `(value categories)`<br>
✅ tanımsız davranış `(undefined behavior)` <br>
✅ derleyiciye bağlı davranışlar. `(implementation defined & implementaion specified)`<br>
✅ derleyici eklentileri `(compiler extensions)` <br>
✅ kapsam `(scope)` ve isim arama `(name lookup)` <br>
✅ erişim kontrolü `(access control)` <br>
✅ çift anlamlılık hatası `(ambiguity)` <br>

## İlk Değer Verme _(Initialization)_
✅ eş biçimli ilk değer verme `(uniform initialization)`<br>
✅ daraltıcı dönüşümler `(narrowing conversions)` <br>
✅ most vexing parse <br>
✅ doğrudan ilk değer verme `(direct intialization)` <br>
✅ değerle başlatma `value initialization`<br>
✅ kopyalama ile ilk değer verme `(copy initialization)` <br>
✅ varsayılan ilk değer verme `(default initialization)` <br>
✅ bileşiklere ilk değer verme `(aggregate initialization)` <br>

## Tür Çıkarımı _(Type Deduction)_
✅ auto belirteci ile tür çıkarımı `(auto type deduction)` <br>
✅ decltype belirteci ile tür çıkarımı `(decltype type deduction)` <br>
✅ sonradan gelen geri dönüş türü `(trailing  return type)` <br>
✅ auto geri dönüş değeri türü `(auto return type)` <br>

## kapsamlandırılmış enum türleri _(scoped enums)_
✅ geleneksel enum türleri `(conventional enum types)` <br>
✅ baz tür seçimi `(underlying type)` <br>
✅ tür dönüşümleri `(type conversions)` <br>
✅ enum türleri kapsam `(enum classes & scope)` <br>
✅ using enum declarations (C++20) <br>

## Sabit İfadeleri _(Constant Expressions)_
✅ const anahtar sözcüğü ve const semantiği `(const keyword & const semantics)`<br>
✅ const nesneler `(const objects)`<br>
✅ constexpr anahtar sözcüğü `(constexpr keyword)`<br>
✅ constexpr işlevler `(constexpr functions)`<br>
✅ consteval işlevler - C++20 `(consteval functions - C++20)`<br>
✅ constinit anahtar sözcüğü - C++20

## İşlevlerin Varsayılan Argüman Alması _(Default Arguments)_

## Referans Semantiği (Reference Semantics)
✅ sol taraf referansları `(L value references)`<br>
✅ sağ taraf referansları `(R value references)`<br>
✅ referanslar ve const semantiği `(references & const semantics)`<br>
✅ referanslar ile göstericilerin `(pointer)` karşılaştırılması<br>
✅ parametresi referans olan işlevler<br>
✅ referans döndüren işlevler<br>

## İşlev Yüklemesi _(Function Overloading)_
✅ genel kurallar<br>
✅ yüklenmiş işlev çözümlenmesi `(function overload resolution)`<br>
✅ const yüklemesi `(const overloading)`<br>
✅ extern "C" bildirimi `(extern C declarations)`<br>
✅ işlev yüklemesinde dikkat edilmesi gereken durumlar<br>

## Tür Dönüştürme Operatörleri _(Type-cast Operators)_
✅ static_cast<> operatörü<br>
✅ const_cast<> operatörü<br>
✅ reinterpret_cast<> operatörü<br>
✅ dynamic_cast<> operatörü `(kalıtım başlığı altında)`<br>

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
  + geçici nesneler yoluyla kopyalama eliminasyonu `(copy elision by temporaries)`
  + RVO (return value optimization)
  + NRVO (names return value optimization)
  + zorunlu kopyalama eliminasyonu `(mandatory copy elision)`

## Operatör Yüklemesi _(Operator Overloading)_
✅ operatör yüklemesine ilişkin genel kurallar<br>
✅ üye operatör fonksiyonları `(member operator functions)`<br>
✅ global operatör fonksiyonları `(global operator functions)`<br>
✅ aritmetik operatörlerin yüklenmesi<br>
✅ karşılaştırma operatörlerinin yüklenmesi<br>
✅ 3 yollu karşılaştırma operatörü `(3-way comparision operator)` C++20<br>
✅ "++" ve "--" operatörlerinin yüklenmesi<br>
✅ ok operatörü ve içerik operatörlerinin yüklenmesi<br>
✅ [] operatörünün yüklenmesi<br>
✅ fonksiyon çağrı operatörünün yüklenmesi<br>
✅ tür dönüştürme operatör fonksiyonları `(type-cast operator functions)`<br>
✅ programcının tanımladığı sabitler `(user-defined literals)`<br>

## Dinamik Ömürlü Nesneler _(Dynamic Objects)_
✅ new ve delete ifadeleri `(new & delete expressions)` <br>
✅ new[] ve delete [] ifadeleri<br>
✅ operator new işlevleri<br>
✅ operator delete işlevleri<br>
✅ operator new ve operator delete işlevlerinin yüklenmesi<br>
✅ std::bad_alloc<br>
✅ std::set_new_handler ve std::get_new_handler<br>
✅ placement new operatörleri<br>
✅ nothrow new<br>

## Tür Eş İsimleri _(Type Alias)_
✅ typedef bildirimleri<br>
✅ using bildirimleri<br>

## İsim Alanları _(Namespaces)_
✅ isim alanlarının oluşturulması <br>
✅ isim alanları ve isim arama `(namespaces & name lookup)` <br>
✅ çözünürlük operatörü ve isim alanları `(scope resoşution operator & namespaces)` <br>
✅ using bildirimi `(using declaration)`<br>
✅ using namespace direktifi `(using namespace directive)` <br>
✅ argümana bağlı isim arama `(argument dependent lookup)`<br>
✅ isimsiz isim alanı `(unnamed namespace)`<br>
✅ içsel isim alanları `(nested namespaces)`<br>
✅ inline isim alanları `(inline namespaces)`<br>
✅ isim alanı eş ismi `(namespace alias)`<br>
✅ işlev yüklemesi ve isim alanları `(function overloading & namespaces)` <br>

## Sınıflar ve Kalıtım _(Classes & Inheritance)_
+ nesne yönelimli programlama ve kalıtım `(OOP & inheritance)`
+ public kalıtımı `(public inheritance)`
+ çalışma zamanı çok biçimliliği `(runtime polymorphism)`
  + dinamik ve statik tür bilgisi `(static & dynamic type)`
  + sanal işlevler `(virtual function)`
  + saf sanal işlevler `(pure virtual function)`
  + sanal sonlandırıcı işlev `(virtual destructor)`
  + sanal kurucu işlev idiyomu `(virtual constructor idiom)`
  + override bağlamsal anahtar sözcüğü
  + sanal gönderim mekanizmasının implementasyonu `(implementation of virtual dispatch mechanism)`
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
  + implementaion inheritance
  + empty base optimization
+ protected kalıtımı `(protected inheritance)`
+ sınıf içi using bildirimi 
+ kalıtımla alınan kurucu işlevler `(inherited constructors)`
+ mixin sınıflar `(mixin classes)`

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
+ kendi hata sınıflarımızı oluşturmak `(custom exception classes)`
+ exception garantileri `(eception guarantees)`
  + `basic exception guarantee`
  + `strong exception guarantee`
  + `no throw guarantee`
+ std::current_exception
+ std::exception_ptr
+ std::rethrow_exception

## Çalışma Zamanında Tür Belirlenmesi _(RTTI)_
✅ dynamic_cast operatörü<br>
✅ typeid operatörü<br>
✅ std::typeinfo sınıfı<br>
✅ std::bad_typeid<br>

## std::string sınıfı
✅ genel kavramlar <br>
✅ string::size_type<br>
✅ string::npos<br>
✅ arama işlevleri<br>
✅ set işlemleri<br>
✅ erişim işlemleri<br>
✅ karşılaştırma işlevleri `(comparision functions)`<br>
✅ sayısal dönüşüm işlevleri `(numeric conversions)`<br>
✅ küçük string optimizasyonu `(small string optimization)`<br>
✅ bir STL kabı olaral string sınıfı `(string class as STL container)` <br>

## Bileşik Nesneler _(Composition)_
+ öğe olan nesneler ve özel işlevler, kopyalama kontrolü.
+ öğe olan nesneler ve erişim kontrolü
+ bileşik nesnelerin kullanıldığı temalar

## İçsel türler _(Type Members)_
+ sınıf içinde yapılan eş isim bildirimleri
+ içsel sınıflar `(nested classes)`
  + erişim kontrolü `(access control)`
  + `pimpl` idiyomu `(pimpl idiom)`

## Şablonlar _(Templates)_
+ şablon tür parametreleri `(template type parameters)`
+ şablon sabit parametreleri `(template non-type parameters)`
+ şablon şablon parametreleri `(template template parameters)`
+ şablon argümanları `(template arguments)`
  + belirtilmiş template argümanları `(explicit template arguments)`
  + varsayılan template argümanları `(default template arguments)`
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
✅ std::stack<br>
✅ std::queue<br>
✅ std::priority_queue<br>

## Algoritmalar _(Algorithms)_
✅ algoritmaların temel özellikleri ve genel ilkeler <br>
✅ salt okuyan algoritmalar `non-modifying algorithms)`<br>
✅ kap öğelerini değiştiren algoritmalar `(modifying algorithms)`<br>
✅ kap öğelerini konumlandıran algoritmalar `(mutating algorithms)`<br>
✅ sıralama ile ilgili algoritmalar `(sorting algorithms)`<br>
✅ sıralanmış aralıklar üzerinde koşturulan algoritmalar `(sorted range algorithms)`<br>
✅ nümerik algoritmalar `(numeric algorithms)`<br>
✅ algoritmaların lambda ifadelerini kullanması<br>

## Lambda İfadeleri _(Lambda Expressions)_
✅ kapanış türleri ve kapanış nesneleri `(closure types and closure objects)`<br>
✅ lambda ifadeleri ve tür çıkarımı `(lambda expressions and type deduction)`<br>
✅ lambda yakalama ifadeleri `(lambda captures)`<br>
✅ `lambda init capture`<br>
✅ capture this <br>
✅ capture `*this`<br>
✅ mutable lambdalar<br>
✅ trailing return type<br>
✅ genelleştirilmiş lambda ifadeleri `(generalized lambda expressions)`<br>
✅ algoritmalarda lambda ifadelerinin kullanımı<br>
✅ lambda ifadeleri C++11/14/17/20<br>
✅ lambda idiyomları `(lambda idioms)`<br>

## Akıllı Gösterici Sınıfları _(Standard Smart Pointer Classes)_
+ unique_ptr sınıfı
  + std::make_unique işlev şablonu
  + std::default_delete ve custom deleters
  + tipik hatalar
+ std::shared_ptr sınıfı
  + referans sayımı `(reference counting)`
  + std::make_shared işlev şablonu
  + weak_ptr sınıfı

## Standart Giriş Çıkış Kütüphanesi _(iostream Library)_
✅ giriş çıkış akımlarına ilişkin standart sınıflar `(standard stream classes)` <br>
✅ global akım nesneleri `(global stream objects)`<br>
✅ formatlı giriş çıkış işlemleri `(formatted input output)`<br>
✅ << ve >> operatörlerinin yüklenmesi `(inserter & extractors)`<br>
✅ formatlama ve formatlama işlemleri `(formatting)`<br>
✅ manipülatörler `(manipulators)`<br>
✅ akımın durumu `(condition states)`<br>
✅ string akımları `(stringstreams)`<br>
✅ dosya işlemleri `(file operations)`<br>
✅ formatsız giriş ve çıkış işlemleri `(unformatted input output)`<br>
✅ bellek üstünde yapılan giriş çıkış işlemleri `(in-memory input output operations)`<br>

## Bazı önemli STL Öğelerinin Tanıtımı
✅ std::pair<br>
✅ std::tuple<br>
✅ std::initializer_list<br>
✅ std::bitset<br>
✅ std::regex<br>
✅ type_traits kütüphanesi<br>
✅ std::allocator<br>
✅ std::ratio<br>
✅ std::chrono<br>
✅ standart random kütüphanesi<br>
✅ std::string_view sınıfı<br>
✅ std::optional sınıfı<br>
✅ std::variant sınıfı<br>
✅ std::any sınıfı<br>
✅ std::byte<br>
✅ std::invoke<br>

## Tamamlayıcı Araçlar ve Sentaks Öğeleri
✅ static_assert <br>
✅ decltype(auto) tür çıkarımı<br>
✅ std::declval<br>
✅ üye fonksiyon göstericileri `(member function pointers)`<br>
✅ ham string sabitleri `(raw string literals)`<br>
✅ ikilik sayı sisteminde yazılan sabitler `(binary literals)`<br>
✅ basamak ayırıcısı `(digit seperator)`<br>
✅ ilk değer vermeli if deyimi `(if with initializer)`<br>
✅ ilk değer vermeli switch  deyimi `(if with initializer)`<br>
✅ alignas belirteci `(alignas specifier)`<br>
✅ alignof operatörü `(alignof operator)`<br>
✅ yapısal bağlama `(structural binding) (C++17)`<br>
✅ attribute’lar `(attributes)`<br>

## Concurrency
✅ memory model <br>
✅ thread’ler ve thread yönetimi<br>
✅ std::this_thread isim alanı<br>
✅ data race kavramı ve data_race’den kaçınma<br>
✅ standart mutex sınıfları ve mutex işlemleri<br>
✅ lock_guard ve unique_lock sınıfları<br>
✅ std::condition_variable sınıfı<br>
✅ std::future ve std::promise sınıfları<br>
✅ std::async işlevi<br>
✅ atomik türler `(atomic types)`<br>
✅ görev tabanlı `(task based)` programlama<br>
✅ std::packaged_task sınıfı<br>
✅ paralel STL algoritmaları<br>
