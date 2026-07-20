# ❤️ Prediksi Penyakit Jantung Menggunakan Supervised Learning dan Analisis Klaster Pasien Menggunakan Unsupervised Learning

## Final Project Machine Learning

### Anggota Kelompok

- Muhammad Abdillah Mu’tashim (24523239)
- Muhamad Aldio Khairullah Santoso (24523252)
- Hiraldy Ibrahim (24523176)
- Irham Malik Taufik (24523030)

---

# Deskripsi Proyek

Proyek ini bertujuan untuk mengimplementasikan dua pendekatan Machine Learning menggunakan satu dataset yang sama, yaitu **Heart Disease Prediction Dataset**.

Pendekatan pertama menggunakan **Supervised Learning** dengan algoritma **Random Forest Classifier** untuk memprediksi apakah seorang pasien berpotensi mengalami penyakit jantung berdasarkan data kesehatannya.

Pendekatan kedua menggunakan **Unsupervised Learning** dengan algoritma **K-Means Clustering** untuk mengelompokkan pasien berdasarkan kemiripan karakteristik kesehatannya tanpa menggunakan label target.

Selain itu, model prediksi juga diimplementasikan ke dalam aplikasi sederhana menggunakan **Gradio** sehingga pengguna dapat melakukan prediksi secara interaktif melalui antarmuka web.

---

# Dataset

**Nama Dataset**

Heart Disease Prediction Dataset

**Sumber Dataset**

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

Dataset ini memiliki beberapa atribut kesehatan, antara lain:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- CA
- Thal
- Target (Heart Disease)

---

# Tahapan Pengerjaan

Proyek ini dikerjakan melalui beberapa tahapan sebagai berikut:

1. Import Library
2. Load Dataset
3. Memahami Dataset
4. Exploratory Data Analysis (EDA)
5. Data Preprocessing
6. Implementasi Supervised Learning
7. Evaluasi Model
8. Implementasi Unsupervised Learning
9. Evaluasi Clustering
10. Implementasi Gradio
11. Insight dan Kesimpulan

---

# Algoritma yang Digunakan

## Supervised Learning

Algoritma:

- Random Forest Classifier

Evaluasi Model:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance

---

## Unsupervised Learning

Algoritma:

- K-Means Clustering

Evaluasi Clustering:

- Elbow Method
- Silhouette Score
- Davies-Bouldin Index
- Visualisasi Cluster Menggunakan PCA

---

# Library yang Digunakan

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Gradio
- Joblib

---

# Struktur Proyek

```
Heart-Disease-Prediction/
│
├── Final_Project.ipynb
├── heart.csv
├── heart_disease_model.pkl
├── scaler.pkl
├── README.md
└── requirements.txt
```

---

# Cara Menjalankan Proyek

1. Clone repository ini.

```bash
git clone https://github.com/username/Heart-Disease-Prediction.git
```

2. Install seluruh library yang dibutuhkan.

```bash
pip install -r requirements.txt
```

3. Buka file notebook menggunakan Google Colab atau Jupyter Notebook.

4. Upload dataset **heart.csv**.

5. Jalankan seluruh cell secara berurutan.

6. Jalankan aplikasi Gradio untuk mencoba prediksi penyakit jantung.

---

# Implementasi Gradio

Aplikasi Gradio digunakan sebagai antarmuka sederhana agar pengguna dapat melakukan prediksi penyakit jantung tanpa harus menjalankan kode secara langsung.

Input yang digunakan:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- CA
- Thal

Output:

- Hasil Prediksi Penyakit Jantung

---

# Hasil Proyek

Berdasarkan implementasi yang telah dilakukan, diperoleh beberapa hasil sebagai berikut:

- Model Random Forest berhasil digunakan untuk memprediksi penyakit jantung berdasarkan data kesehatan pasien.
- Algoritma K-Means berhasil mengelompokkan pasien berdasarkan kemiripan karakteristik kesehatan.
- Evaluasi model menunjukkan bahwa Random Forest memiliki performa klasifikasi yang baik.
- Evaluasi clustering menunjukkan bahwa data berhasil dikelompokkan menjadi beberapa cluster yang memiliki karakteristik berbeda.
- Model berhasil diimplementasikan ke dalam aplikasi Gradio sehingga dapat digunakan secara interaktif.

---

# Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan pada penelitian ini antara lain:

- Menggunakan dataset dengan jumlah data yang lebih banyak.
- Membandingkan performa beberapa algoritma klasifikasi seperti Logistic Regression, SVM, dan XGBoost.
- Membandingkan algoritma clustering seperti DBSCAN atau Hierarchical Clustering.
- Mengembangkan aplikasi menjadi sistem berbasis web dengan fitur yang lebih lengkap.
- Menambahkan visualisasi dan interpretasi model menggunakan SHAP atau LIME.

---

# Lisensi

Proyek ini dibuat untuk memenuhi tugas **Final Project Mata Kuliah Machine Learning** dan digunakan hanya untuk keperluan akademik.
