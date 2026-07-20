# ❤️ Heart Disease Prediction

## Tentang Project

Project ini dibuat sebagai tugas akhir mata kuliah **Fundamental Sains Data**.

Pada project ini kami menggunakan **Heart Disease Prediction Dataset** untuk mengimplementasikan dua metode machine learning, yaitu **Supervised Learning** dan **Unsupervised Learning**.
Untuk supervised learning saya menggunakan algoritma **Random Forest** guna memprediksi apakah seseorang memiliki penyakit jantung atau tidak. Sedangkan pada unsupervised learning saya menggunakan algoritma **K-Means Clustering** untuk mengelompokkan pasien berdasarkan kemiripan karakteristik kesehatannya.
Selain proses pembuatan model, project ini juga mencakup tahapan eksplorasi data (EDA), preprocessing, evaluasi model, visualisasi hasil, serta pembuatan antarmuka sederhana menggunakan Gradio.

---

## Dataset

Dataset yang digunakan adalah **Heart Disease Prediction Dataset** yang diperoleh dari Kaggle.
Beberapa informasi pada dataset:
- Jumlah data : 302 data (setelah menghapus data duplikat)
- Jumlah fitur : 13 fitur dan 1 target
- Target :
  - 0 = Tidak memiliki penyakit jantung
  - 1 = Memiliki penyakit jantung

Beberapa fitur yang digunakan antara lain:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Thal
- dan beberapa fitur kesehatan lainnya.

---

## Tahapan Pengerjaan

Tahapan yang dilakukan pada project ini meliputi:

- Import library
- Load dataset
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Training model
- Evaluasi model
- Clustering menggunakan K-Means
- Visualisasi hasil clustering
- Pembuatan aplikasi sederhana menggunakan Gradio

---

## Algoritma yang Digunakan

### Supervised Learning

- Random Forest Classifier

Evaluasi model menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Unsupervised Learning

- K-Means Clustering

Evaluasi clustering menggunakan:

- Elbow Method
- Silhouette Score
- Davies-Bouldin Index

---

## Hasil

Dari hasil implementasi Random Forest, model mampu melakukan klasifikasi penyakit jantung dengan performa yang cukup baik berdasarkan nilai evaluasi yang diperoleh.
Sedangkan pada proses clustering, K-Means berhasil membagi data pasien menjadi **4 kelompok** berdasarkan karakteristik kesehatannya. Pengelompokan tersebut kemudian divisualisasikan menggunakan PCA agar lebih mudah dipahami.

---

## Tools yang Digunakan

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Gradio

---

## Struktur Project

```
Heart-Disease-Prediction/
│
├── Tugas Final FSD.ipynb
├── heart.csv
├── heart_model.pkl
├── app.py
├── README.md
└── requirements.txt
```

---

## Cara Menjalankan

1. Clone repository ini.

```bash
git clone https://github.com/username/Heart-Disease-Prediction.git
```

2. Install library yang dibutuhkan.

```bash
pip install -r requirements.txt
```

3. Jalankan notebook menggunakan Google Colab atau Jupyter Notebook.

4. Jika ingin mencoba aplikasi prediksi, jalankan:

```bash
python app.py
```

---

## Kesimpulan

Berdasarkan hasil yang diperoleh, Random Forest cukup baik digunakan untuk memprediksi penyakit jantung pada dataset ini. Selain itu, K-Means juga mampu mengelompokkan pasien berdasarkan karakteristik kesehatan yang dimiliki sehingga dapat memberikan gambaran mengenai profil masing-masing kelompok pasien.

Melalui project ini saya menjadi lebih memahami tahapan dalam membangun model machine learning, mulai dari eksplorasi data hingga evaluasi model dan implementasi sederhana menggunakan Gradio.

---

## Author

**Aggota**

**Mata Kuliah:** Fundamental Sains Data

**Universitas:** ...
