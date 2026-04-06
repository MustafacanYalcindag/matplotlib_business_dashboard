# 📊 Business Performance Dashboard (Matplotlib & Pandas)

Bu proje, Python'ın en güçlü görselleştirme kütüphanesi olan **Matplotlib** ve veri işleme kütüphanesi **Pandas** kullanılarak hazırlanmıştır. Amacı, karmaşık satış ve operasyon verilerini yönetimin hızlı karar almasını sağlayacak görsel grafiklere (Dashboard) dönüştürmektir.

---

## 🛠️ Uygulanan Teknikler ve Görselleştirme Türleri

Proje içerisinde veri görselleştirmenin temel prensipleri şu grafik türleri üzerinden uygulanmıştır:

### 1. Satış Trend Analizi (Çizgi Grafik - Line Plot)
* **Kullanım:** Zaman içindeki satış değişimlerini ve büyüme ivmesini takip etmek için.
* **Teknik:** `plt.plot()` kullanılarak verilerin periyodik performansı görselleştirilmiştir.

### 2. Ürün ve Kategori Karşılaştırması (Sütun Grafik - Bar Chart)
* **Kullanım:** Hangi ürünün veya kategorinin daha fazla ciro getirdiğini kıyaslamak için.
* **Teknik:** `plt.bar()` ile kategorik veriler arasındaki farklar belirginleştirilmiştir.

### 3. Pazar Payı ve Dağılım Analizi (Pasta Grafik - Pie Chart)
* **Kullanım:** Toplam satışlar içinde hangi kalemlerin ne kadar paya sahip olduğunu göstermek için.
* **Teknik:** `plt.pie()` ve `autopct` parametresi ile yüzdesel dağılım net bir şekilde sunulmuştur.

---

## 📂 Proje İçeriği ve Yapısı

* `matplotlib_business_dashboard.ipynb`: Verilerin görselleştirildiği ve özelleştirildiği ana Jupyter Notebook dosyası.
* **Özelleştirmeler:** Grafiklere eklenen başlıklar (`title`), eksen isimleri (`xlabel`, `ylabel`), göstergeler (`legend`) ve ızgaralar (`grid`) ile profesyonel bir görünüm elde edilmiştir.



[Image of Data visualization dashboard types]


---

## 🛠️ Kurulum ve Çalıştırma

1. Bilgisayarınızda Python yüklü olduğundan emin olun ve gerekli kütüphaneleri kurun:
   ```bash
   pip install matplotlib pandas numpy
