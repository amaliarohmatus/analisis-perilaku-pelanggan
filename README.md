# Analisis Perilaku Pelanggan

Proyek ini bertujuan untuk memahami karakteristik dan perilaku belanja pelanggan melalui pendekatan analisis data. Mulai dari eksplorasi data (EDA) hingga segmentasi pelanggan menggunakan K-Means Clustering. Hasil analisis diharapkan dapat membantu perusahaan menyusun strategi marketing yang lebih tepat sasaran dan berbasis data.

---

## Tujuan Analisis

1. Siapa pelanggan yang paling menguntungkan?
2. Apakah kampanye pemasaran sudah efektif?
3. Faktor apa yang paling memengaruhi pelanggan untuk membeli?
4. Apakah pelanggan berpendapatan tinggi selalu lebih sering membeli?
5. Pelanggan lebih suka belanja lewat channel apa?
6. Pelanggan mana yang mulai tidak aktif?

---

## Dataset

Dataset yang digunakan adalah **Marketing Campaign Dataset** yang berisi informasi 
demografis, perilaku belanja, dan respons kampanye dari 2.240 pelanggan.

| File | Keterangan |
|---|---|
| `marketing_campaign.csv` | Dataset asli |
| `customer_segmentation_final.csv` | Dataset hasil clustering |

---

## Alur Analisis

1. **Data Cleaning** — menangani missing value, outlier, dan anomali kategorikal
2. **Feature Engineering** — membuat fitur baru seperti Age, Total_Spending, Total_Purchase
3. **Exploratory Data Analysis (EDA)** — eksplorasi distribusi data, korelasi antar variabel, dan analisis channel belanja
4. **Clustering (K-Means)** — segmentasi pelanggan menjadi 4 kelompok berdasarkan Income, Total_Spending, Recency, dan Total_Purchase

---

## Hasil Segmentasi

| Segmen | Jumlah | Karakteristik |
|---|---|---|
| Pelanggan Setia | 499 | Income tinggi, belanja besar, masih aktif |
| Pelanggan Berisiko | 508 | Income tinggi, belanja besar, mulai tidak aktif |
| Pelanggan Biasa | 580 | Income rendah, belanja kecil, masih aktif |
| Pelanggan Tidak Aktif | 617 | Income rendah, belanja kecil, sudah tidak aktif |

---

## Tools & Library

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (KMeans, StandardScaler, Silhouette Score)
- Google Colab
- Google Looker Studio (visualisasi dashboard)
