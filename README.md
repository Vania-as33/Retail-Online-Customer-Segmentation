# Retail-Online-Customer-Segmentation
UAS Analisis Big Data – Kelompok 3 (2022A)
- VANIA TITANISA INDRAWAN		22031554009
- RESHAR FALDI JULIANDA 		22031554025
- ALDORA NOVRIZAL NITIMANTA	22031554033
- DEVIN AULIA ASSHAFA		  	22031554037

## Deskripsi Proyek
Proyek ini bertujuan untuk melakukan segmentasi pelanggan (customer segmentation) pada data transaksi retail online menggunakan pendekatan analisis data dan machine learning (clustering).
Segmentasi pelanggan dilakukan untuk mengelompokkan pelanggan berdasarkan pola perilaku belanja mereka, sehingga dapat memberikan insight yang berguna bagi pengambilan keputusan bisnis, seperti strategi pemasaran dan peningkatan layanan pelanggan.

## Dataset
Dataset yang digunakan berasal dari UCI Machine Learning Repository, berjudul Online Retail.
Link dataset: https://archive.ics.uci.edu/dataset/352/online+retail

Dataset ini berisi data transaksi retail online, termasuk informasi seperti:
- Invoice (ID transaksi)
- StockCode (ID produk)
- Description (deskripsi produk)
- Quantity (jumlah produk)
- InvoiceDate (tanggal & waktu)
- UnitPrice (harga satuan)
- CustomerID
- Country (negara)

## Metodologi
Tahapan analisis dalam proyek ini meliputi:
1. Data Understanding
  - Memahami struktur dan karakteristik dataset
  - Mengidentifikasi fitur-fitur penting dalam data transaksi
2. Data Preprocessing
  - Menangani data hilang (missing values)
  - Menghapus data duplikat
  - Mengubah format data (misalnya kolom tanggal dan waktu)
  - Standarisasi fitur numerik
3. Feature Engineering
  - Membentuk fitur perilaku pelanggan (misalnya total transaksi, frekuensi pembelian, dan total pengeluaran)
  - Agregasi data transaksi berdasarkan pelanggan
4. Clustering / Customer Segmentation
  - Menggunakan algoritma clustering (eksperimen menggunakan K-Means dan Hierarchical)
  - Menentukan jumlah cluster optimal
  - Melakukan pelabelan segmen pelanggan
5. Evaluasi dan Interpretasi
  - Menganalisis karakteristik tiap segmen pelanggan
  - Menarik insight bisnis dari hasil segmentasi

## Langkah-Langkah Menjalankan Project
1. Data Collecting
  - Unduh dataset dari UCI: https://archive.ics.uci.edu/dataset/352/online+retail
  - Simpan file .xlsx secara lokal.
2. Install Library
  - install library yang akan digunakan seperti: pandas, numpy, matplotlib, seaborn, scikit-learn (jika belum menginstall library)
3. Load Dataset
4. Data Cleaning
  - Hapus duplikat
  - Tangani missing values
  - Konversi tanggal
5. Feature Engineering
  - Buat fitur seperti total pembelian, frekuensi transaksi, dll.
6. Clustering
  - Menerapkan algoritma K-Means dan Hierarchical untuk segmentasi pelanggan.
7. Evaluation & Visualization
  - Analisis hasil clustering dengan grafik dan statistik.
8. Interpretasi
  - Tarik insight setiap segmen untuk rekomendasi bisnis.
