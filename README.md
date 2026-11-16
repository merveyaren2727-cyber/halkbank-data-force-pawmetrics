# halkbank-data-force-pawmetrics
Halkbank Data Force 8 haftalık eğitim programı süresince geliştirilen akıllı stok ve bütçe karar destek projesi.
# 🐾 PawMetrics — Akıllı Stok Tahmini ve Bütçe Sapma Karar Destek Sistemi

**Halkbank Data Force** 8 haftalık eğitim programı süresince öğrendiğim algoritmik düşünme, Python, Yapay Zeka (GenAI), Veri Okuryazarlığı, SQL ve Veri Görselleştirme yetkinliklerini gerçek hayat problemine uyarlayarak hafta hafta geliştirdiğim uçtan uca veri projesi.

## 🎯 Projenin Amacı
Evcil hayvan bakım giderlerini, mama/kum tüketim hızını ve aylık bütçe sapmalarını analiz ederek kritik stok seviyeleri için erken uyarı üreten ve bütçe optimizasyonu sağlayan bir karar destek mekanizması kurgulamak.

---

## 🗺️ Geliştirme Günlüğü

| Hafta & Tarih | Modül & Eğitmen | Müfredat Odağı | Projeye Eklenen Katman |
| :--- | :--- | :--- | :--- |
| **1. Hafta**<br>*(10 & 12 Kas 2026)* | **Temel Yazılım ve Algoritma I & II**<br>*(M. Burak Şentürk)* | Karmaşık iş problemlerini algoritmik bir düzleme taşıma, süreçleri mantıksal akışlarla modelleme, Google Colab ile temel Python yapıları ve Low-Code (n8n) otomasyon mantığı. | **v1.0:** Tüm `Evet/Hayır` karar dallarını içeren akış şeması, Python kural motoru (`list`, `for`, `if/else`) ve n8n tetikleyici kurgusu. |

---

## 📌 Hafta 1: Teknik Kavram Çantası (`PawMetrics_v1_Hafta1.ipynb`)

### 🐍 Python Temelleri ve Bilinmesi Gereken Terimler
* **`print()`:** Ekrana bilgi, metin veya hesaplama sonucu yazdırma fonksiyonu.
* **Değişken (`Variable`):** Verileri hafızada tutan etiketler (`=` operatörü ile değer atanır; büyük/küçük harf duyarlıdır ve PEP 8 okunabilirlik standartlarına uyulur).
* **Veri Tipleri (`str`, `int`, `float`):** Metin (`"Mama"`), tam sayı (`15`) ve ondalıklı sayı (`12.5`) tipleri. *(Kritik Kural: Python'da sayılarda binlik ayracı olarak nokta `.` kullanılmaz; `100.000` yerine `100000` yazılır.)*
* **Tip Dönüşümleri (`int()`, `float()`, `str()`):** Farklı veri tiplerini matematiksel işlem veya metin birleştirme için birbirine dönüştürme.
* **Listeler (`list` - `[]`):** Birden fazla veriyi tek bir yapıda sıralı olarak tutan veri yapısı (`kalemler = ["Mama", "Kum", "Vitamin"]`).
* **`len()`:** Bir listenin veya metnin içinde kaç eleman olduğunu sayan fonksiyon.
* **`for` Döngüsü:** Listedeki her bir eleman için aynı hesaplama veya kontrol işlemini sırayla tekrarlayan döngü yapısı.
* **`if / elif / else`:** Belirli bir koşul doğruysa (`True`) veya yanlışsa (`False`) farklı karar dallarını çalıştıran mekanizma.

### ⚡ Low-Code & n8n Mantığı
* **Workflow (İş Akışı):** Birbirine bağlı adımlardan oluşan otomatik süreç şeması.
* **Trigger (Tetikleyici):** Akışı başlatan ilk olay (örneğin belirli bir saatte çalışan *Schedule Trigger* veya yeni veri girişi).
* **Node (Düğüm):** Akış içindeki her bir işlem kutucuğu (veri okuma, hesaplama, e-posta/bildirim gönderme).
* **IF Node:** Koşullu dallanma (`True / False`) ile kritik stok veya bütçe aşımı uyarılarının otomatik yönlendirilmesi.
