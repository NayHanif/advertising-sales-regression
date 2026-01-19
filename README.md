# advertising-sales-regression
Implementasi Regresi Linier Berganda menggunakan dataset Advertising berdasarkan buku Pengantar Data Science karya Nova Agustina.

# Analisis Regresi Linier Berganda - Penjualan Produk

Proyek ini merupakan implementasi studi kasus **Regresi Linier Berganda** menggunakan Python untuk memprediksi angka penjualan (*Sales*) berdasarkan biaya iklan di berbagai media (TV, Radio, dan Newspaper).

## Deskripsi Proyek
Tujuan dari proyek ini adalah untuk menemukan garis yang paling sesuai (*best fit line*) dan menyusun persamaan matematika yang menggambarkan hubungan antara variabel biaya promosi dengan hasil penjualan. 

Proyek ini mencakup:
* Eksplorasi dan pembersihan data.
* Pembangunan model regresi menggunakan `scikit-learn` dan `statsmodels`.
* Visualisasi hasil prediksi dibandingkan data aktual.
* Pembuatan persamaan regresi dan interpretasi koefisien.

## Referensi Belajar
Kode dan metodologi dalam notebook ini dipelajari dan dikembangkan berdasarkan referensi dari buku:
> **Pengantar Data Science: Teori, Teknik, dan Aplikasinya di Era Digital** > Karya: *Nova Agustina, dkk.*

## Dataset
Dataset yang digunakan adalah **Advertising Dataset**, yang mencakup kolom:
- `TV`: Biaya iklan TV (dalam ribuan dolar).
- `Radio`: Biaya iklan Radio.
- `Newspaper`: Biaya iklan Surat Kabar.
- `Sales`: Penjualan produk (Target).

## Hasil Analisis
Model menghasilkan persamaan regresi sebagai berikut:
**Sales = 2.94 + (0.05 x TV) + (0.19 x Radio) + (-0.00 x Newspaper)**

Berdasarkan hasil ini, dapat disimpulkan bahwa iklan di media **Radio** memiliki pengaruh paling signifikan terhadap kenaikan penjualan dibandingkan media lainnya dalam dataset ini.

## Library yang Digunakan
* `Pandas` & `Numpy` (Manipulasi Data)
* `Matplotlib` & `Seaborn` (Visualisasi Data)
* `Scikit-Learn` & `Statsmodels` (Pemodelan Statistik)

---
*Dibuat untuk tujuan pembelajaran mandiri dalam bidang Data Science.*
