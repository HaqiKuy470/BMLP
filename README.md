# 🤖 Membangun Proyek Machine Learning - BMLP

Proyek akhir kelas **Belajar Machine Learning untuk Pemula** di Dicoding.  
Menggunakan dataset transaksi perbankan untuk membangun model clustering dan klasifikasi.

---

## 📊 Dataset
**Bank Transaction Dataset for Fraud Detection**  
2.512 data transaksi perbankan dengan fitur seperti jumlah transaksi, usia nasabah, saldo akun, dan lainnya.

---

## 🔧 Teknologi
- Python
- Pandas, NumPy
- Scikit-learn
- Yellowbrick
- Matplotlib, Seaborn

---

## 📁 Struktur File
```
├── Clustering_Submission_Akhir_BMLP.ipynb   # Notebook clustering
├── Klasifikasi_Submission_Akhir_BMLP.ipynb  # Notebook klasifikasi
├── model_clustering.h5                       # Model K-Means
├── PCA_model_clustering.h5                   # Model K-Means + PCA
├── decision_tree_model.h5                    # Model Decision Tree
├── explore_RandomForest_classification.h5    # Model Random Forest
├── tuning_classification.h5                  # Model setelah tuning
├── data_clustering.csv                       # Data hasil clustering
└── data_clustering_inverse.csv               # Data hasil inverse transform
```

---

## 📈 Hasil
- **Clustering**: K-Means dengan 3 cluster menggunakan Elbow Method
- **Klasifikasi**: Decision Tree & Random Forest dengan GridSearchCV tuning
