# 🛒 Retail Sales Analysis – SQL Project

## 📌 Proje Hakkında

Bu proje, bir perakende satış veritabanı üzerinde SQL kullanarak veri keşfi (EDA), veri temizleme ve iş sorularını analiz etmeyi hedeflemektedir. Veri analizi alanında yeni başlayanlar için tasarlanmış bu proje, SQL becerilerini uygulamalı olarak geliştirmenizi sağlar.

## 🎯 Proje Amaçları

- Perakende satış verisi içeren bir SQL veritabanı kurmak
- Eksik veya hatalı verileri tespit edip temizlemek
- SQL kullanarak temel EDA (Exploratory Data Analysis) işlemlerini gerçekleştirmek
- İşe yönelik soruları SQL sorguları ile yanıtlayarak içgörüler elde etmek

## 🗂️ Veritabanı Yapısı

- **Veritabanı adı:** `p1_retail_db`
- **Tablo adı:** `retail_sales`
- **Kolonlar:**
  - `transactions_id`: İşlem ID'si (INT, PRIMARY KEY)
  - `sale_date`: Satış tarihi (DATE)
  - `sale_time`: Satış saati (TIME)
  - `customer_id`: Müşteri ID'si (INT)
  - `gender`: Cinsiyet (VARCHAR)
  - `age`: Yaş (INT)
  - `category`: Ürün kategorisi (VARCHAR)
  - `quantity`: Satılan ürün adedi (INT)
  - `price_per_unit`: Birim fiyat (FLOAT)
  - `cogs`: Satış maliyeti (FLOAT)
  - `total_sale`: Toplam satış tutarı (FLOAT)

## 🧹 Veri Temizleme ve Keşif Aşamaları

- Toplam kayıt sayısı ve benzersiz müşteri sayısı hesaplandı
- Kategori çeşitleri listelendi
- Null değer içeren satırlar belirlendi ve veri temizliği yapıldı
- Temiz veri üzerinden analiz adımlarına geçildi

## 🔍 SQL ile Yapılan Analizler

- Belirli bir tarihteki satışları listeleme
- Kasım 2022'de, "Clothing" kategorisinden 4’ten fazla ürün satılan işlemleri bulma
- Her kategori için toplam satış tutarı ve işlem sayısı hesaplama
- “Beauty” kategorisinden alışveriş yapan müşterilerin ortalama yaşını bulma
- 1000 TL üzerindeki satışları filtreleme
- Her kategori ve cinsiyet için işlem sayılarını bulma
- Her yılın en yüksek ortalama satış yaptığı ayı belirleme
- En çok harcama yapan 5 müşteriyi listeleme
- Her kategoriye ait benzersiz müşteri sayısını bulma
- Günün saatine göre sipariş sayılarını (Morning, Afternoon, Evening) analiz etme

## 📊 Bulgular ve İçgörüler

- Yüksek değerli işlemler, premium müşteri segmentine işaret ediyor
- Giyim ve güzellik kategorileri satışlarda öne çıkıyor
- Ay bazlı analizlerle sezonluk satış trendleri ortaya kondu
- En çok alışveriş yapan müşteriler belirlendi

## 📁 Proje Dosyaları

- `database_setup.sql`: Veritabanı ve tablo oluşturma scripti
- `analysis_queries.sql`: Tüm analiz sorgularını içeren dosya

## 🚀 Nasıl Kullanılır?

1. Bu repo'yu bilgisayarınıza klonlayın: git clone https://github.com/kullanici-adi/retail-sales-sql-analysis.git
2. SQL veritabanınızda `p1_retail_db` veritabanını ve `retail_sales` tablosunu oluşturmak için `database_setup.sql` dosyasını çalıştırın.
3. `sql_query.sql` içindeki sorguları sırasıyla çalıştırarak analizleri yapabilirsiniz.

## 👨‍💻 Kullanılan Teknolojiler

- SQL (PostgreSQL / MySQL uyumlu)
- Veri analizi ve veri temizleme işlemleri için temel SQL fonksiyonları (GROUP BY, HAVING, JOIN, CTE, RANK vs.)

## 📌 Notlar

- Proje örnek bir veri seti üzerinde yürütülmüştür. Gerçek bir ticari veriye ait değildir.
- Eğitim ve portföy geliştirme amacıyla hazırlanmıştır.

---

## 📧 İletişim

Herhangi bir öneri, yorum ya da iş birliği için bana ulaşabilirsiniz:

- 📬 Email: [ismailumutluoglu10@gmail.com]
---

> Bu proje, SQL ile veri analizi becerilerimi geliştirmek amacıyla hazırlanmıştır. Gerçek dünyadan alınan iş sorularına SQL ile yanıt vermeyi deneyimledim. 💡
