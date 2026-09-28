# Uyku Analizi ve Kalp Krizi Riski Tahmini

Bu proje, "Bilgisayar Mühendisliği Projesi 2" kapsamında geliştirilmiş bir makine öğrenmesi uygulamasıdır. Uyku sağlığı, günlük stres seviyesi ve çeşitli yaşam tarzı faktörlerini analiz ederek bireylerin kalp krizi geçirme riskini tahmin etmeyi amaçlar.

## 📊 Veri Seti
Projede **"Sleep Health and Lifestyle"** veri seti kullanılmıştır (`Sleep_health_and_lifestyle_dataset.csv`). Bu veri seti; yaş, cinsiyet, uyku süresi, uyku kalitesi, fiziksel aktivite seviyesi, stres seviyesi ve vücut kitle indeksi gibi özellikleri içermektedir.

## 🚀 Kullanılan Teknolojiler ve Modeller
- **Programlama Dili:** Python
- **Makine Öğrenmesi Modeli:** XGBoost (`model_xgb.pkl`)
- **Veri Ön İşleme:** Standartlaştırma (StandardScaler - `scaler.pkl`)
- **Geliştirme Ortamı:** Jupyter Notebook (`uykuanalizikalpkriziriskitahmini.ipynb`)

## 📂 Proje İçeriği
- `uykuanalizikalpkriziriskitahmini.ipynb`: Veri analizi, model eğitimi ve değerlendirme aşamalarının bulunduğu kaynak kod dosyası.
- `model_xgb.pkl`: Eğitilmiş XGBoost modelinin dışa aktarılmış hali.
- `scaler.pkl`: Tahminleme sırasında yeni verileri standartlaştırmak için kullanılan ölçekleyici.
- `Proje raporu.pdf` & `Proje raporu.docx`: Projenin detaylı geliştirme raporları ve sunumu.

## 🛠️ Nasıl Çalıştırılır?
1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone https://github.com/azrabahsi/sleep-health-heart-attack-prediction.git
   ```
2. Gerekli Python kütüphanelerini yükleyin (pandas, numpy, scikit-learn, xgboost, vb.).
3. Jupyter Notebook dosyasını açıp hücreleri sırasıyla çalıştırarak analiz sonuçlarını ve model başarısını inceleyebilirsiniz.
4. Kendi verilerinizle tahmin yapmak için `.pkl` dosyalarını bir Python betiğine dahil ederek (load ederek) modeli doğrudan kullanabilirsiniz.

## 📝 Sonuç ve Çıktılar
Projenin detaylı analiz sonuçları, veri görselleştirmeleri ve model performans metrikleri `Proje raporu.pdf` dokümanında ve Jupyter Notebook içerisinde yer almaktadır.
