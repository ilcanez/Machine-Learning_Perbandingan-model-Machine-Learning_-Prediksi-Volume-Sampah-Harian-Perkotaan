📊 Perbandingan Model Machine Learning untuk Prediksi Volume Sampah Harian Perkotaan

Repository ini berisi penelitian perbandingan berbagai model machine learning regresi yang diterapkan untuk prediksi volume sampah harian di wilayah perkotaan, dengan studi kasus Kota Jakarta.

Penelitian ini bertujuan untuk mengevaluasi kinerja berbagai algoritma regresi dalam memprediksi volume sampah harian, serta mengidentifikasi model terbaik yang dapat digunakan sebagai dasar pengambilan keputusan di bidang pengelolaan sampah perkotaan.

🔍 Metodologi Penelitian

Penelitian dilakukan dengan pendekatan CRISP-DM, yang meliputi:

Business Understanding

Data Understanding

Data Preparation

Modeling

Evaluation

Deployment (simulasi)

Pada tahap pemodelan, dilakukan perbandingan baseline tanpa hyperparameter tuning untuk memastikan evaluasi yang adil antar model.

🤖 Model Machine Learning yang Digunakan

Sebanyak 12 model regresi dibandingkan dalam penelitian ini, yaitu:

Linear Regression

Ridge Regression

Lasso Regression

K-Nearest Neighbors (KNN)

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

XGBoost Regressor

LightGBM Regressor

CatBoost Regressor

Linear Support Vector Regression (Linear SVR)

Seluruh model dilatih menggunakan parameter default dari pustaka:

scikit-learn

XGBoost

LightGBM

CatBoost

📁 Dataset yang Digunakan
1️⃣ Data Volume Sampah Harian Kota Jakarta

Sumber: Kaggle Dataset

<img width="1311" height="486" alt="image" src="https://github.com/user-attachments/assets/89c1b840-4f87-4ec7-b446-e7a6cfd80f98" />
2️⃣ Data Kependudukan Kota Jakarta

Sumber: Badan Pusat Statistik (BPS)

<img width="994" height="480" alt="image" src="https://github.com/user-attachments/assets/47f94eeb-c2fa-49b3-b1fd-4ea6a5d50fdc" />

Data kependudukan digunakan sebagai fitur eksternal tambahan untuk meningkatkan akurasi prediksi dan mengatasi keterbatasan studi sebelumnya.

📈 Hasil Perbandingan Model

Evaluasi model dilakukan menggunakan metrik regresi (seperti RMSE, MAE, dan R²).

<img width="766" height="561" alt="image" src="https://github.com/user-attachments/assets/e1179abf-7222-47d7-a6a3-f0f54a6c0a65" /> <img width="949" height="536" alt="image" src="https://github.com/user-attachments/assets/fb7d1ec3-65e6-4965-a253-1e9e37a41eef" />

Berdasarkan hasil evaluasi, diperoleh 3 model dengan performa terbaik.

🔗 Ensemble Learning (Stacking Ensemble)

Tiga model terbaik kemudian diimplementasikan menggunakan metode Stacking Ensemble untuk meningkatkan performa prediksi dengan mengombinasikan keunggulan masing-masing model.

<img width="1310" height="656" alt="image" src="https://github.com/user-attachments/assets/9617dd8c-1509-4a88-af29-7eef3b043d8e" />
🧪 Uji Coba Model Stacking Ensemble

Model stacking ensemble kemudian diuji pada data pengujian untuk mengevaluasi performa akhir dan kestabilan prediksi.

<img width="797" height="473" alt="image" src="https://github.com/user-attachments/assets/147259b4-fd5f-490b-82ef-2f305dfe7ec2" />
🎯 Kesimpulan Singkat

Model ensemble menunjukkan performa yang lebih stabil dibandingkan model tunggal

Penambahan fitur eksternal (kependudukan) berkontribusi pada peningkatan akurasi

Pendekatan ini berpotensi mendukung perencanaan pengelolaan sampah perkotaan berbasis data
