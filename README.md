# taxi-fare-prediction

Bu proje, taksi yolculuk ücretlerini mesafe, süre, hava durumu, trafik yoğunluğu, zaman dilimi gibi faktörlere göre tahmin etmeyi amaçlamaktadır.

Kullanılan yöntem: Linear Regression
Öncesinde veri temizleme, eksik veri doldurma, one-hot encoding ve scaler işlemleri yapılmıştır.

📁 Veri Seti Özellikleri

Veri seti şunları içerir:

Trip_Distance_km: Yolculuk mesafesi

Trip_Duration_Minutes: Toplam süre

Traffic_Conditions: Low / Medium / High

Weather: Clear / Rain / Snow

Time_of_Day: Morning / Afternoon / Evening

Passenger_Count: Yolcu sayısı

Fare Amount (Trip_Price): Hedef değişken

Toplam: ~1.000 satır

🔧 Kullanılan Teknikler
✔ Veri Temizleme

Null değerlerin silinmesi / medyan ile doldurulması

Bozuk tiplerin dönüştürülmesi

Outlier analizi

✔ Feature Engineering

One-Hot Encoding

Label Encoding

StandardScaler ile ölçekleme

✔ Model

LinearRegression

Train-test split (%80–%20)

✔ Performans Metrikleri

R²

MAE

RMSE

| Metrik | Değer |
| ------ | ----- |
| R²     | 0.87  |
| MAE    | 4.2   |
| RMSE   | 6.1   |
