# Penerapan Data Stream Mining pada Analisis Transaksi Penjualan Kopi Menggunakan Gaussian Naive Bayes dengan Pendekatan Incremental Learning

## Deskripsi Proyek
Proyek ini bertujuan untuk menerapkan konsep *Data Stream Mining* dalam analisis transaksi penjualan kopi menggunakan algoritma Gaussian Naive Bayes dengan pendekatan *Incremental Learning*. Pendekatan ini digunakan untuk mempelajari proses pembaruan model secara bertahap ketika data transaksi baru diterima.
Melalui proyek ini, data transaksi penjualan kopi diolah untuk memahami karakteristik data dan menerapkan klasifikasi menggunakan Gaussian Naive Bayes. Pendekatan *Incremental Learning* digunakan untuk mempelajari bagaimana model dapat diperbarui secara bertahap tanpa harus dilatih ulang dari awal setiap kali data baru tersedia.

## Dataset
- **Nama Dataset:** Coffee Sales
- **Sumber:** [Kaggle – Coffee Sales](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)
- **Jenis Data:** Data transaksi penjualan kopi.
- **Informasi Data:** Dataset mencakup informasi transaksi, tanggal dan waktu penjualan, jumlah produk, lokasi toko, harga, serta kategori dan jenis produk. <Cite refs={["turn312311search1","turn312311search0"]} />

## Metode yang Digunakan
### 1. Data Stream Mining
Digunakan sebagai pendekatan untuk memproses dan menganalisis data yang diterima secara bertahap, sehingga sesuai untuk mempelajari transaksi yang terus bertambah.
### 2. Gaussian Naive Bayes
Algoritma klasifikasi berbasis probabilitas yang menggunakan Teorema Bayes dengan asumsi distribusi Gaussian pada fitur numerik. Model ini digunakan untuk melakukan klasifikasi berdasarkan fitur yang telah disiapkan.
### 3. Incremental Learning
Pendekatan pembelajaran bertahap yang memungkinkan model memperbarui pengetahuannya menggunakan data baru tanpa harus memulai proses pelatihan dari awal. Penerapannya pada Gaussian Naive Bayes dapat dilakukan melalui pembaruan parameter model secara bertahap.

## Alur Pengerjaan
1. **Memuat Dataset:** membaca data transaksi penjualan kopi dari Kaggle.
2. **Preprocessing Data:** memeriksa dan menyiapkan data agar dapat digunakan dalam proses pemodelan.
3. **Pengolahan Fitur:** memilih serta mengubah fitur yang dibutuhkan sesuai dengan target klasifikasi.
4. **Penerapan Gaussian Naive Bayes:** membangun model klasifikasi berdasarkan data transaksi.
5. **Incremental Learning:** memperbarui model secara bertahap menggunakan data yang diproses per bagian.
6. **Evaluasi Model:** mengevaluasi hasil klasifikasi menggunakan metrik yang diterapkan dalam proyek.

## Tujuan dan Hasil Proyek
Proyek ini memberikan pengalaman dalam mengolah data transaksi penjualan kopi, menerapkan algoritma Gaussian Naive Bayes, serta mempelajari konsep *Incremental Learning* dalam pemrosesan data secara bertahap. Penerapan pendekatan tersebut diharapkan dapat memberikan pemahaman mengenai penggunaan model klasifikasi untuk data transaksi yang terus diperbarui.

