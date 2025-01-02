# Principal Component Analysis sebagai Teknik Reduksi Dimensi pada Data Penjualan Rumah di Kawasan Jabodetabek

Makalah ini membahas penggunaan **Principal Component Analysis (PCA)** sebagai teknik reduksi dimensi untuk dataset berdimensi tinggi, khususnya pada data penjualan rumah di kawasan Jabodetabek. PCA digunakan untuk menyederhanakan dataset tanpa menghilangkan informasi penting, dengan tujuan meningkatkan efisiensi proses analisis data.

## Penulis

- **Adhimas Aryo Bimo**  
  NIM: 13523052  
  Program Studi Teknik Informatika  
  Sekolah Teknik Elektro dan Informatika, Institut Teknologi Bandung  

## Abstrak

Dalam penelitian ini, PCA diterapkan menggunakan dua pendekatan utama:
1. **Singular Value Decomposition (SVD)**  
2. **Matriks Kovarians**  

Dataset awal memiliki **111 fitur numerik**, yang direduksi menjadi **15 komponen utama**. Hasil percobaan menunjukkan:
- **Peningkatan efisiensi waktu komputasi sebesar 12,9%.**
- **Peningkatan kesalahan prediksi sebesar 0,22%.**

Makalah ini juga membandingkan performa model machine learning yang dilatih menggunakan dataset asli dan dataset hasil reduksi.

## Teknologi yang Digunakan

- **Python 3.12**  
- **Pustaka Python**:
  - Pandas
  - Matplotlib
  - Scikit-learn
  - XGBoost
  - NumPy

## Cara Menjalankan Kode

1. Clone repository ini:
   ```bash
   git clone https://github.com/ryonlunar/makalah-algeo.git
   cd repository
