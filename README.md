# Musteri-Memnuniyeti-Tahmin-Modellemesi
Müşteri memnuniyetini tahmin etmek için makine öğrenmesi teknikleri kullanılan bir proje. Veri işleme için pandas, numpy; görselleştirme için seaborn, matplotlib; modelleme için RandomForestRegressor ve LogisticRegression kullanılmıştır. Performans metrikleriyle değerlendirilmiştir.

## 📂 Proje İçeriği

Bu çalışma kapsamında aşağıdaki adımlar izlenmiştir:

1.  **Veri Keşfi (EDA):** Veri setinin yapısı incelendi, eksik veriler kontrol edildi ve istatistiksel özetler çıkarıldı.
2.  **Veri Görselleştirme:**
    * Eksik verilerin `Heatmap` ile kontrolü.
    * Yaş dağılımları ve yaş gruplarına göre memnuniyet analizleri.
    * Ülke bazlı memnuniyet karşılaştırmaları.
    * Satın alma sıklığı ve sadakat seviyesinin memnuniyete etkisi.
3.  **Veri Ön İşleme:** Kategorik değişkenler (Cinsiyet, Ülke, Sadakat Seviyesi vb.) `LabelEncoder` kullanılarak sayısal verilere dönüştürüldü.
4.  **Makine Öğrenmesi Modeli:**
    * Algoritma: **Random Forest Regressor**
    * Hedef Değişken: `SatisfactionScore` (Memnuniyet Skoru)
    * Modelin doğruluk oranı hesaplandı.

## 🛠 Kullanılan Kütüphaneler

Projenin çalışması için aşağıdaki Python kütüphaneleri gereklidir:

* **Pandas:** Veri manipülasyonu için.
* **NumPy:** Sayısal işlemler için.
* **Matplotlib & Seaborn:** Veri görselleştirme için.
* **Scikit-Learn:** Makine öğrenmesi modeli ve veri ön işleme için.

## 🚀 Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için:

1.  Bu repoyu klonlayın veya indirin.
2.  Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn
    ```
3.  `customer_satisfaction7.csv` dosyasının notebook ile aynı dizinde olduğundan emin olun.
4.  `.ipynb` uzantılı Jupyter Notebook dosyasını çalıştırın.

## 📊 Örnek Analiz Sonuçları

Proje içerisinde yapılan analizlerden bazı çıkarımlar:
* Müşteri sadakat seviyesi arttıkça memnuniyet skorlarında belirgin bir değişim gözlemlenmiştir.
* Belirli yaş aralıklarındaki müşterilerin memnuniyet eğilimleri analiz edilmiştir.
