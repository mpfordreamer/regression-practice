# Regresi - Salary Prediction

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi gaji (*Salary*) berdasarkan jumlah tahun pengalaman (*Years of Experience*) menggunakan model **Simple Linear Regression**. Model ini melatih data historis untuk menemukan hubungan garis lurus (linear) antar variabel.

---

## 📂 Struktur Proyek
```text
Regresi/
├── dataset/
│   └── Salary_dataset.csv   # Dataset Gaji & Pengalaman
└── regression-practice.ipynb # Notebook Latihan Regresi
```

---

## 🛠️ Ringkasan & Library
Model ini mengevaluasi kinerja regresi menggunakan metrik standar seperti R2 Score dan Mean Squared Error (MSE).

**Library Utama:**
*   `pandas` & `numpy`: Pengolahan data dan manipulasi array.
*   `seaborn` & `matplotlib`: Visualisasi grafik standar (*scatterplot*).
*   `plotly`: Grafik interaktif (*scatter plot* dengan garis tren).
*   `sklearn`: Algoritma `LinearRegression` dan fungsi `train_test_split`.

---

## 🚀 Cara Menjalankan
Untuk menjalankan notebook ini secara interaktif di **Google Colab**, ikuti langkah berikut:

1.  **Buka Google Colab**: Masuk ke [Google Colab](https://colab.research.google.com/).
2.  **Upload Notebook**: Pilih tab `Upload` dan pilih file `regression-practice.ipynb`.
3.  **Upload Dataset**:
    *   Pastikan path dataset di notebook sesuai (misal: `dataset/Salary_dataset.csv`).
    *   Upload file `Salary_dataset.csv` ke session storage Colab.
4.  **Jalankan Sel**: Klik `Runtime` -> `Run all` atau jalankan sel satu per satu dari atas ke bawah.

---

## 📊 Informasi Dataset
Dataset ini berisi data sederhana untuk analisis regresi:
*   `YearsExperience`: Jumlah tahun pengalaman kerja pasien/karyawan.
*   **`Salary`** (Target): Jumlah gaji tahunan (atau bulanan) yang didapatkan.

---
