# C Programlama Dili Kursu İçeriği

+ __Kursun Tanıtımı__
+ __C Programlama Dilinin Genel Tanıtımı__
	+ programlama dillerini birbirinden ayıran kriterler
		+ declarative ve imperative diller _(declarative & imperative languages)_
		+ programlama paradigmaları _(programming paradigms)_
		+ seviye (level)
		+ mülkiyet
		+ statik ve dinamik tür kavramları _(static typing vs. dynamic typing)_
		+ prosedürel programlama ve C dili _(procedural programming & C language)_
	+ C dilinin kullanım alanları 
	+ C dilinin temel özellikleri
	+ C dilinin tarihsel gelişimi ve C Standartları _(history of C language & C Standards)_
		+ Klasik C
		+ C89
		+ C99
		+ C11
	+ C ve C++ ilişkisi

+ __Temel Kavramlar__
	+ atom kavramı _(tokens)_ 
		+ atom kategorileri _(token categories)_
			+ anahtar sözcükler _(keywords)_
			+ isimler _(identifiers)_
			+ sabitler _(constants - literals)_
			+ string literalleri _(string literals)_
			+ operatörler _(operators)_
		+ atomlarına ayırma _(tokenizing)_
		+ en uzun atom kuralı _(maximum munch)_
	+ sayı sistemleri
		+ işaretli ve işaretsiz ikilik sayı sistemi _(signed & unsigned binary systems)_
		+ dönüşümler _(conversions)_
		+ bire tümleme işlemi _(one's complement)_
		+ ikiye tümleme işlemi _(two's complement)_
		+ onaltılık sayı sistemi _(hexadecimal system)_
		+ sekizlik sayı sistemi _(octal system)_
	+ nesneler _(objects)_
		+ tür kavramı _(data types)_
		+ nesnelerin bellek alanları _(storage)_
		+ temel türler _(fundemantal types)_
		+ programcı tarafından tanımlanan türler _(user-defined types)_
	+ ifadeler (expressions)
		+ ifade kategorileri _(value categories)_
			+ sol taraf değeri ifadesi _(L value expression)_
			+ sağ taraf değeri ifadesi _(R value expression)_
		+ sabit ifadesi _(constant expression)_
		
+ __Bir C Programı Oluşturmak__
	+ metin düzenleyici programlar ve text dosyaları
	+ kaynak dosya ve çeviri birimi _(source file & translation unit)_
	+ derleyici program ve derleme süreci 
		+ derleyici bulgu iletileri
		+ tanımsız davranış _(undefined behavior)_
		+ derleyiciye bağlı durumlar _(implementation defined behavior)_
		+ derleyici programların lojik kontrolleri
		+ derleyiciler ve kod optimizasyonu
		+ derleyici eklentileri _(compiler extensions)_
	+ önişlemci program _(preprocessor)_
	+ bağlayıcı program bağlama zamanı _(linker program & link time)_ 
	+ ide’ler ve yardımcı programlar
		+ statik kod analizi yapan programlar
		+ hata ayıklayıcı programlar
		
+ __Veri Türleri (Data Types)__
	+ varsayılan türler _(fundemental/basic types)_
		+ tamsayı türleri _(integer types)_
		+ gerçek sayı türleri _(floating types)_
	+ programcı tarafından oluşturulan türler _(user defined types)_
	
+ __Bildirim ve Tanımlama (Declarations & Definitions)__
	+ bildirimler ve deyimler _(declarations and statements)_
	+ ilk değer verme _(initialization)_
	+ bildirim listesi _(declarations as comma-separated lists)_ 
	+ tanımlama _(definition)_
+ __Kapsam ve İsim arama (Scope & Name Lookup)__
	+ kapsam (scope)
		+ kapsam kategorileri _(scope categories)_
			+ blok kapsamı _(block scope)_
			+ dosya kapsamı _(file scope)_
			+ function prototype scope
			+ işlev kapsamı _(function scope)_
	+ isim arama _(name lookup)_
	+ isim çakışmaları _(name collision)_
	
+ __Ömür Kavramı (Storage Duration)__
	+ otomatik ömür _(automatic storage class)_
	+ statik ömür _(static storage class)_
	+ dinamik ömür _(dynamic storage class)_
	
+ __İşlevler (Functions)__
	+ işlevlerin tanımlanması _(function definitions)_
		+ işlevlerin parametre değişkenleri _(formal parameters)_
		+ işlevlerin geri dönüş değerleri _(return values)_
		+ değerle çağrı _(call by value)_
		+ referansla çağrılan işlevler _(call by reference)_
		+ void işlevler _(void functions)_
	+ return deyimi _(return statement)_
		+ ifadeli ve ifadesiz return deyimleri _(return statements with/without expression)
_	+ saf ve saf olmayan işlevler _(pure and impure functions)_
	+ işlevlerin çağrılması _(function calls)_
		+ işlev çağrılarından elde edilen değerlerin kullanılması
	+ inline işlevler _(inline functions)_
	+ işlevlerin bildirilmesi _(function declarations)_
	
+ __Standart Kütüphane (Standard Library)__
	+ standart kütüphanenin varlık nedenleri
		+ ortak arayüz ilkesi _(common interface principle)_ 
		+ taşınabilirlik _(portability)_
		+ kodların tekrar kullanımı _(code reuse)_
	+ standart formatlı giriş çıkış işlevleri _(standard formatted input/output functions)_
		+ standart giriş akımı _(standard input stream)_
		+ standart çıkış akımları _(standard output stream)_
		+ standart hata akımı _(standard error stream)_
		+ akımların yönlendirilmesi _(direction of the streams)_
		+ printf işlevi
		+ scanf işlevi
	+ standart formatsız giriş ve çıkış işlemleri _(standard unformatted input/output functions)_ 
		+ getchar
		+ putchar
	+ standart başlık dosyaları _(standard headers)_
	+ standart math kütüphanesi _(standard math library)_

+ __Operatörler (Operators)__
	+ temel kavramlar
		+ operatörlerin değer üretmesi _(values generated by operators)_
		+ operatör önceliği _(priority of operators)_
		+ öncelik yönü _(associativity)_
		+ yan etki _(side effect)_
		+ yan etki noktası _(sequence point)_
	+ aritmetik operatörler
		+ toplama, çıkarma, çarpma, bölme ve kalan operatörleri
		+ işaret operatörleri _(sign operators)_
		+ artırma ve eksiltme operatörleri _(increment & decrement operators)_
	+ karşılaştırma operatörleri _(relational operators)_
		+ karşılaştırma idiyomları 
		+ tipik hatalar _(typical mistakes)_ 
	+ lojik operatörler _(logical operators)_
		+ lojik yorumlama
		+ kısa devre davranışı _(short-circuit behavior)_
		+ tipik hatalar _(typical mistakes)_
		+ lojik ifadeler -(logical expressions)_
		+ idiyomlar _(idioms)_
	+ atama operatörleri _(assignment operators)_
		+ atama operatörlerinin değer üretmesi _(values generated by assignment operators)_
		+ yalın atama operatörü
		+ işlemli atama operatörleri _(compound assignment operators)_
		+ idiyomlar _(idioms)_
	+ virgül operatörü _(comma operator)_
	+ öncelik operatörü
+ __Sabitler (Constants)__
	+ sabitlerin türleri _(types of constants)_
		+ tamsayı sabitleri _(integer constants)_
		+ gerçek sayı sabitleri _(floating constants)_
			+ üstel notasyon _(scientific notation)_ 
		+ karakter sabitleri _(character constants)_
			+ kaçış sekansları _(escape sequences)_
			
+ __Kontrol Deyimleri__
	+ if deyimi _(if statement)_
		+ genel sentaks
		+ else if merdiveni _(else if ladders)_
		+ tipik yapılan hatalar _(typical mistakes)_
		+ test işlevleri _(test functions)_
	+ döngü deyimleri
		+ while döngü deyimi _(while statement)_
		+ do while döngü deyimi _(do-while statement)_
		+ for döngü deyimi _(for statement)_
		+ break deyimi _(break statement)_
		+ continue deyimi _(continue statement)_
		+ iç içe döngüler _(nested loops)_
		+ döngü idiyomları _(loop idioms)_ 
	+ switch deyimi
	+ goto deyimi
+ __Koşul Operatörü (Ternary Operator)__
+ __Standart ctype Kütüphanesi__
	+ karakter test işlevleri
		+ isupper, islower, isalpha, isdigit, isalnum, isxdigit, isspace, isblank, ispunct, isprint, isgraph, iscntrl
	+ karakter dönüşüm işlevleri
		+ toupper ve tolower işlevleri
+ __İşlev Bildirimleri (Function Declarations)__
+ __Önişlemci Komutları – 1__
	+ #include komutu
	+ #define komutu ve makrolar
		+ sembolik sabitler
		+ işlevsel makrolar
	+ #undef komutu
	+ koşullu derleme işlemleri ve koşullu derleme komutları
		+ #if
		+ #endif
		+ #else
		+ #elif
		+ #ifdef
		+ #ifndef
	+ standart limits kütüphanesi
	
+ __Tür Dönüşümleri (Type Conversions)__
	+ otomatik tür dönüşümleri _(implicit type conversions)_
	+ tür dönüştürme operatörü _(type-cast operator)_
	+ tür dönüşümleri ve veri kaybı _(narrowing conversions)_
	
+ __typedef bildirimleri – 1__
	+ tür eş isimleri ve taşınabilirlik _(type alias & portability)_  
	+ standart typedef isimleri _(standard typedef names)_
		+ size_t tür eş ismi
		+ ptrdiff_t tür ismi
		+ time_t ve clock_t tür isimleri
	+ \<stdint> başlık dosyası
	+ \<stdbool> başlık dosyası
	
+ __Rastgele Sayı Üretimi ve Programlamadaki Önemi__
	+ gerçek ve sözde rastgele sayı üretimi _(truly and pseudo random number generation)_
	+ rastgele sayı üretim algoritmaları
	+ tohum değeri _(seed value)_
	+ standart rand ve srand işlevleri
+ __sizeof Operatörü__
+ __Diziler (arrays)__
	+ veri yapıları ve algoritmalara giriş _(introduction to data structure & algorithms)_
		+ veri yapıları _(data structures)_
		+ algoritmanın karmaşıklığı _(complexity of algorithms)_
		+ big O notasyonu _(big O notation)_
	+ tamsayı ve gerçek sayı dizileri
	+ dizilere ilk değer verme _(initialization of arrays)_
		+ designated initializer (C99)
	+ yazılar ve yazı tutan char diziler
		+ null karakter _(null character)_
		+ yazılara ilişkin temel algoritmalar
+ __Göstericiler (pointers)__
	+ temel kavramlar
		+ adres ifadeleri _(pointer expressions)_
		+ gösterici değişkenler _(pointer variables)_
		+ göstericiler ve storage _(pointers & storage duration)_
	+ adres operatörü _(address of operator)_
	+ içerik operatörü _(dereferencing operator)_  
	+ diziden adrese dönüşüm _(array to pointer conversion)_
	+ geçerli ve geçersiz göstericiler _(valid & invalid pointers)_
	+ göstericiler ve const semantiği _(pointers & const semantics)_
		+ kendisi const göstericiler _(const pointers)_
		+ okuma amaçlı const göstericiler 
		+ const semantiği ve tür dönüşümleri _(const semantics & type conversions)_
	+ gösterici aritmetiği
	+ indeks operatörü _(index/subscript operators)_
	+ diziler üstünde işlem yapan işlevler 
	+ göstericiler ve karşılaştırma işlemleri _(pointers & relational operators)_
	+ adres döndüren işlevler _(function returning pointers)_
	+ NULL gösterici _(NULL pointer)_
	+ endianness, little endian, big endian kavramları _(endianness, litlle & big endian)_
	+ gösterici hataları _(pointer mistakes)_
+ __Standart string Kütüphanesi (string library)__
	+ strlen, strcpy, strcat, strncpy, strncat işlevleri
	+ arama işlevleri: strchr, strnchr, strstr, strpbrk, strspn, strcspn
	+ karşılaştırma işlevleri : strcmp, strcoll, stricmp
	+ strtok işlevi
	+ diğer standart string işlevleri
	+ örnek bazı Posix işlevleri
+ __Standart stddef Kütüphanesi__
+ __String Sabitleri (String Literals)__
	+ string sabitleri ve const doğruluğu _(string literals and const correctness)_
	+ string sabitleri ve ömür _(lifespan of string literals)_
	+ özdeş string sabitleri 
	+ string sabitleri ve kaçış sekansları
	+ string sabitlerinin birden fazla satıra yayılması
+ __Gösterici Dizileri (Pointer Arrays)__
+ __Gösterici Gösteren Gösterici (Pointer to pointer)__
+ __void Göstericiler (void Pointers)__
	+ türden bağımsız işlevler _(generic functions)_
	+ standart memset, memcpy, memmove, memchr, memcmp işlevleri
	+ void ** türü
+ __İşlev Göstericileri (Function Pointers)__
	+ genel sentaks
	+ işlevden adrese dönüşüm _(function to pointer conversion)_
	+ işlev göstericileri ve typedef bildirimleri _(function pointers and typedef declarations)_
	+ geri çağrı işlev yapısı _(call-back functions)_
	+ standart qsort ve bsearch işlevleri
	+ işlev gösterici dizileri _(function pointer arrays)_
+ __Çok Boyutlu Diziler (Multi-dimensional Arrays)__
+ __Programların Sonlandırılması__
	+ normal ve anormal sonlanma (normal & abnormal termination)
	+ standart exit, atexit ve abort işlevleri
+ __Dinamik Bellek Yönetimi (Dynamic Memory Management)__
	+ dinamik bellek ihtiyacı ve dinamik ömür kavramı _(dynamic storage)_
	+ heap alanı ve yönetimi _(heap and heap management)_
	+ heap’in parçalara ayrılması _(heap fragmentation)_
	+ standart dinamik bellek yönetimi işlevleri _(standard memory management functions)_
		+ malloc
		+ calloc
		+ realloc
		+ free
		+ bellek sızıntısı _(memory leak)___
		+ boşa düşen göstericiler _(dangling pointers)_
		+ dinamik diziveri yapısı _(dynamic array data structure)_
		
+ __Yer Belirleyiciler (Storage Class Specifiers) ve Tür Niteleyiciler (Type Modifiers)__
	+ yer belirleyiciler _(storage  class specifiers)_
		+ auto anahtar sözcüğü
		+ register anahtar sözcüğü
		+ extern anahtar sözcüğü
		+ static anahtar sözcüğü
		+ modül ve bağlantı kategorileri
			+ iç bağlantı _(internal linkage)_
			+ dış bağlantı _(external linkage)_
		+ global isim alanının kirlenmesi problemi _(global namespace pollution problem)_
	+ tür niteleyicileri _(type modifiers)_
		+ const anahtar sözcüğü ve const semantiği _(const keyword & const semantics)_
		+ volatile anahtar sözcüğü _(volatile keyword)_
		+ restrict anahtar sözcüğü _(restrict keyword)_
+ __Programların sonlandırılması__
	+ Normal sonlanma ve standart exit işlevi _(normal termination & std. exit function)_
		+ standart atexit işlevi _(std. atexit function)_
_	+ Anormal sonlanma ve standart abort işlevi _(abnormal termination)_
	
+ Yapılar _(Structures)_
	+ genel sentaks
		+ yapı öğeleri _(structure members)_
		+ nokta operatörü _(member selection - dot operator)_
		+ ok operatörü _(member selection - arrow operator)_
		+ yapı nesnelerine ilk değer verilmesi _(initialization of structure variables)_
	+ yapı nesneleri ve işlevler _(functions with structure parameters)_
	+ tamamlanmış ve eksik türler _(complete / incomplete types)_
	+ içsel türler _(nested types)_
	+ yapı öğesinin kendi türünden gösterici olması
	+ düğüm kavramı _(nodes)_ 
	+ bağlı liste (linked list) veri yapısı
		+ tekli bağlı listeler _(singly linked lists)_
		+ çifte bağlı listeler _(double linked lists)_
		+ döner bağlı isteler _(rotating lists)_
	+ ikili arama ağacı veri yapısı _(binary search tree data structure)_ 
	+ yapı türlerinden sabitler _(compound literals)_
	+ handle kavramı ve nesne yönelimli C kütüphaneleri
	+ Hizalama ve yapı türleri
		+ hizalama ile ilgili kodlama hataları
		+ offsetof makrosu		
	+ Anonim yapılar
	+ Yapıların içsel türleri _(nested types of structures)_
+ __Standart time Kütüphanesi (time Library)__
	+ takvim zamanı ve ayrıştırılmış zaman
		+ time_t türü
		+ clock_t türü
	+ struct tm yapısı
	+ time, localtime, gmtime, ctime, asctime, strftime, mktime, clock işlevleri

+ __Birlikler (Unions)__
	+ birliklerin kullanım temaları
	+ tagged unions
+ __Numaralandırmalar (Enumarations)__
	+ numaralandırma sabitleri _(enumaration constants)_
	+ enum idiyomları _(enum idioms)_
+ __Bitsel İşlemler (Bitwise Operations)__
	+ bitsel operatörler _(bitwise operators)_
	+ bitsel manipülasyon işlemleri _(bitwise manipulations)_
	+ yapıların bit alanı öğeleri _(bitfield members of structures)_
	+ bitsel işlemler ve birlikler _(bitwise operations & unions)_
	+ bit vektör kullanımı _(bit vectors)_
	+ bitsel düzeyde oluşturulan arama (lookup) tabloları
+ __Komut Satırı Argümanları (Command Line Arguments)__
+ __Dosya İşlemleri (File Operations)__
	+ dosyaların açılması ve kapatılması
		+ dosya açış modları
			+ okuma, yazma ve sona ekleme modları
			+ text modu ve binary mod
		+ fopen, freopen, fclose ve fcloseall işlevleri
	+ okuma ve yazma işlemleri
		+ formatlı okuma yazma işlemleri
			+ fprintf işlevi
			+ fscanf işlevi
			+ fputs işlevi
			+ fgets işlevi
		+ formatsız okuma yazma işlemleri
			+ fgetc işlevi
			+ fputc işlevi
			+ fread işlevi
			+ fwrite işlevi
	+ standart dosya konum göstericisi işlevleri
		+ fseek işlevi
		+ ftell işlevi
		+ rewind işlevi
		+ fsetpos işlevi
		+ fgetpos işlevi
		+ feof, ferror, clearerr, fflush işlevleri
		+ fsetbuf işlevi
		+ ungetc işlevi
	+ Diğer dosya işlevleri ve örnek uygulamalar
+ __Standart signal kütüphanesi__

+ __Önişlemci Komutları – 2__
	+ önişlemci operatörleri _(preprocessor operators)_
		+ `#` dizge yapma operatörü _(stringification operator)_ 
		+ `##` atom yapıştırma operatörü _(token-pasting operator)_ 
		+ defined operatörü _(defined operator)_
	+ öntanımlı sembolik sabitler _(predefined symbolic constants)_
	+ #line komutu
	+ #error komutu
	+ #pragma komutu
+ __assert Makrosu__

+ __Değişken Sayıda Argümanla Çağrılabilen İşlevler (Variadic Functions)__

+ __C99 Standartları ile Eklenen Önemli Öğeler__
	+ long long veri türü _(long long data type)_
	+ for döngü deyiminde yapılan bildirimler
	+ \_Bool anahtar sözcüğü ve _<stdbool.h>_ başlık dosaysı
	+ <stdint.h> başlık dosyası ve standart tür eş isimleri
	+ inline fonksiyonlar _(inline functions)_
	+ değişken boyutlu diziler _(variable length arrays)_
	+ yapıların esnek dizi öğeleri _(flexible array members)_
	+ restrict belirteci _(restrict qualifier)_
	+ bileşik sabitler _(compound literals)_
	+ variadic makrolar _(variadic macros)_
	+ C99 standartları ile eklenen diğer standart kütüphane öğeleri
 
