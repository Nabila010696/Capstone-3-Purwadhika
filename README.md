# Capstone-3-Purwadhika
Capstone 3 Hotel Booking Machine Learning

#**Business Problem and Machine Learning Goals:**

Hotel menghadapi permasalahan booking cancellation yang berdampak pada kualitas layanan hotel kepada tamu dan juga potensi pendapatan hotel. Machine Learning ini dibutuhkan oleh pihak manajemen hotel untuk dapat melakukan upaya pencegahan dan antisipasi dari pembatalan booking yang dilakukan oleh tamu.

**Metric Evaluation**
Recall : Untuk mendeteksi sebanyak mungkin cancellation yang dilakukan oleh tamu
Akurasi :  Untuk melihat performa keseluruhan (berapa persen prediksi benar dari semua data).

**Conclusion**
Dari hasil uji coba model dan Hiperparameter Tuning, didapati model terbaik adalah Random Forest Classifier dengan parameter berikut :
RandomForestClassifier
class_weight='balanced_subsample', 
criterion='log_loss',
max_features='log2', n_estimators=230,
random_state=1616
