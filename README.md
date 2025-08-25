# Rekomendasi-Resume-Pekerjaan-Menggunakan-Random-Oversampling-dan-Klasifikasi-Machine-Learning
Proyek ini bertujuan untuk membangun sistem rekomendasi kategori pekerjaan berdasarkan data resume menggunakan metode Random Oversampling untuk mengatasi ketidakseimbangan kelas, serta beberapa algoritma Machine Learning Classification sebagai model prediksi.

# Dataset
Dataset : https://huggingface.co/datasets/azrai99/job-dataset dan https://media.githubusercontent.com/media/noran-mohamed/Resume-Classification-Dataset/refs/heads/main/Preprocessed_Data.csv

Dilakukan preprocessing meliputi:
1. Cleaning (menghapus data kosong, duplikasi, dan karakter khusus).
2. Text preprocessing (case folding, stopwords removal, tokenization).
3. Feature extraction menggunakan TF-IDF.

# Metodologi
<img width="837" height="262" alt="image" src="https://github.com/user-attachments/assets/f603e124-edc4-45d1-9e54-137775415511" />

# Hasil
1. Model terbaik menunjukkan performa dengan nilai F1-Score tertinggi setelah penanganan imbalanced dataset.
2. Random Oversampling berhasil meningkatkan akurasi prediksi untuk kelas minoritas.
