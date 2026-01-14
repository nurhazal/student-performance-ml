# Öğrencilerin Sınav Performansının Makine Öğrenmesi ile Tahmini – Python, Scikit-Learn, Pandas

Bu proje, öğrencilerin sınavlardaki performansını tahmin etmek için çeşitli makine öğrenmesi modelleri uygulayan bir veri bilimi çalışmasıdır.

## Proje Amacı
- Öğrencilerin matematik, okuma ve yazma puanları ile başarı durumlarını ("geçti" veya "kaldı") tahmin etmek.
- Farklı makine öğrenmesi algoritmalarını karşılaştırmak ve performanslarını ölçmek.

## Kullanılan Veri
- Dataset: `StudentsPerformance.csv`
- Özellikler:
  - gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score
- Hedef değişken: `result` (geçti/kaldı)

## Kullanılan Teknolojiler
- Python
- Pandas, NumPy (veri işleme)
- Matplotlib, Seaborn (görselleştirme)
- Scikit-Learn (makine öğrenmesi)
  - Modeller: Decision Tree, Random Forest, KNN, Naive Bayes, Logistic Regression, SVM, LDA
  - Değerlendirme metrikleri: Accuracy, Precision, Recall, F1-score
  - Cross-validation: Stratified 5-fold

## Proje Özellikleri
- Veri ön işleme: Label encoding ve normalizasyon uygulandı.
- Modellerin performansı karşılaştırıldı ve görselleştirildi.
- Confusion matrix ve ROC eğrileri ile model doğruluğu analiz edildi.
- Test seti üzerinde tahmin sonuçları üretildi ve yanlış tahmin edilen öğrenciler tespit edildi.

