# Tugas 1 — Analisis dan Visualisasi Film Populer Menggunakan PCA dan t-SNE

**Kelompok :**  
1. Muhammad Abdillah Mu'tashim – NIM(24523239)
2. Hiraldy ibrahim – NIM(24523176)
3. Muhamad Aldio Khairullah Santoso – NIM(24523250)
4. irham malik taufik – NIM(24523030)

## Deskripsi Proyek
Proyek ini membahas analisis dan visualisasi dataset film populer menggunakan dua metode reduksi dimensi, yaitu **Principal Component Analysis (PCA)** dan **t-Distributed Stochastic Neighbor Embedding (t-SNE)**. 

Dataset yang digunakan berisi informasi film populer, seperti **genre**, **vote average**, **vote count**, **popularity**, **budget**, **revenue**, **runtime**, dan **release year**. Analisis dilakukan untuk melihat pola persebaran data film berdasarkan fitur-fitur numerik tersebut.

## Tujuan Analisis
1. Mengolah dataset film populer sebelum dilakukan analisis.
2. Memilih fitur numerik yang relevan untuk proses reduksi dimensi.
3. Menerapkan metode PCA untuk melihat struktur umum data.
4. Menerapkan metode t-SNE untuk melihat pola kedekatan lokal antarfilm.
5. Membandingkan hasil visualisasi PCA dan t-SNE.
6. Menarik kesimpulan dari pola persebaran data yang dihasilkan.

## Dataset
Dataset yang digunakan berasal dari Kaggle:

**Popular Movies Dataset (TMDB)**  
Sumber: Kaggle

## Tahapan Pengerjaan
1. Mengimpor dataset film populer.
2. Melakukan eksplorasi data awal.
3. Membersihkan data dan memilih fitur numerik yang relevan.
4. Menangani nilai kosong pada data yang digunakan.
5. Melakukan standardisasi fitur numerik.
6. Menerapkan PCA untuk reduksi dimensi dan visualisasi data.
7. Menerapkan t-SNE untuk visualisasi data dalam dua dimensi.
8. Menganalisis hasil PCA dan t-SNE.
9. Menyusun kesimpulan berdasarkan hasil visualisasi.

## Ringkasan Hasil
Hasil PCA menunjukkan gambaran umum struktur data film, namun pemisahan antar genre belum terlihat sepenuhnya jelas. Sementara itu, t-SNE menghasilkan visualisasi yang lebih detail dalam menampilkan kedekatan lokal antarfilm. Dari hasil tersebut dapat disimpulkan bahwa t-SNE lebih membantu dalam melihat pola persebaran lokal data, sedangkan PCA lebih baik untuk menggambarkan struktur data secara umum.
