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
✅ decltype auto tür çıkarımı `(decltype auto)` <br>

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
✅ referanslar ve _life extension_ <br>

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
✅ sınıf kapsamı `(class scope)` <br>
✅ sınıflar ve isim arama `(name lookup)`<br>
✅ erişim kontrolü `(access control)` ve veri gizleme `(data hiding)`<br>
&emsp;&emsp;❇️ public öğeler `(public members)`<br>
&emsp;&emsp;❇️ private öğeler `(private members)`<br>
&emsp;&emsp;❇️ protected öğeler `(protected members)`<br>
✅ sınıfların öğeleri `(class members)`<br>
&emsp;&emsp;❇️ sınıfların veri öğeleri `(data members)`<br>
&emsp;&emsp;&emsp;&emsp;⦿  non-static veri öğeleri<br>
&emsp;&emsp;&emsp;&emsp;⦿  mutable veri öğeleri<br>
&emsp;&emsp;&emsp;&emsp;⦿  static veri öğeleri<br>
&emsp;&emsp;❇️ sınıfların üye işlevleri<br>
&emsp;&emsp;&emsp;&emsp;⦿ non-static üye işlevler<br>
&emsp;&emsp;&emsp;&emsp;⦿ const üye işlevler<br>
&emsp;&emsp;&emsp;&emsp;⦿ static üye işlevler<br>
&emsp;&emsp;❇️ this göstericisi ve \*this<br>
&emsp;&emsp;❇️ sınıfların tür öğeleri `(type members)`<br>
✅ sınıfların kurucu işlevleri `(constructors)`<br>
&emsp;&emsp;❇️ kurucu işlev ilk değer verme listesi `(constructor initializer list)`<br>
&emsp;&emsp;❇️ delege eden kurucu işlevler `(delegating constructors)`<br>
&emsp;&emsp;❇️ explicit kurucu işlevler `(explicit constructors)`<br>
✅ sınıfların sonlandırıcı işlevleri `(destructors)`<br>
✅ üye işlevlerin çağrılması<br>
✅ sınıflar ve const doğruluğu `(classes & const correctness)`<br>
&emsp;&emsp;❇️ const sınıf nesneleri `(const objects)`<br>
&emsp;&emsp;❇️ const üye fonksiyonlar `(const member fuctions)`<br>
✅ geçici sınıf nesneleri `(temporary objects)`<br>
✅ otomatik tür dönüşümleri `(implicit type conversions)` <br>
✅ mutable anahtar sözcüğü<br>
✅ friend bildirimi `(friend declarations)` <br>
&emsp;&emsp;❇️ friend bildirimi ve veri gizleme<br>
&emsp;&emsp;❇️ global işlevlere friend bildirimi<br>
&emsp;&emsp;❇️ sınıfların üye işlevlerine friend bildirimi<br>
&emsp;&emsp;❇️ sınıflara friend bildirimi<br>
&emsp;&emsp;❇️ attorney client idiyomu<br>

## Sınıfların Özel Üye İşlevleri ve Kopyalama İşlemleri _(Special Member Functions & Copy Control)_
✅ sınıfların özel işlevleri <br>
&emsp;&emsp;❇️ default constructor `(varsayılan kurucu işlev)`<br>
&emsp;&emsp;❇️ destructor `(sonlandırıcı işlev)`<br>
&emsp;&emsp;❇️ copy constructor `(kopyalayan kurucu işlev)`<br>
&emsp;&emsp;❇️ move constructor `(taşıyan kurucu işlev)`<br>
&emsp;&emsp;❇️ copy assignment `(kopyalayan atama işlevi)`<br>
&emsp;&emsp;❇️ move assignment `(taşıyan atama işlevi)`<br>
✅ özel işlevlerin default edilmesi<br>
✅ özel işlevlerin delete edilmesi<br>
✅ sınıflar ve taşıma semantiği `(move semantics)`<br>
✅ `rule of zero`<br>
✅ `rule of five`<br>
✅ kopyala takas et idiyomu `(copy & swap idiom)`<br>
✅ kopyalamanın eliminasyonu `(copy elision)`<br>
&emsp;&emsp;❇️ geçici nesneler yoluyla kopyalama eliminasyonu `(copy elision by temporaries)`<br>
&emsp;&emsp;❇️ RVO (return value optimization)<br>
&emsp;&emsp;❇️ NRVO (names return value optimization)<br>
&emsp;&emsp;❇️ zorunlu kopyalama eliminasyonu `(mandatory copy elision)`<br>

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
✅ nesne yönelimli programlama ve kalıtım `(OOP & inheritance)` <br>
✅ public kalıtımı `(public inheritance)`<br>
✅ çalışma zamanı çok biçimliliği `(runtime polymorphism)`<br>
&emsp;&emsp;❇️ dinamik ve statik tür bilgisi `(static & dynamic type)`<br>
&emsp;&emsp;❇️ sanal işlevler `(virtual function)`<br>
&emsp;&emsp;❇️ saf sanal işlevler `(pure virtual function)`<br>
&emsp;&emsp;❇️ sanal sonlandırıcı işlev `(virtual destructor)`<br>
&emsp;&emsp;❇️ sanal kurucu işlev idiyomu `(virtual constructor idiom)`<br>
&emsp;&emsp;❇️ override bağlamsal anahtar sözcüğü<br>
&emsp;&emsp;❇️ sanal gönderim mekanizmasının implementasyonu `(implementation of virtual dispatch mechanism)`<br>
&emsp;&emsp;❇️ nesne dilimlenmesi `(object slicing)`<br>
&emsp;&emsp;❇️ sanal olmayan arayüz idiyomu `(non-virtual interface idiom)`<br>
✅ final bağlamsal anahtar sözcüğü `(final contextual keyword)` <br>
&emsp;&emsp;❇️ final sınıflar `(final classes)`<br>
&emsp;&emsp;❇️ `final override`<br>
✅ çoklu kalıtım `multiple inheritance)`<br>
&emsp;&emsp;❇️ çoklu kalıtımda kapsam ve isim arama`(multiple inheritance & name lookup)` <br>
&emsp;&emsp;❇️ çoklu kalıtımda sınıfın özel işlevleri<br>
&emsp;&emsp;❇️ elmas formasyonu `(diamond formation)`<br>
&emsp;&emsp;❇️ sanal kalıtım `(virtual inheritance)`<br>
&emsp;&emsp;❇️ çoklu kalıtım ve kalıtımla alınan kurucu işlevler<br>
&emsp;&emsp;❇️ çoklu kalıtımda kopyalama ve taşıma işlemleri<br>
✅ private kalıtımı `(private inheritance)`<br>
&emsp;&emsp;❇️ implementaion inheritance<br>
&emsp;&emsp;❇️ empty base optimization<br>
✅ protected kalıtımı `(protected inheritance)`<br>
✅ sınıf içi using bildirimi <br>
✅ kalıtımla alınan kurucu işlevler `(inherited constructors)`<br>
✅ mixin sınıflar `(mixin classes)`<br>

## Olağan Dışı Durumların İşlenmesi _(Exception Handling)_
✅ exception güvenliği `(exception safety) `<br>
✅ hata nesnelerinin gönderilmesi `(throwing exception objects)`<br>
&emsp;&emsp;throw deyimi `(throw statement)`<br>
&emsp;&emsp;rethrow deyimi `(rethrow statement)`<br>
✅ try blokları<br>
✅ catch blokları<br>
&emsp;&emsp; catch all <br>
✅ yakalanamayan hata nesnesi `(uncaught exception)`<br>
✅ std::terminate<br>
✅ std::set_terminate<br>
✅ hata nesnesinin yeniden gönderilmesi `(rethrow statement)`<br>
✅ yığının geri sarımı `(stack unwinding)`<br>
✅ kurucu işlevlerden exception gönderimi<br>
✅ sonlandırıcı işlevler ve hata gönderimi<br>
✅ exception handling ve kalıtım `(eception handling & inheritance)`<br>
✅ exception handling ve dinamik ömürlü sınıf nesneleri `(eception handling & dynamic objects)`<br>
✅ exception  güvenliği için akıllı göstericilerin kullanımı `(eception handling & smart pointers)`<br>
✅ işlev try blokları `(function try block)`<br>
✅ noexcept belirleyicisi `(noexcept specifier)`<br>
✅ beklenmeyen hata nesnesi `(unexpected excetion)`<br>
✅ std::unexpected_exception<br>
✅ std::exception sınıfı ve hiyerarşisi<br>
&emsp;&emsp;❇️ std::exception sınıfı ve what sanal fonksiyonu<br>
&emsp;&emsp;❇️ std::logic_error<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::invalid_argument<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::domain_error<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::length_error<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::out_of_range<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::future_error<br>
&emsp;&emsp;❇️ std::runtime_error<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::range_error<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::overflow_error<br>
&emsp;&emsp;&emsp;&emsp;⦿ std::underflow_error<br>
&emsp;&emsp;❇️ std::system_error<br>
&emsp;&emsp;❇️ std::regex_error<br>
&emsp;&emsp;❇️ std::bad_alloc<br>
&emsp;&emsp;❇️ std::bad_typeid<br>
&emsp;&emsp;❇️ std::bad_cast<br>
&emsp;&emsp;❇️ std::bad_exception<br>
&emsp;&emsp;❇️ std::bad_weak_ptr<br>
&emsp;&emsp;❇️ std::bad_function_call<br>
✅ kendi hata sınıflarımızı oluşturmak `(custom exception classes)`<br>
✅ exception garantileri `(eception guarantees)`<br>
&emsp;&emsp;❇️ `basic exception guarantee`<br>
&emsp;&emsp;❇️ `strong exception guarantee`<br>
&emsp;&emsp;❇️ `no throw guarantee`<br>
✅ std::current_exception<br>
✅ std::exception_ptr<br>
✅ std::rethrow_exception<br>

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
✅ öğe olan nesneler ve özel işlevler, kopyalama kontrolü.<br>
✅ öğe olan nesneler ve erişim kontrolü<br>
✅ bileşik nesnelerin kullanıldığı temalar<br>

## İçsel türler _(Type Members)_
✅ sınıf içinde yapılan eş isim bildirimleri<br>
✅ içsel sınıflar `(nested classes)`<br>
&emsp;&emsp;❇️ erişim kontrolü `(access control)`<br>
&emsp;&emsp;❇️ `pimpl` idiyomu `(pimpl idiom)`

## Şablonlar _(Templates)_
✅ şablon tür parametreleri `(template type parameters)` <br>
✅ şablon sabit parametreleri `(template non-type parameters)`<br>
✅ şablon şablon parametreleri `(template template parameters)`<br>
✅ şablon argümanları `(template arguments)`<br>
&emsp;&emsp;❇️ belirtilmiş template argümanları `(explicit template arguments)`<br>
&emsp;&emsp;❇️ varsayılan template argümanları `(default template arguments)`<br>
✅ şablonlardan kod üretimi `(template instantiation)`<br>
✅ fonksiyon şablonları `(function templates)`<br>
&emsp;&emsp;❇️ fonksiyon şablonlarında tür çıkarımı `(function template argument deduction)`<br>
&emsp;&emsp;❇️ fonksiyon şablonlarının yüklenmesi `(function template overloading)`<br>
✅ sınıf şablonları `(class templates)`<br>
✅ kurucu işlev ile tür çıkarımı `(CTAD)`<br>
✅ üye şablonlar `(member templates)`<br>
✅ şablonların özelleştirilmesi `(template specialization)`<br>
&emsp;&emsp;❇️ tam özelleştirme `(explicit/full specialization)`<br>
&emsp;&emsp;❇️ kısmi özelleştirme `(partial specialization)`<br>
✅ `sfinae`<br>
✅ değişken sayıda parametreli şablonlar `(variadic templates)`<br>
✅ mükemmel gönderim `(perfect forwarding)`<br>
✅ katlama ifadeleri `(fold expressions)`<br>
✅ `if constexpr`<br>
✅ değişken şablonları `(variable templates)`<br>
✅ eş isim şablonları `(alias templates)`<br>

## İteratörler _(Iterators)_
✅ aralık kavramı `(ranges)`<br>
✅ iteratörlerin kategorileri `(iterator categories)`<br>
&emsp;&emsp;❇️ input iterator<br>
&emsp;&emsp;❇️ output iterator<br>
&emsp;&emsp;❇️ forward iterator<br>
&emsp;&emsp;❇️ bidirectional iterator<br>
&emsp;&emsp;❇️ random access iterator<br>
✅ kapların begin ve end işlevleri<br>
✅ global begin ve end işlevleri<br>
✅ iterator işlevleri<br>
&emsp;&emsp;❇️ std::next <br>
&emsp;&emsp;❇️ std::prev <br>
&emsp;&emsp;❇️ std::iter_swap<br>
&emsp;&emsp;❇️ std::advance <br>
&emsp;&emsp;❇️ std::distance<br>
✅ iterator uyumlandırıcıları `(iterator adaptors)`<br>
&emsp;&emsp;❇️ akım iteratörleri `(stream iterators)`<br>
&emsp;&emsp;&emsp;&emsp;⦿ istream_iterator<br>
&emsp;&emsp;&emsp;&emsp;⦿ ostream_iterator<br>
&emsp;&emsp;&emsp;&emsp;⦿ istreambuf_iterator<br>
&emsp;&emsp;&emsp;&emsp;⦿ ostreambuf_iterator<br>
&emsp;&emsp;❇️ reverse iterators<br>
&emsp;&emsp;❇️ move iterators<br>
&emsp;&emsp;❇️ insert iterators<br>
&emsp;&emsp;&emsp;&emsp;⦿ back_insert_iterator<br>
&emsp;&emsp;&emsp;&emsp;⦿ front_insert_iterator<br>
&emsp;&emsp;&emsp;&emsp;⦿ insert_iterator<br>
✅ iterator traits

## Kaplar _(Containers)_
✅ STL kapları ve veri yapıları `(STL containers & data structures) ` <br>
✅ sıralı kaplar `(sequence containers)`<br>
&emsp;&emsp;❇️ std::vector<br>
&emsp;&emsp;❇️ std::deque<br>
&emsp;&emsp;❇️ std::string<br>
&emsp;&emsp;❇️ std::array<br>
&emsp;&emsp;❇️ std::list<br>
&emsp;&emsp;❇️ std::forward_list<br>
✅ ilişkisel kaplar `(associative containers)`<br>
&emsp;&emsp;❇️ std::set<br>
&emsp;&emsp;❇️ std::multiset<br>
&emsp;&emsp;❇️ std::map<br>
&emsp;&emsp;❇️ std::multimap<br>
✅ sırasız ilişkisel kaplar `(unordered containers)`<br>
&emsp;&emsp;❇️ std::unordered_set<br>
&emsp;&emsp;❇️ std::unordered_multiset<br>
&emsp;&emsp;❇️ std::unordered_map<br>
&emsp;&emsp;❇️ std::unordered_multimap<br>
✅ kapların tür öğeleri `(type members of containers)`<br>
✅ kapların emplace işlevleri<br>

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
✅ unique_ptr sınıfı <br>
&emsp;&emsp;❇️ std::make_unique işlev şablonu <br> 
&emsp;&emsp;❇️ std::default_delete ve custom deleters <br>
&emsp;&emsp;❇️ tipik hatalar <br>
✅ std::shared_ptr sınıfı<br>
&emsp;&emsp;❇️ referans sayımı `(reference counting)`<br>
&emsp;&emsp;❇️ std::make_shared işlev şablonu<br>
&emsp;&emsp;❇️ weak_ptr sınıfı<br>

## Standart Giriş Çıkış Kütüphanesi _(iostream Library)_
✅ giriş çıkış akımlarına ilişkin standart sınıflar `(standard stream classes)` <br>
✅ global akım nesneleri `(global stream objects)`<br>
✅ formatlı giriş çıkış işlemleri `(formatted input output)`<br>
✅ << ve >> operatörlerinin yüklenmesi `(inserter & extractors)`<br>
✅ formatlama ve formatlama işlemleri `(formatting)`<br>
✅ manipülatörler `(manipulators)`<br>
✅ akımın durumu `(condition states)`<br>
✅ string akımları `(string streams)`<br>
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
✅ std::string_view sınıfı (C++17)<br>
✅ std::optional sınıfı (C++17) <br>
✅ std::variant sınıfı (C++17)<br>
✅ std::any sınıfı (C++17)<br>
✅ std::byte (C++17)<br>
✅ std::invoke<br>

## Tamamlayıcı Araçlar ve Sentaks Öğeleri
✅ aralık tabanlı for döngüleri `(range based for loops)`<br>
✅ ilk değer vermeli if ve switch deyimleri `(if/switch with initializers)`<br>
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
