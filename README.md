# MongoDB Nedir?

MongoDB, 2009 yılında geliştirilmiş, açık kaynak kodlu bir **NoSQL** veritabanıdır.

Günümüzün veritabanı ihtiyaçları giderek karmaşık hale gelmekte ve geleneksel SQL tabanlı veritabanları bu talepleri karşılamakta yetersiz kalabilmektedir. İşte bu noktada MongoDB devreye girer; **NoSQL** (Not Only SQL) paradigmasının öncüsüdür ve geleneksel yapılara göre birçok farklılık sunar.

> *Piyasada Cassandra, BigTable ve Dynamo gibi başka NoSQL veritabanları da bulunmaktadır.*

---

## MongoDB Özellikleri

MongoDB, en gelişmiş açık kaynaklı nesne-ilişkisel veritabanı yönetim sistemlerinden (ORDBMS) biridir ve birçok önemli özellikle donatılmıştır.

### 1. Veri Tipleri ve Esnek Şema
* MongoDB, JSON benzeri **BSON (Binary JSON)** belgeleri kullanır; bu sayede veriler daha esnek bir şekilde depolanır ve modellenir.
* SQL veritabanları sabit bir şema gerektirirken, MongoDB **esnek bir şema** ile çalışır.
* Bu özellik, veritabanının uygulamanızın ihtiyaçlarına daha iyi uyarlanabilmesini sağlar.

### 2. Yatay Ölçeklenebilirlik (Horizontal Scalability)
* MongoDB **yatay ölçeklenebilir** bir yapıdadır; veri ve trafik arttıkça sisteme yeni sunucular eklemek kolaydır.
* Büyüyen uygulamalar için büyük bir avantajdır, oysa geleneksel SQL veritabanları genellikle dikey ölçeklenebilirlik ile sınırlıdır.

### 3. Hızlı Okuma ve Yazma
* Yüksek performanslı uygulamaları destekleyecek şekilde **hızlı okuma ve yazma** işlemleri sağlar.
* Verilerin veritabanı hafızasına yüklenebilmesi, hızlı erişimi mümkün kılar.

### 4. Zengin Sorgu Yetenekleri
* Karmaşık sorguları kolayca işleyebilir ve belgeler üzerinde **indeksleme** yapabilir.
* Bu yetenekler, veri çekerken ve sorgularken daha hızlı sonuç almanızı sağlar.

### 5. Yüksek Kullanılabilirlik ve Yedekleme
* **Yüksek kullanılabilirlik (High Availability)** için yerleşik destek sunar ve veri yedeklemeyi kolaylaştırır.
* Veri kaybını önlemek ve kesintisiz hizmet sunmak için bu özellikler kritiktir.

### 6. Topluluk ve Destek
* Büyük bir kullanıcı topluluğuna sahiptir, bu sayede birçok kaynak ve destek bulunabilir.
* **MongoDB Atlas** gibi yönetilen hizmetler ile bulut tabanlı çözümler de sunulmaktadır.
