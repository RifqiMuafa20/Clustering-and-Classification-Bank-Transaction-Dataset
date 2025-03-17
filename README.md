# 🔍 Bank Transaction Classification & Clustering

Repository ini berisi implementasi **klasifikasi** dan **klastering** pada **Bank Transaction Dataset**. Proyek ini bertujuan untuk mengelompokkan serta mengklasifikasikan transaksi berdasarkan pola yang ditemukan dalam data, menggunakan algoritma **Machine Learning** seperti Logistic Regression, Random Forest, dan K-Means.

## 📊 Fitur dalam Repository
✅ **Preprocessing Data**: Pembersihan, transformasi, dan normalisasi data transaksi bank.  
✅ **Clustering**: Menggunakan algoritma **K-Means** untuk mengelompokkan transaksi berdasarkan karakteristiknya. 
✅ **Evaluasi Model Clustering**: Menggunakan metrik **Silhouette Score**.  
✅ **Classification**: Model **Logistic Regression** dan **Random Forest** untuk mengklasifikasikan transaksi.  
✅ **Hyperparameter Tuning**: Grid Search untuk optimasi parameter model.  
✅ **Evaluasi Model Klasifikasi**: Menggunakan metrik **Akurasi, F1-score, dan Classification Report**.

## 🛠 Teknologi yang Digunakan
- **Python**: NumPy, Pandas, Matplotlib, Seaborn  
- **Scikit-learn**: Model klasifikasi dan klastering  
- **Jupyter Notebook**  

## 📂 Struktur Repository
```
📦 bank-transaction-analysis
│── [Clustering]_Submission_Akhir_BMLP_Muh. Rifqi Muafa.ipynb      # File Jupyter Notebook untuk model Clustering
│── [Klasifikasi]_Submission_Akhir_BMLP_Muh Rifqi Muafa      # File Jupyter Notebook untuk model Klasifikasi
│── bank_transactions_data_2.csv      # Dataset Awal
│── Final_Dataset_Klasifikasi.csv      # Dataset Hasil Clustering
│── README.md             # Dokumentasi proyek
```

## 🚀 Instalasi & Penggunaan
1. **Clone repository**  
   ```bash
   git clone https://github.com/RifqiMuafa20/Clustering-and-Classification-Bank-Transaction-Dataset.git
   cd repository-name
   ```
3. **Jalankan notebook atau skrip**  
   Buka **Jupyter Notebook** dan jalankan file untuk eksplorasi data, training model, serta evaluasi.

## 📈 Hasil & Analisis
- **Klastering**:  
  - K-Means berhasil mengelompokkan transaksi menjadi 3 kelas berdasarkan pola tertentu.
    1. Cluster 1: Kelompok Konsumen Stabil dan Berpenghasilan Tinggi
    2. Cluster 2: Kelompok Pelanggan Muda dan Bertransaksi Aktif
    3. Cluster 3: Kelompok Pensiunan dan Profesional Berpenghasilan Tinggi
- **Klasifikasi**:  
  - **Logistic Regression** dan **Random Forest** mencapai akurasi **>97%**.
  - Hasil tuning hyperparameter tidak memberikan peningkatan yang signifikan.

## 📜 Lisensi
Proyek ini menggunakan lisensi **MIT License**.

---

💡 **Kontribusi & Feedback**  
Silakan lakukan **pull request** atau buat **issue** jika ingin berkontribusi! Jika ada pertanyaan, jangan ragu untuk menghubungi. 😊
