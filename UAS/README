# 📚 Machine Learning Project Collection (UAS)

Kumpulan proyek implementasi machine learning dalam bentuk notebook Python (.ipynb) yang berfokus pada **REGRESSION MODEL MLP**, **CLASSIFICATION MODELS MLP**, dan **CNN**.

---

## 📁 Daftar File

### 1. `regresiutstelkommm.ipynb` - Regresi Multi-Framework (TensorFlow & PyTorch)
Notebook ini mengeksplorasi implementasi model regresi menggunakan dua framework deep learning populer:

- **TensorFlow MLP Regressor**
  - Dense layers + BatchNorm + Dropout
  - Optimizer: AdamW + CosineDecay
  - Metrik Evaluasi: MSE, RMSE, R²
- **PyTorch MLP Regressor**
  - Layer serupa dengan pendekatan PyTorch
  - Learning rate scheduler + Early Stopping manual
- **Analisis Evaluasi:**
  - Tabel perbandingan metrik (MSE, RMSE, R²)
  - Visualisasi hasil prediksi (scatter plot)
  - Diskusi performa & rekomendasi perbaikan model

---

### 2. `klasifikasiutss.ipynb` - Klasifikasi Biner dengan Tabular Data (MLP)
Notebook ini merupakan eksperimen klasifikasi biner menggunakan data tabular dengan arsitektur MLP pada:

- **TensorFlow MLP Classifier**
  - Preprocessing: StandardScaler
  - Evaluasi: Confusion Matrix, AUC, ROC Curve
- **PyTorch MLP Classifier**
  - Arsitektur serupa, training manual dengan EarlyStopping
- **Evaluasi Model:**
  - Accuracy, Precision, Recall, F1-Score, AUC
  - Visualisasi Confusion Matrix & ROC Curve
  - Tabel komparatif dan analisa performa kedua model

---

### 3. `klasifikasiikan_CNN.ipynb` - Klasifikasi Gambar Ikan dengan CNN
Notebook ini membangun dan melatih model CNN untuk mengklasifikasikan berbagai jenis ikan dari dataset gambar terstruktur (train, val, test).

- **Dataset:**
  - Folder `train/`, `val/`, dan `test/` berisi gambar per kelas
- **Pipeline:**
  - Augmentasi data: Flip, Rotation, Zoom
  - Caching dan prefetching dengan `AUTOTUNE`
- **Model CNN:**
  - 3 blok Conv2D + MaxPooling
  - Dense layer akhir dengan softmax
- **Evaluasi:**
  - Akurasi per epoh
  - Confusion matrix
  - ROC AUC (jika multi-label dibinarisasi)

---

## 📌 Catatan Tambahan
- Notebook ini menggunakan `scikit-learn`, `TensorFlow`, dan `PyTorch`.
- Beberapa kode membutuhkan dataset eksternal (`FishImgDataset`, "KlasifikasiUTS") — pastikan struktur folder sesuai dengan `base_dir` pada notebook.
- Direkomendasikan untuk menggunakan GPU untuk training CNN.
