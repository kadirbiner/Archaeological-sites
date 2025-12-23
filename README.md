# 🏛️ Archaeological Sites: Risk Analysis & Clustering Portal

Bu proje, arkeolojik alan verileri üzerinde makine öğrenmesi ve coğrafi görselleştirme teknikleri kullanarak hazırladığım tez çalışmamın dijital çıktılarını içermektedir. Proje; risk faktörlerini analiz eder, yoğunluk haritaları oluşturur ve kümeleme algoritmalarıyla alanları gruplandırır.

## 🚀 Canlı Dashboard ve Haritalar
Analiz sonuçlarını interaktif olarak incelemek için aşağıdaki linke tıklayabilirsiniz:
👉 **[ARKEOLOJİK ANALİZ PORTALI](https://kadirbiner.github.io/Archaeological-sites/)**

---

## 🔍 Proje Kapsamı ve Analizler

Proje kapsamında arkeolojik envanter verileri dört farklı perspektiften incelenmiştir:

### 1. Bütünleşik Risk Dashboard (Öne Çıkan)
Arkeolojik alanların karşı karşıya olduğu **Kaçak Kazı, Yapılaşma, Tarımsal Faaliyetler** gibi risklerin Türkiye genelindeki dağılımını gösterir. Sağ ve sol paneller aracılığıyla canlı istatistiksel veri sunar.

### 2. K-Means Kümeleme (K=3)
Veri setindeki alanları coğrafi koordinatları ve benzerlik puanlarına göre 3 ana kümeye ayırarak bölgesel odak noktalarını belirler.

### 3. HDBSCAN Analizi
Hiyerarşik ve yoğunluk tabanlı bir yaklaşım kullanarak, doğal kümelenme eğilimlerini saptar ve veri gürültüsünü (outliers) başarılı bir şekilde filtreler.

### 4. DBSCAN (20km EPS)
Belirli bir coğrafi yarıçap (20km) içindeki yoğunlukları baz alarak, riskin en çok kümelendiği kritik bölgeleri tespit eder.

---

## 🛠️ Teknik Altyapı
Proje geliştirilirken aşağıdaki teknolojiler kullanılmıştır:

* **Python:** Veri işleme ve analiz.
* **Folium & Leaflet.js:** Yüksek performanslı interaktif harita renderlama.
* **Scikit-learn:** Makine öğrenmesi ve kümeleme modelleri.
* **Bootstrap 5:** Kullanıcı dostu web arayüzü tasarımı.
* **GitHub Pages:** Web yayını ve barındırma.

---

## 📂 Dosya Yapısı
* `index.html`: Proje ana sayfası (Arayüz).
* `Profesyonel_Arkeo_Harita.html`: Ana Risk Dashboard dosyası.
* `k-means_k3_harita.html`: K-Means kümeleme sonuçları.
* `hdbscan_harita.html`: HDBSCAN yoğunluk analizi.
* `dbscan_eps20km.html`: DBSCAN mekansal analiz sonuçları.

---

## 👤 İletişim
**Kadir Biner** Proje ile ilgili sorularınız veya iş birliği için GitHub üzerinden iletişime geçebilirsiniz.

---
*Bu çalışma akademik amaçlarla hazırlanmış bir tez çıktısıdır.*
