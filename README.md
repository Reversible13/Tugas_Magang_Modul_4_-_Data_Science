# Exploratory Data Analysis: Tokopedia Product Insight (Modul 4)

## Contributors

- **Muhammad Maulana Rosyid** - *Technical Data Analyst* (Fokus pada Data Cleaning, Visualisasi Multivariat, dan Implementasi Logarithmic Scaling).
- **Rifat Qoyyim Sidik** - *Business Intelligence Researcher* (Fokus pada Interpretasi Bisnis Tahap 5, Riset Sentimen Marketplace, dan Perumusan Rekomendasi Strategis).
- **Kelompok 1 - Universitas Terbuka (UT)**

## Project Overview 
Proyek ini merupakan bagian dari tugas magang **Divisi Data Science**. Fokus utama proyek ini adalah melakukan *Exploratory Data Analysis* (EDA) pada dataset produk marketplace (Tokopedia) untuk memahami korelasi antara harga, kategori produk, dan sentimen pelanggan.

Tujuan akhirnya adalah mentransformasi data mentah menjadi **Actionable Business Insights** yang dapat mendukung pengambilan keputusan manajerial.

---

## Metodologi yang diterapkan

Proyek ini dibagi menjadi 5 tahap sistematis:

1.  **Tahap 1: Data Cleaning & Preparation**
    * Identifikasi dan penanganan *missing values*.
    * Standarisasi tipe data dan pembersihan anomali.
2.  **Tahap 2: Univariate Analysis**
    * Analisis distribusi harga per kategori produk.
    * Implementasi **Logarithmic Scaling** pada Boxplot untuk menangani data yang *skewed*.
3.  **Tahap 3: Sentiment Analysis Mapping**
    * Visualisasi persepsi pelanggan berdasarkan ulasan produk.
4.  **Tahap 4: Multivariate Analysis**
    * Mengeksplorasi hubungan antara `product_price`, `sold_count`, dan `rating`.
5.  **Tahap 5: Business Synthesis & Recommendation**
    * Merumuskan solusi manajerial berdasarkan temuan teknis dari tahap sebelumnya.

---

## Key Insights & Rekomendasi (Tahap 5)

Berdasarkan hasil analisis kelompok, ditemukan beberapa poin strategis:
* **Price-Sentiment Correlation:** Terdapat pola unik di mana kategori produk tertentu menunjukkan sensitivitas harga yang tinggi terhadap kepuasan pelanggan.
* **Outlier Detection:** Identifikasi produk dengan volume penjualan tinggi meskipun berada pada rentang harga premium.
* **Strategic Action:** Rekomendasi optimasi *pricing strategy* untuk meningkatkan daya saing di kategori produk dengan sentimen netral.
