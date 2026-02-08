# Credit-Risk-Prediction-IDX-Partners
📌 Project Overview
Proyek ini adalah bagian dari Project-Based Internship (PBI) di ID/X Partners x Rakamin Academy. Fokus utamanya adalah membangun model Machine Learning yang mampu memprediksi risiko gagal bayar (credit risk) pada platform pinjaman. Dengan menggunakan dataset historis, proyek ini bertujuan untuk membantu perusahaan memitigasi kerugian finansial melalui sistem persetujuan kredit otomatis.

🚀 Business Objectives
Mitigasi Risiko: Mengidentifikasi karakteristik nasabah yang berpotensi gagal bayar (Bad Loan).
Otomasi: Membangun sistem scoring otomatis untuk mempercepat proses decision making.
Insights: Memberikan rekomendasi strategis bagi tim manajemen terkait kebijakan pemberian pinjaman.

🛠️ Tech Stack & Tools
Language: R
Libraries: tidyverse, caret, reshape2, randomForest, themis, recipes, pROC, xgboost, Ckmeans.1d.dp
Technique: SMOTE (untuk menangani Imbalanced Data), Random Search/Grid Search (untuk Hyperparameter Tuning).

📊 Key Findings (EDA)
Inquiries: Nasabah dengan jumlah pencarian kredit tinggi dalam 6 bulan terakhir memiliki risiko gagal bayar yang lebih besar.
Home Ownership: Nasabah dengan status tempat tinggal 'RENT' (Sewa) cenderung memiliki tingkat default lebih tinggi dibanding pemilik rumah.
Credit Grade: Terdapat korelasi kuat di mana penurunan sub-grade kredit berbanding lurus dengan peningkatan risiko gagal bayar.

📈 Model Performance
Model terbaik yang digunakan dalam proyek ini adalah XGBoost dengan hasil evaluasi:
AUC Score: 0,691
KS Statistic: 0,28
Note: Model telah dioptimasi menggunakan SMOTE untuk mengatasi ketidakseimbangan data target.

📂 Repository Structure
data/: Directory untuk dataset (jika diperbolehkan diunggah).
notebook/: File kodingan (.R dan .Rmd).
output/: Hasil visualisasi dan grafik.
report/: File PDF Presentasi (Infografis).
