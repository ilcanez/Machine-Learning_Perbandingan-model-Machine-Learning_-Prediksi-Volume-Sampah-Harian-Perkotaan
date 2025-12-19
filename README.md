# Machine-Learning_Perbandingan-model-Machine-Learning_-Prediksi-Volume-Sampah-Harian-Perkotaan
Penelitian ini melakukan perbandingan berbagai model machine learning regresi guna diterapkan pada prediksi volume sampah harian perkotaan
Model regresi yang dibandingkan adalah sebanyak 12 model, yaitu : Linear Regression, Ridge Regression, Lasso Regression, K-Nearest 
Neighbors, Decision Tree, Random Forest, Gradient Boosting, XGBoost, 
LightGBM, CatBoost, serta Linear SVR. Seluruh model pada tahap baseline dilatih 
menggunakan parameter default dari pustaka scikit-learn, XGBoost, LightGBM, 
dan CatBoost.

Dataset yang digunakan :
1. Data Volume Sampah harian Kota Jakarta (Kaggle Dataset)

<img width="1311" height="486" alt="image" src="https://github.com/user-attachments/assets/89c1b840-4f87-4ec7-b446-e7a6cfd80f98" />

2. Data Penduduk kota Jakarta (Badan Pusat Statistik)
   
<img width="994" height="480" alt="image" src="https://github.com/user-attachments/assets/47f94eeb-c2fa-49b3-b1fd-4ea6a5d50fdc" />


Hasil Perbandingan Model :
<img width="766" height="561" alt="image" src="https://github.com/user-attachments/assets/e1179abf-7222-47d7-a6a3-f0f54a6c0a65" />
<img width="949" height="536" alt="image" src="https://github.com/user-attachments/assets/fb7d1ec3-65e6-4965-a253-1e9e37a41eef" />

Model 3 Terbaik di implementasikan mengggunakan metode ensemble berupa Stacking Ensemble :

<img width="1310" height="656" alt="image" src="https://github.com/user-attachments/assets/9617dd8c-1509-4a88-af29-7eef3b043d8e" />


Uji Coba Model (Stacking Ensemble)
<img width="797" height="473" alt="image" src="https://github.com/user-attachments/assets/147259b4-fd5f-490b-82ef-2f305dfe7ec2" />
