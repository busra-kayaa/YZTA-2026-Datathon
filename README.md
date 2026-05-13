# YZTA 2026 Datathon 

Bu depo, **Yapay Zeka ve Teknoloji Akademisi (YZTA) 2026 Datathon** yarışması kapsamında geliştirilen tahmin modellerini, veri analizi süreçlerini ve en yüksek skoru üreten submission (teslim) dosyalarını içermektedir. 

Yarışma sürecinde geliştirilen çeşitli modeller arasından en iyi sonuç veren 2 farklı yaklaşım seçilerek bu repoya eklenmiştir.

## 📂 Depo İçeriği

*   **`train.csv`**: Modellerin eğitilmesi için kullanılan ana veri seti.
*   **`test_x.csv`**: Tahminlerin üretildiği, hedef değişkeni içermeyen test veri seti.
*   **`sample_submission.csv`**: Yarışma platformunun beklediği örnek çıktı formatı.
*   **`submission.ipynb`**: En iyi performans gösteren modellerden birinin veri ön işleme, özellik mühendisliği (feature engineering) ve modelleme adımlarını içeren Jupyter Notebook dosyası.
*   **`submission.csv`**: `submission.ipynb` dosyasından elde edilen tahmin sonuçları.
*   **`datathon_busra_version_6.ipynb`**: Farklı hiperparametre optimizasyonları veya model mimarileri denenerek elde edilen alternatif en iyi 2. yaklaşımın kodları.
*   **`datathon_busra_version_6.csv`**: 6. versiyon notebook'undan elde edilen tahmin sonuçları.

## 🚀 Modelleme Yaklaşımı ve Metodoloji

Bu projede temel olarak aşağıdaki adımlar izlenmiştir:
1.  **Keşifçi Veri Analizi (EDA):** Verideki eksik değerlerin tespiti, aykırı değer analizi ve değişkenler arası korelasyonların incelenmesi.
2.  **Özellik Mühendisliği (Feature Engineering):** [Buraya yaptığın en önemli 1-2 feature engineering adımını yazabilirsin, örn: "Tarih değişkenlerinden yeni özellikler üretildi, kategorik veriler encode edildi."]
3.  **Model Seçimi ve Eğitimi:** Proje kapsamında [Örn: CatBoost, XGBoost veya LightGBM] gibi makine öğrenmesi algoritmaları kullanılmıştır. 
4.  **Hiperparametre Optimizasyonu:** Modellerin performansını maksimize etmek için [Örn: Optuna kullanarak çapraz doğrulama (Cross-Validation) ile parametre arayışı] gerçekleştirilmiştir.
