# Titanic-EDA-project
# 🚢 Titanic - Exploratory Data Analysis (EDA)

Analisis eksploratif pada dataset Titanic dari Kaggle untuk memahami karakteristik penumpang dan faktor-faktor yang mempengaruhi kemungkinan selamat dalam tragedi tersebut.

> 📁 Dataset: [Titanic - Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/competitions/titanic)

---

## 🧭 Tujuan Proyek

Proyek ini bertujuan untuk melakukan proses **Exploratory Data Analysis (EDA)** yang mencakup:

- Pembersihan data (missing values & duplikat)
- Deteksi dan penanganan outlier
- Transformasi numerik (log)
- Encoding data kategorikal
- Menyiapkan dataset untuk analisis lanjutan atau pemodelan

---

## 📊 Tahapan EDA

| Tahap | Deskripsi |
|------|-----------|
| **1. Load Data** | Membaca file `train.csv` ke DataFrame |
| **2. Data Inspection** | Memahami struktur, tipe data, dan statistik awal |
| **3. Missing Value Handling** | Menangani nilai kosong dengan median & modus |
| **4. Duplicate Removal** | Menghapus baris data yang duplikat |
| **5. Outlier Detection** | Menggunakan IQR untuk mendeteksi outlier di `Fare` |
| **6. Log Transformation** | Mengurangi skewness pada distribusi `Fare` |
| **7. Encoding** | Label encoding (`Sex`) dan One-Hot encoding (`Embarked`) |
| **8. Drop Irrelevant Columns** | Menghapus kolom seperti `Name` dan `Ticket` |

---

## 🖥️ Tools & Library

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib

---

---

## 📈 Visualisasi

Contoh visualisasi distribusi data sebelum dan sesudah transformasi log:

| Sebelum Transformasi | Setelah Transformasi |
|----------------------|----------------------|
| ![Distribusi Fare](assets/fare_dist.png) | ![Distribusi Log Fare](assets/log_fare_dist.png) |

> Gambar bisa ditambahkan setelah hasil plot disimpan via `plt.savefig()`.

---

## ✅ Output Akhir

Dataset bersih dan siap pakai untuk tahap analisis lanjutan atau modeling machine learning:

- Tidak ada missing value
- Tidak ada duplikat
- Outlier terdeteksi dan bisa ditindaklanjuti
- Data numerik dan kategorikal sudah diolah dengan baik

---

## 📌 Catatan

Proyek ini disusun sebagai bagian dari pembelajaran data analysis.  
Juga dapat dijadikan referensi untuk praktek EDA pada dataset lain.

---

## 👤 Author

> 🧑 Nama: [Faza Qinthoro]  
> 🎓 Tugas: Exploratory Data Analysis - Dataset Titanic  
> 📅 Tanggal: 8 Mei 2025



