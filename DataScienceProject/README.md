# 📊 Telco Customer Churn Prediction
Bu projede, Kaggle platformundan alınan “WA_Fn-UseC_-Telco-Customer-Churn.csv” veri seti kullanılarak, bir telekomünikasyon şirketinin müşterilerinin aboneliklerini iptal edip etmeyecekleri tahmin edilmeye çalışılmıştır.

## 🔍 Amaç
Geçmiş müşteri bilgilerine dayanarak bir müşterinin abonelikten ayrılma (churn) ihtimalini öngörmektir. Bu sayede şirketlerin olası kayıpları önceden tespit ederek stratejiler geliştirmesi hedeflenmektedir.

## 🧹 Veri Ön İşleme
customerID sütunu tahminle ilgisiz olduğu için veri setinden çıkarılmıştır.

TotalCharges sütununda eksik değer bulunan satırlar veri setinden temizlenmiştir.

Kategorik değişkenler uygun şekilde sayısallaştırılmıştır.

Gerekli durumlarda veri ölçeklendirmesi yapılmıştır.

## 🤖 Kullanılan Modeller
Aşağıdaki makine öğrenmesi algoritmaları Scikit-learn kütüphanesi kullanılarak ve varsayılan parametrelerle uygulanmıştır:

📌 Logistic Regression

📌 Decision Tree Classifier

📌 Support Vector Classifier (LinearSVC)

📌 K-Nearest Neighbors (KNN)

📌 Multi-layer Perceptron Classifier (MLPClassifier / Neural Network)

🔁 Model Değerlendirme
Modellerin performansı, 5-Fold Cross-Validation (karışık veriyle) yöntemi ile değerlendirilmiştir. Her model için hem eğitim hem de test setindeki ortalama doğruluk (accuracy) değerleri hesaplanmıştır.
