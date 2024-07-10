# SaaS Sales Data Analysis

### Topik
##### Bagaimana diskon mempengaruhi profitabilitas secara keseluruhan?

## Overview
Proyek ini menganalisis dampak diskon terhadap profitabilitas perusahaan SaaS (perusahaan fiktif). Analisisnya melibatkan pembersihan data, statistik deskriptif, analisis korelasi, dan regresi linier untuk memahami bagaimana diskon mempengaruhi penjualan dan profit. Dataset ini berisi data transaksi dari perusahaan SaaS fiktif yang menjual software penjualan dan pemasaran ke perusahaan lain (B2B).

## Dataset
Dataset yang digunakan dalam proyek ini adalah `SaaS-Sales.csv`, yang berisi kolom berikut:
- **Order ID:** Pengidentifikasi unik untuk setiap pesanan
- **Order Date:** Tanggal pemesanan
- **Customer ID:** Pengidentifikasi unik untuk setiap pelanggan
- **Discount:** Diskon berlaku untuk pesanan
- **Sales:** Jumlah penjualan pesanan
- **Profit:** Jumlah keuntungan pesanan

## Struktur Proyek
Proyek ini disusun sebagai berikut:

## Langkah Analisis

### 1. Data Loading dan Data Cleaning
- Muat data dari file CSV.
- Periksa dan tangani nilai yang hilang.
- Periksa tipe data dan pastikan sudah sesuai.

### 2. Statistik Deskriptif
- Hitung dan tampilkan statistik ringkasan untuk Discount, Sales, dan Profit.

### 3. Analisis Korelasi
- Menghitung dan memvisualisasikan matriks korelasi untuk Discount, Sales, dan Profit.

### 4. Visualisasi
- Buat plot sebar untuk memvisualisasikan hubungan antara:
 - Discount dan Profit
 - Sales dan Profit
 - Discount dan Sales

### 5. Analisis Regresi
- Melakukan regresi linier untuk memodelkan Profit berdasarkan Discount dan Sales.
- Visualisasikan garis regresi pada scatter plots.

### 6. Integrasi Tableau
- Gunakan Tableau untuk analisis interaktif dan terperinci.
- Buku kerja Tableau `Tableau_Analysis.twbx` mencakup berbagai visualisasi dan dasbor untuk mengeksplorasi data lebih jauh.

## Insights dan Recommendation
Berdasarkan analisis, insight penting diperoleh untuk membantu pemangku kepentingan memahami dampak diskon terhadap profitabilitas dan membuat keputusan berdasarkan data. Untuk insight detail, lihat hasil visualisasi dan regresi di folder output (Grafik) dan Tableau workbook.

### Insight Utama:
1. **Analisis Korelasi:**
 - Terdapat korelasi negatif yang lemah antara Discount dan Profit.
 - Terdapat korelasi positif antara Sales dan Profit.

2. **Visualisasi:**
 - Scatter plots menunjukkan bahwa diskon yang lebih tinggi tidak selalu menghasilkan profit yang lebih tinggi.
 - Sales mempunyai dampak positif yang lebih langsung terhadap Profit dibandingkan Diskon.

3. **Analisis Regresi:**
 - Model regresi menunjukkan bahwa meskipun Diskon dan Sales merupakan prediktor Profit yang signifikan, Sales mempunyai pengaruh yang lebih kuat terhadap Profit dibandingkan Diskon.

### Rekomendasi:
- **Strategi Diskon:**
 - Evaluasi kembali strategi diskon karena diskon yang lebih tinggi tidak memberikan kontribusi signifikan terhadap peningkatan keuntungan.
 - Pertimbangkan untuk mengoptimalkan tingkat diskon untuk menyeimbangkan antara menarik pelanggan dan mempertahankan profitabilitas.

- **Strategi penjualan:**
 - Fokus pada strategi yang mendorong volume penjualan, karena penjualan memiliki dampak yang lebih besar terhadap profitabilitas.
 - Jelajahi cara untuk meningkatkan akuisisi dan retensi pelanggan tanpa terlalu bergantung pada diskon.

**Tableau workbook:**
- Gunakan Tableau Public atau Tableau Desktop untuk membuka 'link_tableau??????????????' untuk analisis interaktif.

