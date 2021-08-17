# C Programlama Dili Kursu İçeriği

+ __Kursun Tanıtımı__
+ __C Programlama Dilinin Genel Tanıtımı__
	+ programlama dillerini birbirinden ayıran kriterler
		+ declarative ve imperative diller
		+ programlama paradigmaları
		+ seviye (level)
		+ mülkiyet
		+ statik ve dinamik tür kavramları
		+ prosedürel programlama ve C dili
	+ C dilinin kullanım alanları
	+ C dilinin temel özellikleri
	+ C dilinin tarihsel gelişimi ve C Standartları
		+ Klasik C
		+ C89
		+ C99
		+ C11
	+ C ve C++ ilişkisi

+ __Temel Kavramlar__
	+ atom (token) kavramı
		+ atom kategorileri
			+ anahtar sözcükler (keywords)
			+ isimler (identifiers)
			+ sabitler (constants - literals)
			+ string literalleri (string literals)
			+ operatörler (operators)
		+ atomlarına ayırma (tokenizing)
		+ en uzun atom kuralı (maximum munch)
	+ sayı sistemleri
		+ işaretli ve işaretsiz ikilik sayı sistemi
		+ dönüşümler
		+ bire tümleme işlemi
		+ ikiye tümleme işlemi
		+ onaltılık sayı sistemi
		+ sekizlik sayı sistemi
	+ nesneler (objects)
		+ tür (type) kavramı
		+ nesnelerin bellek alanları (storage)
		+ temel türler (fundemantal types)
		+ programcı tarafından tanımlanan türler (user defined types)
	+ ifadeler (expressions)
		+ ifade kategorileri (value categories)
			+ sol taraf değeri ifadesi (L value expression)
			+ sağ taraf değeri ifadesi (R value expression)
		+ sabit ifadesi (constant expression)
		
+ __Bir C Programı Oluşturmak__
	+ metin düzenleyici programlar ve text dosyaları
	+ kaynak dosya ve çeviri birimi
	+ derleyici program ve derleme süreci
		+ derleyici bulgu iletileri
		+ tanımsız davranış (undefined behavior)
		+ derleyiciye bağlı durumlar (implementation defined behavior)
		+ derleyici programların lojik kontrolleri
		+ derleyiciler ve kod optimizasyonu
		+ derleyici eklentileri (compiler extensions)
	+ önişlemci program (preprocessor)
	+ bağlayıcı program (linker) bağlama zamanı
	+ ide’ler ve yardımcı programlar
		+ statik kod analizi yapan programlar
		+ hata ayıklayıcı programlar
		
+ __Veri Türleri (Data Types)__
	+ varsayılan türler (fundemental types)
		+ tamsayı türleri (integer types)
		+ gerçek sayı türleri (floating types)
	+ programcı tarafından oluşturulan türler (user defined types)
	
+ __Bildirim ve Tanımlama (Declarations & Definitions)__
	+ bildirimler ve deyimler (declarations and statements)
	+ ilk değer verme (initialization)
	+ bildirim listesi
	+ tanımlama (definition)
+ __Kapsam ve İsim arama (Scope & Name Lookup)__
	+ kapsam (scope)
		+ kapsam kategorileri
			+ block scope
			+ file scope
			+ function prototype scope
			+ function scope
	+ isim arama (name lookup)
	+ isim çakışmaları (name collision)
	
+ __Ömür Kavramı (Storage Duration)__
	+ otomatik ömür (automatic storage class)
	+ statik ömür (static storage class)
	+ dinamik ömür (dynamic storage class)
	
+ __İşlevler (Functions)__
	+ işlevlerin tanımlanması (function definitions)
		+ işlevlerin parametre değişkenleri
		+ işlevlerin geri dönüş değerleri
		+ değerle çağrı (call by value)
		+ referansla çağrılan işlevler (call by reference)
		+ void işlevler
	+ return deyimi (return statement)
		+ ifadeli ve ifadesiz return deyimleri
	+ saf (pure) ve saf olmayan (impure) işlevler
	+ işlevlerin çağrılması (function calls)
		+ işlev çağrılarından elde edilen değerlerin kullanılması
	+ inline işlevler (inline functions)
	+ işlevlerin bildirilmesi (function declarations)
	
+ __Standart Kütüphane (Standard Library)__
	+ standart kütüphanenin varlık nedenleri
		+ ortak arayüz (common interface) ilkesi
		+ taşınabilirlik (portability)
		+ kodların tekrar kullanımı (code reuse)
	+ standart formatlı giriş çıkış işlevleri
		+ standart giriş akımı (standard input stream)
		+ standart çıkış akımları (standard output stream)
		+ standart hata akımı (standard error stream)
		+ akımların yönlendirilmesi (direction of the streams)
		+ printf işlevi
		+ scanf işlevi
	+ standart formatsız giriş ve çıkış işlemleri
		+ getchar
		+ putchar
	+ standart başlık dosyaları
	+ standart math kütüphanesi

+ __Operatörler (Operators)__
	+ temel kavramlar
		+ operatörlerin değer üretmesi
		+ operatör önceliği
		+ öncelik yönü (associativity)
		+ yan etki (side effect)
		+ yan etki noktası (sequence point)
	+ aritmetik operatörler
		+ toplama, çıkarma, çarpma, bölme ve kalan operatörleri
		+ işaret operatörleri (sign operators)
		+ artırma ve eksiltme operatörleri (increment & decrement operators)
	+ karşılaştırma operatörleri
		+ karşılaştırma idiyomları
		+ tipik hatalar
	+ lojik operatörler
		+ lojik yorumlama
		+ kısa devre davranışı
		+ tipik hatalar
		+ lojik ifadeler
		+ idiyomlar
	+ atama operatörleri
		+ atama operatörlerinin değer üretmesi
		+ yalın atama operatörü
		+ işlemli atama (compound assignment) operatörleri
		+ idiyomlar
	+ virgül operatörü
	+ öncelik operatörü
+ __Sabitler (Constants)__
	+ sabitlerin türleri
		+ tamsayı sabitleri (integer constants)
		+ gerçek sayı sabitleri (floating constants)
			+ üstel (scientific) notasyon
		+ karakter sabitleri
			+ kaçış sekansları (escape sequences)
			
+ __Kontrol Deyimleri__
	+ if deyimi
		+ genel sentaks
		+ else if merdiveni
		+ tipik yapılan hatalar
		+ test işlevleri
	+ döngü deyimleri
		+ while döngü deyimi
		+ do while döngü deyimi
		+ for döngü deyimi
		+ break deyimi
		+ continue deyimi
		+ iç içe döngüler
		+ döngü idiyomları
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
	+ otomatik tür dönüşümleri (implicit type conversions)
	+ tür dönüştürme operatörü (type-cast operator)
	+ tür dönüşümleri ve veri kaybı
	
+ __typedef bildirimleri – 1__
	+ tür eş isimleri (type alias) ve taşınabilirlik
	+ standart typedef türleri
		+ size_t tür eş ismi
		+ ptrdiff_t tür ismi
		+ time_t ve clock_t tür isimleri
	+ stdint başlık dosyası
	+ stdbool başlık dosyası
	
+ __Rastgele Sayı Üretimi ve Programlamadaki Önemi__
	+ gerçek ve sözde rastgele sayı üretimi
	+ rastgele sayı üretim algoritmaları
	+ tohum değeri (seed value)
	+ standart rand ve srand işlevleri
+ __sizeof Operatörü__
+ __Diziler (arrays)__
	+ veri yapıları ve algoritmalara giriş
		+ veri yapıları
		+ algoritmanın karmaşıklığı (complexity of algorithms)
		+ big O notasyonu
	+ tamsayı ve gerçek sayı dizileri
	+ dizilere ilk değer verme
		+ designated initializer (C99)
	+ yazılar ve yazı tutan char diziler
		+ null karakter
		+ yazılara ilişkin temel algoritmalar
+ __Göstericiler (pointers)__
	+ temel kavramlar
		+ adres ifadeleri
		+ gösterici değişkenler
		+ göstericiler ve storage
	+ adres operatörü
	+ içerik (dereferencing) operatörü 
	+ diziden adrese dönüşüm (aray to pointer conversion)
	+ geçerli (valid) ve geçersiz (invalid) göstericiler
	+ göstericiler ve const semantiği
		+ kendisi const göstericiler
		+ okuma amaçlı const göstericiler
		+ const semantiği ve tür dönüşümleri
	+ gösterici aritmetiği
	+ indeks operatörü
	+ diziler üstünde işlem yapan işlevler
	+ göstericiler ve karşılaştırma işlemleri
	+ adres döndüren işlevler (function returning pointers)
	+ NULL gösterici
	+ endianness, little endian, big endian kavramları
	+ gösterici hataları
+ __Standart string Kütüphanesi (string library)__
	+ strlen, strcpy, strcat, strncpy, strncat işlevleri
	+ arama işlevleri: strchr, strnchr, strstr, strpbrk, strspn, strcspn
	+ karşılaştırma işlevleri : strcmp, strcoll, stricmp
	+ strtok işlevi
	+ diğer standart string işlevleri
	+ örnek bazı Posix işlevleri
+ __Standart stddef Kütüphanesi__
+ __String Sabitleri (String Literals)__
	+ string sabitleri ve const doğruluğu (string literals and const correctness)
	+ string sabitleri ve ömür
	+ özdeş string sabitleri
	+ string sabitleri ve kaçış ekansları
	+ string sabitlerinin birden fazla satıra yayılması
+ __Gösterici Dizileri (Pointer Arrays)__
+ __Gösterici Gösteren Gösterici (Pointer to pointer)__
+ __void Göstericiler (void Pointers)__
	+ türden bağımsız işlevler (generic functions)
	+ standart memset, memcpy, memmove, memchr, memcmp işlevleri
	+ void ** türü
+ __İşlev Göstericileri (Function Pointers)__
	+ genel sentaks
	+ işlevden adrese dönüşüm (function to pointer conversion)
	+ işlev göstericileri ve typedef bildirimleri
	+ geri çağrı (call-back) işlev yapısı
	+ standart qsort ve bsearch işlevleri
	+ işlev gösterici dizileri (function pointer arrays)
+ __Çok Boyutlu Diziler (Multi-dimensional Arrays)__
+ __Programların Sonlandırılması__
	+ normal ve anormal sonlanma (normal & abnormal termination)
	+ standart exit, atexit ve abort işlevleri
+ __Dinamik Bellek Yönetimi (Dynamic Memory Management)__
	+ dinamik bellek ihtiyacı ve dinamik ömür kavramı
	+ heap alanı ve yönetimi
	+ heap’in parçalara ayrılması (fragmentation)
	+ standart dinamik bellek yönetimi işlevleri
		+ malloc
		+ calloc
		+ realloc
		+ free
		+ bellek sızıntısı (memory leak)
		+ boşa düşen göstericiler (dangling pointers)
		+ dinamik dizi (dynamic array) veri yapısı
		
+ __Yer Belirleyiciler (Storage Class Specifiers) ve Tür Niteleyiciler (Type Modifiers)__
	+ yer belirleyiciler (storage  class specifiers)
		+ auto anahtar sözcüğü
		+ register anahtar sözcüğü
		+ extern anahtar sözcüğü
		+ static anahtar sözcüğü
		+ modül ve bağlantı kategorileri
			+ iç bağlantı (internal linkage)
			+ dış bağlantı (external linkage)
		+ global isim alanının kirlenmesi problemi
	+ tür niteleyiciler (type modifiers)
		+ const anahtar sözcüğü ve const semantiği
		+ volatile anahtar sözcükleri
		+ restrict anahtar sözcüğü
+ __Programların sonlandırılması__
	+ Normal sonlanma ve standart exit işlevi (normal termination)
		+ standart atexit işlevi
	+ Anormal sonlanma ve standart abort işlevi (abnormal termination)
	
+ Yapılar (Structures)
	+ genel sentaks
		+ yapı öğeleri
		+ nokta operatörü
		+ ok operatörü
		+ yapı nesnelerine ilk değer verilmesi
	+ yapı nesneleri ve işlevler
	+ tamamlanmış ve eksik türler (complete / incomplete types)
	+ içsel türler (nested types)
	+ yapı öğesinin kendi türünden gösterici olması
	+ düğüm (node) kavramı
	+ bağlı liste (linked list) veri yapısı
		+ tekli bağlı listeler (singly linked lists)
		+ çifte bağlı listeler (double linked lists)
		+ döner bağlı isteler (rotating lists)
	+ ikili arama ağacı (binary search tree) veri yapısı
	+ yapı türlerinden sabitler (compound literals)
	+ handle kavramı ve nesne yönelimli C kütüphaneleri
	+ Hizalama ve yapı türleri
		+ hizalama ile ilgili kodlama hataları
		+ offsetof makrosu		
	+ Anonim yapılar
	+ Yapıların içsel türleri (nested types)
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
	+ numaralandırma sabitleri
	+ enum idiyomları
+ __Bitsel İşlemler (Bitwise Operations)__
	+ bitsel operatörler
	+ bitsel manipülasyon işlemleri
	+ yapıların bit alanı öğeleri
	+ bitsel işlemler ve birlikler
	+ bit vektör kullanımı
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
	+ önişlemci operatörleri
		+ `#` dizge yapma (stringification) operatörü
		+ `##` atom yapıştırma (token-pasting) operatörü
		+ defined operatörü
	+ öntanımlı sembolik sabitler (predefined symbolic constants)
	+ #line komutu
	+ #error komutu
	+ #pragma komutu
+ __assert Makrosu__

+ __Değişken Sayıda Argümanla Çağrılabilen İşlevler (Variadic Functions)__

+ __C99 Standartları ile Eklenen Önemli Öğeler__
	+ long long veri türü 
	+ for döngü deyiminde yapılan bildirimler
	+ _Bool anahtar sözcüğü ve <stdbool.h> başlık dosaysı
	+ <stdint.h> başlık dosyası ve standart tür eş isimleri
	+ inline fonksiyonlar (inline functions)
	+ değişken boyutlu diziler (variable length arrays)
	+ yapıların esnek dizi öğeleri (flexible array members)
	+ restrict belirteci
	+ bileşik sabitler (compound literals)
	+ variadic makrolar (variadic macros)
	+ C99 standartları ile eklenen diğer standart kütüphane öğeleri
 
