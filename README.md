☕ Coffee Shop Customer Analytics with PySpark & MlLib

Project ini menganalisis data transaksi Coffee Shop X untuk memahami **pola perilaku pelanggan**, membantu optimasi **stok produk** dan **penjadwalan staf** menggunakan Apache Spark (PySpark).

---

🔧 Tech Stack

- PySpark: ETL, Data Cleaning, RDD, Spark SQL, dan Machine Learning.
- HDFS: Penyimpanan data raw & processed.
- Python: Analisis tambahan dan visualisasi.
- Parquet: Format data efisien untuk Big Data.

---

📊 Key Insights

1. Pola Waktu: Teridentifikasi jam-jam **peak hour** berdasarkan transaksi historis.
2. Perilaku Belanja: Perbedaan karakter pelanggan pagi, siang, dan akhir pekan.
3. Segmentasi Pelanggan: Clustering mengungkap tipe pembeli seperti _Morning Coffee Run_ dan _Lunch Crowd_.

---

🚀 Cara Menjalankan

1. Clone repository ini.
2. Jalankan **Analisis*Pola_Transaksi_dan_Segmentasi_Pelanggan_Coffee_Shop_Menggunakan_PySpark*&\_MLlib.ipynb** untuk generate data processed.
3. Pastikan Spark & HDFS sudah berjalan.
4. Jalankan notebook sesuai urutan modul (ETL → EDA → Modeling).

---

📦 Output

- Dataset bersih format **Parquet** (`/processed`)
- Insight bisnis berbasis data
- Model K-Means untuk segmentasi pelanggan

> Project ini dirancang sebagai simulasi **end-to-end Data Engineering & Analytics Pipeline**.
