#  SQL Server Database – Şiir Web Sitesi | Poem Website Database

##  Türkçe Açıklama
Bu proje, **şiirler, şairler ve kullanıcı etkileşimlerini** yöneten bir **SQL Server veritabanı projesidir**.  
Veritabanı yapısı, `SiirWebSite_Database.sql` dosyasında yer almaktadır.  
Bu dosyayı **SQL Server Management Studio (SSMS)** üzerinde çalıştırarak aynı yapıyı kendi ortamınızda oluşturabilirsiniz.

Veritabanı, bir **şiir paylaşım platformu** için tasarlanmıştır.  
Kullanıcılar şiirleri okuyabilir, yorum yapabilir, beğenebilir ve kendi okuma listelerine ekleyebilirler.  
Şairler, şiirler ve kategoriler arasında **ilişkisel (relational)** bir yapı bulunmaktadır.

---

##  English Description
This project is a **SQL Server database** designed to manage **poems, poets, and user interactions**.  
The database structure is stored in the `SiirWebSite_Database.sql` file.  
You can run this script in **SQL Server Management Studio (SSMS)** to recreate the same database in your local environment.

The database was built for a **poem sharing platform**,  
where users can read poems, post comments, give likes, and save poems to their personal reading lists.  
It features a **relational structure** between poets, poems, and categories.

---

##  Veritabanı Tabloları | Database Tables

| Türkçe Adı | İngilizce Adı | Açıklama / Description |
|-------------|----------------|-------------------------|
| **Kullanici** | User | Kullanıcı bilgilerini içerir / Stores user information. |
| **Sair** | Poet | Şair bilgilerini içerir / Contains poet details. |
| **Siir** | Poem | Şiir başlıklarını, içeriklerini ve tarihlerini tutar / Stores poem titles, contents, and dates. |
| **Kategori** | Category | Şiir kategorilerini içerir / Contains poem categories. |
| **Begeni** | Like | Kullanıcıların şiir beğenilerini tutar / Records user likes on poems. |
| **Yorum** | Comment | Kullanıcı yorumlarını içerir / Stores comments made by users. |
| **OkumaListesi** | ReadingList | Kullanıcıların okuma listelerini içerir / Stores users’ personal reading lists. |

---

##  Saklı Yordam (Stored Procedure)

###  `SairinSiirleri`
Girilen şair adına göre o şaire ait tüm şiirleri listeler.

###  `SairinSiirleri`
Lists all poems written by the poet whose name is provided as a parameter.

---

##  Kullanım | How to Use

**1.** `SiirWebSite_Database.sql` dosyasını açın.  
**2.** SQL Server Management Studio’da yeni bir sorgu penceresi oluşturun.  
**3.** Dosyadaki kodları yapıştırın ve **Execute (F5)** tuşuna basın.  
**4.** Veritabanı otomatik olarak oluşturulacaktır.

**1.** Open the `SiirWebSite_Database.sql` file.  
**2.** Create a new query window in SQL Server Management Studio.  
**3.** Paste the code and press **Execute (F5)**.  
**4.** The database will be created automatically.

---

## Ek Bilgiler | Additional Info
-  Geliştirme Ortamı / Environment: Microsoft SQL Server 2022  
-  Dosya Adı / File Name: `SiirWebSite_Database.sql`  
-  Veritabanı Türü / Database Type: Relational (RDBMS)  
-  Geliştirici / Developer: **Zişan Yüce**  

---

## Açıklama
Bu veritabanı, yazılım projelerinde **arka uç (backend)** tarafında veri yönetimi mantığını göstermek için oluşturulmuştur.  
İleride web uygulaması veya mobil uygulama projelerine kolayca entegre edilebilir.

## Description
This database was created to demonstrate **backend data management** in software projects.  
It can easily be integrated into future web or mobile applications.
