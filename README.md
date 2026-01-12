# Titanic Veri Analizi ve Hayatta Kalma Tahmini

Bu proje, Veri Analizi dersi dönem projesi kapsamında hazırlanmıştır.

## 🎯 Projenin Amacı
Titanic faciasındaki yolcuların yaş, cinsiyet, sınıf gibi demografik özelliklerini inceleyerek; makine öğrenmesi algoritmaları ile yolcuların hayatta kalıp kalmayacağını tahmin eden bir model geliştirmektir.

## 📂 Kullanılan Veri Seti
Kaggle platformundan alınan "Titanic - Machine Learning from Disaster" veri seti kullanılmıştır.
- **Veri Kaynağı:** Kaggle
- **Gözlem Sayısı:** 891 Yolcu
- **Hedef Değişken:** Survived (0: Öldü, 1: Yaşadı)

## ⚙️ Kullanılan Yöntemler
Proje Python dili kullanılarak, Google Colab ortamında geliştirilmiştir.
1. **Veri Ön İşleme:** Eksik veriler (Age) doldurulmuş, gereksiz sütunlar (Cabin, Name, Ticket) çıkarılmış ve kategorik veriler (Sex, Embarked) sayısallaştırılmıştır.
2. **Görselleştirme:** Matplotlib ve Seaborn kütüphaneleri ile veri dağılımı incelenmiştir.
3. **Modelleme:** İki farklı algoritma kullanılmıştır:
    - Lojistik Regresyon (Logistic Regression)
    - Rastgele Orman (Random Forest)

## 📊 Sonuçlar
Yapılan testler sonucunda modellerin doğruluk oranları şu şekildedir:
- **Lojistik Regresyon Başarısı:** %78.09
- **Random Forest Başarısı:** %76.40

Lojistik Regresyon modeli, bu veri setinde daha kararlı ve başarılı sonuçlar vermiştir.
