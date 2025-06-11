# Kütüphane Yönetim Sistemi
# YUSUF KURDOĞLU

**Bu bir kütüphane yönetim sistemi projesidir.**

**Spring Boot kullanarak bir web uygulaması geliştirdim.**

## Teknoloji Yığını
* Spring Boot
* Spring Data JPA
* H2 Veritabanı
* Thymeleaf
* Bootstrap4

## Gereksinimler
Uygulamayı derlemek ve çalıştırmak için ihtiyacınız olanlar:
* JDK 1.8 veya daha yeni
* Maven 3
* Lombok

## Derleme ve Çalıştırma

```bash
mvn clean install && mvn --projects backend spring-boot:run
```

## Port

```
http://localhost:8081
```

## Özellikler

### Temel Fonksiyonalite
- **Kitap Yönetimi:** Kitap ekleme, düzenleme, silme ve listeleme
- **Yazar Yönetimi:** Yazar bilgilerini yönetme
- **Kategori Yönetimi:** Kitap kategorilerini organize etme
- **Yayınevi Yönetimi:** Yayınevi bilgilerini takip etme
- **Arama Fonksiyonu:** Kitapları hızlı arama imkanı

### Teknik Özellikler
- **Responsive Tasarım:** Bootstrap4 ile mobil uyumlu arayüz
- **Veritabanı Entegrasyonu:** H2 embedded veritabanı
- **MVC Mimarisi:** Spring Boot MVC pattern
- **Template Engine:** Thymeleaf ile dinamik sayfa oluşturma
- **ORM:** Spring Data JPA ile veritabanı işlemleri

## Kurulum Adımları

1. **Projeyi klonlayın:**
   ```bash
   git clone https://github.com/kullanici-adi/library-management-sys.git
   cd library-management-sys
   ```

2. **Gerekli araçları kontrol edin:**
   - Java JDK 1.8+ kurulu olmalı
   - Maven 3+ kurulu olmalı

3. **Projeyi derleyin ve çalıştırın:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. **Tarayıcınızda açın:**
   ```
   http://localhost:8081
   ```

## Proje Yapısı

```
src/
├── main/
│   ├── java/
│   │   └── com/mehmetpekdemir/librarymanagementsystem/
│   │       ├── controller/          # Web kontrolcüler
│   │       ├── entity/             # Veritabanı varlıkları
│   │       ├── repository/         # Veri erişim katmanı
│   │       ├── service/            # İş mantığı
│   │       └── exception/          # Hata yönetimi
│   ├── resources/
│   │   ├── templates/              # Thymeleaf şablonları
│   │   └── application.properties  # Uygulama ayarları
│   └── static/                     # CSS, JS dosyaları
└── test/                           # Test dosyaları
```

## Kullanılan Java Konuları

Bu proje aşağıdaki ileri Java konularını içermektedir:

- **Spring Boot Framework:** Modern Java web uygulaması geliştirme
- **Spring Data JPA:** Veritabanı işlemleri ve ORM
- **Dependency Injection:** Spring IoC Container
- **MVC Pattern:** Model-View-Controller mimarisi
- **Annotation-based Configuration:** @Entity, @Controller, @Service
- **Exception Handling:** Merkezi hata yönetimi
- **Template Engine:** Thymeleaf ile dinamik içerik
- **RESTful Architecture:** Web API tasarımı

## Katkıda Bulunma

Bu proje açık kaynak kodludur. Katkıda bulunmak için:

1. Projeyi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'i push edin (`git push origin feature/yeni-ozellik`)
5. Pull Request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

### Features

![Books](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Books.png)
![addBook](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/addBook.png)
![search](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/search.png)
![Authors](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Authors.png)
![Categories](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Categories.png)
![Publishers](https://github.com/mehmetpekdemir/Library-Management-System/blob/master/Photo/Publishers.png)
