# 🏦 Bank Customer Behavior Analysis: Clustering & Classification

> **🌟 Achievement:** Proyek ini meraih penilaian **Bintang 5** pada program **Coding Camp 2026 powered by DBS Foundation** untuk *learning path* **Data Scientist**.

## 📌 Deskripsi Proyek
Repositori ini berisi proyek akhir (*end-to-end Machine Learning pipeline*) yang dikerjakan sebagai bagian dari program kelulusan **Coding Camp 2026 powered by DBS Foundation**. Proyek ini bertujuan untuk menganalisis dan memprediksi pola perilaku nasabah bank menggunakan dua pendekatan *machine learning*:

1. **Clustering (Unsupervised Learning):** Mengelompokkan nasabah ke dalam segmen-segmen tertentu (seperti *Nasabah Profesional Mapan* dan *Nasabah Pelajar Transaksional*). Proses ini juga melibatkan *inverse transform* untuk mendapatkan nilai data asli sehingga menghasilkan *insight* bisnis yang bisa diinterpretasikan.
2. **Classification (Supervised Learning):** Membangun model prediktif (Decision Tree & Random Forest) untuk memprediksi kategori/klaster nasabah berdasarkan fitur transaksi dan demografi.

## 🏆 Highlight Pencapaian
* Menyelesaikan seluruh modul pelatihan secara komprehensif pada jalur **Data Scientist**.
* Evaluasi proyek akhir mendapatkan nilai maksimal, yaitu **Bintang 5**.
* Model **Random Forest** yang telah dioptimasi menggunakan teknik *Hyperparameter Tuning* (GridSearchCV) berhasil memetakan ulang batas klaster nasabah dengan tingkat akurasi **100%**.

## 🛠️ Teknologi yang Digunakan
* **Bahasa Pemrograman:** Python
* **Manipulasi Data:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Decision Tree, RandomForestClassifier, GridSearchCV)
* **Model Deployment:** Joblib

## 📁 Struktur File
* `notebook_clustering.ipynb` : Proses pembersihan data, eksplorasi, dan pembentukan klaster.
* `notebook_klasifikasi.ipynb` : Pembangunan algoritma dan *hyperparameter tuning* model klasifikasi.
* `data_clustering_inverse.csv` : Dataset hasil pengelompokan yang nilainya sudah dikembalikan ke skala nyata.
* `*.h5` : File model *machine learning* yang telah dilatih dan siap digunakan.
* `Sertifikat.pdf` / `Sertifikat.png` : Bukti sertifikat kelulusan Coding Camp 2026.