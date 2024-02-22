# Diabetes Disease Prediction Using Deep Learning

## Overview
Proyek ini bertujuan untuk mengembangkan sistem prediksi penyakit diabetes yang akurat dan efisien dengan menggunakan teknologi deep learning. Sistem ini dirancang untuk mendeteksi potensi penyakit diabetes pada pasien wanita di Amerika Utara (Pima Indians), berdasarkan dataset yang tersedia di [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

## Background
Diabetes adalah masalah kesehatan yang serius yang memerlukan deteksi dini untuk mencegah komplikasi. Dengan menggunakan teknologi deep learning, proyek ini bertujuan untuk meningkatkan akurasi diagnostik penyakit diabetes dibandingkan metode tradisional, memungkinkan deteksi dini dan intervensi yang lebih cepat.

## Dataset
Dataset terdiri dari 768 baris dengan 9 kolom, mencakup informasi tentang jumlah kehamilan, konsentrasi glukosa, tekanan darah, ketebalan lipatan kulit trisep, insulin, indeks massa tubuh (BMI), fungsi silsilah diabetes, umur, dan outcome (hasil).

## Models Explored
- **Narrow Shallow Model**: Model dengan sedikit lapisan dan sedikit neuron per lapisan.
- **Narrow Wide Model**: Model dengan sedikit lapisan tetapi lebih banyak neuron per lapisan.
- **Deep Shallow Model**: Model dengan lebih banyak lapisan, di mana lapisan pertama lebih "wide" dan lapisan berikutnya lebih "narrow".
- **Deep Wide Model**: Model dengan kombinasi banyak lapisan dan banyak neuron per lapisan.

## Hyperparameter Tuning
Eksperimen tuning hyperparameter dilakukan menggunakan Random Search untuk menemukan konfigurasi terbaik dari setiap model.

## Results
Hasil dari eksperimen menunjukkan potensi pendekatan deep learning dalam meningkatkan akurasi prediksi diabetes. Evaluasi model terbaik dilakukan menggunakan dataset pengujian untuk mengukur efektivitas sistem prediksi.

## How to Use
Instruksi tentang cara menjalankan kode, termasuk instalasi library yang diperlukan (`keras-tuner`, `tensorflow`, dll.), pemisahan data, pelatihan model, dan evaluasi, disediakan dalam notebook.

### Team Name: The Woz (Computer Vision)

---

**Created By:**

- C Yongky Pranowo
- Faiq Fahreza
- Aditya Lesmana
- Bernadetta Alnybera F
- Fatkur Alfian
- Habibullah
- Ibnu

---

