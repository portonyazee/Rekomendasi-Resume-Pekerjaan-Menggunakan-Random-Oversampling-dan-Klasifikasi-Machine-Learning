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
1.	Model klasifikasi otomatis berbasis machine learning dapat digunakan untuk merekomendasikan kategori pekerjaan berdasarkan isi resume dengan cukup baik.
2.	Dari tiga algoritma yang diuji, yaitu K-Nearest Neighbors (KNN), Random Forest, dan Naïve Bayes, algoritma Random Forest menunjukkan performa terbaik. Pada pengujian menggunakan Classification Resume Dataset yang terdiri dari 13.306 data, Random Forest memperoleh hasil terbaik pada fold ke-1 dengan accuracy sebesar 87,95%, precision 88,46%, recall 87,95%, dan f1-score 87,79%. Sementara itu, pada Jobstreet Dataset yang berjumlah 56.106 data, performa terbaik juga ditunjukkan oleh Random Forest pada fold ke-4, dengan nilai accuracy 97,93%, precision 97,92%, recall 97,93%, dan f1-score 97,91%. 
3.	Penerapan metode Random Oversampling (ROS) efektif dalam menangani ketidakseimbangan data, terbukti dengan peningkatan akurasi dan f1-score pada algoritma yang diuji.
4.	Hasil pengujian menunjukkan bahwa penggabungan teknik preprocessing yang tepat (TF-IDF, label encoding, feature selection) dengan algoritma yang sesuai dapat meningkatkan efisiensi dan akurasi proses rekrutmen berbasis dokumen.
