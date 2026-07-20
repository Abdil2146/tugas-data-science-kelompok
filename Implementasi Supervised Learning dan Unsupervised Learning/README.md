# ❤️ Prediksi Penyakit Jantung Menggunakan Supervised Learning dan Analisis Klaster Pasien Menggunakan Unsupervised Learning

## Final Project Machine Learning

### 👥 Anggota Kelompok

- Muhammad Abdillah Mu’tashim (24523239)
- Muhamad Aldio Khairullah Santoso (24523252)
- Hiraldy Ibrahim (24523176)
- Irham Malik Taufik (24523030)

---

# 📖 Deskripsi Proyek

Proyek ini bertujuan untuk mengimplementasikan dua pendekatan Machine Learning menggunakan satu dataset yang sama, yaitu **Heart Disease Prediction Dataset**.

Pendekatan pertama menggunakan **Supervised Learning** dengan algoritma **Random Forest Classifier** untuk memprediksi apakah seorang pasien berpotensi mengalami penyakit jantung berdasarkan data kesehatannya.

Pendekatan kedua menggunakan **Unsupervised Learning** dengan algoritma **K-Means Clustering** untuk mengelompokkan pasien berdasarkan kemiripan karakteristik kesehatannya tanpa menggunakan label target.

Selain itu, model prediksi juga diimplementasikan ke dalam aplikasi sederhana menggunakan **Gradio** sehingga pengguna dapat melakukan prediksi secara interaktif melalui antarmuka web.

---

# 📂 Dataset

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

# 🔄 Tahapan Pengerjaan

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

# 🤖 Algoritma yang Digunakan

## Supervised Learning

**Algoritma**

- Random Forest Classifier

**Evaluasi Model**

- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance

---

## Unsupervised Learning

**Algoritma**

- K-Means Clustering

**Evaluasi Clustering**

- Elbow Method
- Silhouette Score
- Davies-Bouldin Index
- Visualisasi Cluster Menggunakan PCA

---

# 🛠️ Library yang Digunakan

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

# 📁 Struktur Proyek

```text
Implementasi Supervised Learning dan Unsupervised Learning/
│
├── images/
│   ├── confusion-matrix.png
│   ├── feature-importance.png
│   ├── elbow-method.png
│   ├── kmeans-clustering.png
│   ├── gradio-before.png
│   ├── gradio-input.png
│   └── gradio-result.png
│
├── FSD_Kelompok_Heart_Disease_Prediction.ipynb
├── heart.csv
├── heart_disease_model.pkl
├── scaler.pkl
├── README.md
└── requirements.txt
```

---

# ▶️ Cara Menjalankan Proyek

1. Clone repository ini.

```bash
git clone https://github.com/Abdil2146/tugas-data-science-kelompok.git
```

2. Masuk ke folder project.

```bash
cd tugas-data-science-kelompok
```

3. Install seluruh library yang dibutuhkan.

```bash
pip install -r requirements.txt
```

4. Buka notebook menggunakan Google Colab atau Jupyter Notebook.

5. Upload dataset **heart.csv**.

6. Jalankan seluruh cell secara berurutan.

7. Jalankan aplikasi Gradio untuk mencoba prediksi penyakit jantung.

---

# 🖥️ Implementasi Gradio

Aplikasi Gradio digunakan sebagai antarmuka sederhana agar pengguna dapat melakukan prediksi penyakit jantung tanpa harus menjalankan kode secara langsung.

### Input

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

### Output

- Hasil Prediksi Penyakit Jantung

---

# 📸 Dokumentasi Hasil

## 1. Confusion Matrix

Confusion Matrix digunakan untuk mengevaluasi performa model **Random Forest Classifier** dalam mengklasifikasikan pasien yang berpotensi mengalami penyakit jantung dan yang tidak. Visualisasi ini menunjukkan jumlah prediksi yang benar maupun salah sehingga memudahkan analisis performa model.

![Confusion Matrix](images/confusion-matrix.png)

---

## 2. Feature Importance

Visualisasi **Feature Importance** menunjukkan tingkat kontribusi masing-masing fitur terhadap hasil prediksi penyakit jantung. Semakin tinggi nilai importance suatu fitur, semakin besar pengaruhnya terhadap keputusan model.

![Feature Importance](images/feature-importance.png)

---

## 3. Elbow Method

Elbow Method digunakan untuk menentukan jumlah cluster (K) yang paling optimal pada algoritma **K-Means Clustering**. Titik siku (elbow) pada grafik menjadi acuan dalam menentukan jumlah cluster terbaik.

![Elbow Method](images/elbow-method.png)

---

## 4. Visualisasi Hasil Clustering

Visualisasi berikut menunjukkan hasil pengelompokan pasien menggunakan algoritma **K-Means Clustering**. Karena dataset memiliki banyak fitur, digunakan **Principal Component Analysis (PCA)** untuk mereduksi dimensi sehingga hasil clustering dapat divisualisasikan dalam dua dimensi.

Setiap titik merepresentasikan satu pasien, sedangkan warna menunjukkan cluster tempat pasien tersebut berada.

![K-Means Clustering](images/kmeans-clustering.png)

---

## 5. Tampilan Awal Aplikasi Gradio

Berikut merupakan tampilan awal aplikasi sebelum pengguna memasukkan data pasien.

![Gradio Before](images/gradio-before.png)

---

## 6. Pengisian Data Pasien

Pengguna mengisi informasi kesehatan pasien pada setiap kolom yang tersedia sebelum proses prediksi dilakukan.

![Gradio Input](images/gradio-input.png)

---

## 7. Hasil Prediksi

Setelah seluruh data pasien dimasukkan, model Random Forest akan memberikan hasil prediksi apakah pasien berpotensi mengalami penyakit jantung atau tidak.

![Gradio Result](images/gradio-result.png)

---

# 📈 Hasil Proyek

Berdasarkan implementasi yang telah dilakukan, diperoleh beberapa hasil sebagai berikut.

- Dataset berhasil dianalisis melalui proses Exploratory Data Analysis (EDA).
- Data berhasil diproses melalui tahap preprocessing sehingga siap digunakan dalam proses pemodelan.
- Model Random Forest berhasil digunakan untuk memprediksi penyakit jantung dengan performa yang baik berdasarkan hasil evaluasi.
- Algoritma K-Means berhasil mengelompokkan pasien ke dalam beberapa cluster berdasarkan kemiripan karakteristik kesehatannya.
- Visualisasi PCA mempermudah interpretasi hasil clustering.
- Model berhasil diimplementasikan ke dalam aplikasi Gradio sehingga pengguna dapat melakukan prediksi secara interaktif.

---

# 💡 Insight dan Kesimpulan

Penggunaan satu dataset untuk dua pendekatan Machine Learning menunjukkan bahwa data yang sama dapat dimanfaatkan untuk tujuan yang berbeda.

Pendekatan **Supervised Learning** berhasil digunakan untuk memprediksi kemungkinan penyakit jantung berdasarkan data kesehatan pasien, sedangkan **Unsupervised Learning** mampu menemukan pola dan mengelompokkan pasien berdasarkan kemiripan karakteristik kesehatannya.

Hasil evaluasi menunjukkan bahwa model Random Forest memiliki performa klasifikasi yang baik, sementara K-Means berhasil membentuk cluster yang memberikan gambaran mengenai karakteristik kelompok pasien.

Implementasi menggunakan Gradio membuktikan bahwa model yang telah dibangun dapat diterapkan menjadi aplikasi sederhana sehingga lebih mudah digunakan oleh pengguna tanpa harus menjalankan kode secara langsung.

---

# 🚀 Pengembangan Selanjutnya

Beberapa pengembangan yang dapat dilakukan pada penelitian ini antara lain:

- Menggunakan dataset dengan jumlah data yang lebih besar.
- Membandingkan performa beberapa algoritma klasifikasi seperti Logistic Regression, Support Vector Machine (SVM), Decision Tree, XGBoost, atau Neural Network.
- Membandingkan algoritma clustering lain seperti DBSCAN atau Hierarchical Clustering.
- Mengembangkan aplikasi menjadi sistem berbasis web dengan tampilan yang lebih interaktif.
- Menambahkan interpretasi model menggunakan SHAP atau LIME agar hasil prediksi lebih mudah dipahami.

---

# 📄 Lisensi

Proyek ini dibuat sebagai **Final Project Mata Kuliah Machine Learning** dan digunakan untuk keperluan akademik.
