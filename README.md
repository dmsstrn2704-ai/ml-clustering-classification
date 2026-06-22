# 🤖 Machine Learning — Clustering & Classification

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange) ![Status](https://img.shields.io/badge/Status-Completed-success)

Proyek submission akhir kursus **Belajar Machine Learning Pemula (BMLP)** Dicoding. Mencakup dua tahap: clustering (unsupervised learning) untuk menemukan pola tersembunyi dalam data, dan classification (supervised learning) untuk membangun model prediksi berdasarkan hasil clustering.

## 📌 Highlights

| Metric | Hasil |
|---|---|
| Teknik unsupervised | Clustering |
| Teknik supervised | Decision Tree Classification |
| Model tersimpan | ✅ 2 model (.h5) |
| Tools | Scikit-learn, Pandas |

## 🔄 Alur Pengerjaan

```
   Raw Dataset
        │
        ▼
 [ CLUSTERING ]  ── Unsupervised Learning
        │            mengelompokkan data tanpa label
        │            berdasarkan kemiripan fitur
        ▼
  Data + Label Cluster
        │
        ▼
 [ CLASSIFICATION ] ── Decision Tree
        │               melatih model untuk memprediksi
        │               cluster pada data baru
        ▼
   Model Tersimpan (.h5)
```

## 🛠️ Teknologi

- **Python 3.x** — bahasa utama
- **Pandas & NumPy** — manipulasi & pembersihan data
- **Scikit-learn** — clustering & classification model
- **Jupyter Notebook** — eksplorasi & dokumentasi proses

## 📁 Struktur Project

```
ml-clustering-classification/
├── [Clustering]_Submission_Akhir_BMLP_Dimas_Satria.ipynb
├── [Klasifikasi]_Submission_Akhir_BMLP_Dimas_Satria.ipynb
├── data_clustering.csv
├── data_clustering_inverse.csv
├── model_clustering.h5
├── decision_tree_model.h5
└── MACHINE LEARNING DICODING.pdf
```

## ⚙️ Instalasi

```bash
# 1. Clone repository
git clone https://github.com/dmsstrn2704-ai/ml-clustering-classification.git
cd ml-clustering-classification

# 2. Install dependencies
pip install pandas numpy scikit-learn jupyter
```

## 🚀 Cara Menjalankan

```bash
# Jalankan notebook clustering
jupyter notebook "[Clustering]_Submission_Akhir_BMLP_Dimas_Satria.ipynb"

# Jalankan notebook classification
jupyter notebook "[Klasifikasi]_Submission_Akhir_BMLP_Dimas_Satria.ipynb"
```

## 📊 Output

- 📄 `data_clustering.csv` — data hasil clustering
- 🧩 `model_clustering.h5` — model clustering tersimpan
- 🌳 `decision_tree_model.h5` — model klasifikasi tersimpan

## 👨‍💻 Author

**Dimas Satria Nugroho**
GitHub: [@dmsstrn2704-ai](https://github.com/dmsstrn2704-ai)
