# Heart-Disease-Prediction
# Proyek Prediksi Penyakit Jantung
  Proyek ini bertujuan untuk melakukan analisis data dan membangun alur (pipeline) untuk mendeteksi potensi penyakit jantung menggunakan pendekatan Object-Oriented Programming (OOP) dalam Python.
# 1. Deskripsi Proyek
  Notebook ini mengolah dataset penyakit jantung (kemungkinan besar dataset Cleveland atau sejenisnya) yang disimpan di Google Drive. Analisis dilakukan secara sistematis mulai dari memuat data, membersihkan data, hingga melakukan analisis eksploratif (EDA).
# 2. Fitur Utama (Alur Pipeline)
  Program ini disusun menggunakan kelas-kelas yang saling terintegrasi dalam sebuah pipeline:
  - Data Loading: Memuat data dari file CSV dengan informasi awal sebanyak 303 baris dan 14 kolom.
  - Preprocessing Data: Pengecekan dan penanganan nilai yang hilang (missing values) pada kolom krusial seperti ca dan thal. Penggantian nama kolom agar lebih            mudah dipahami (misal: chol menjadi cholesterol). Transformasi label target menjadi kategori yang deskriptif: no_disease (sehat) dan has_disease (terindikasi         penyakit jantung).
  - Exploratory Data Analysis (EDA): Menampilkan ringkasan statistik (rata-rata, standar deviasi, nilai min/max) untuk seluruh fitur numerik. Visualisasi distribusi      kolom target untuk melihat keseimbangan data. Analisis fitur spesifik seperti usia (age), kadar kolesterol (cholesterol), dan detak jantung maksimal yang dicapai     (max_heart_rate_achieved).
# 3. Struktur Kode (OOP)
  Kode menggunakan beberapa kelas utama untuk menjaga modularitas:
  - BaseDataset: Menangani urusan pembacaan dan pembersihan awal data.
  - HeartDiseaseEDA: Bertanggung jawab atas visualisasi dan analisis statistik.
  - HeartDiseasePipeline: Kelas utama yang mengoordinasikan seluruh langkah analisis dalam satu eksekusi.
# 4. Teknologi yang Digunakan
  - Python: Bahasa pemrograman utama.
  - Pandas: Untuk manipulasi dan analisis data.
  - Matplotlib/Seaborn: Digunakan untuk menghasilkan visualisasi distribusi dan grafik statistik.
  - Google Colab: Sebagai lingkungan pengembangan (IDE).
