# Preprocessing-Data-Movie
Proyek ini merupakan bagian dari praktikum Data Mining yang berfokus pada tahap preprocessing data menggunakan Python (library Pandas dan Numpy). Dataset yang digunakan adalah data film yang berisi informasi terkait karakteristik film, mulai dari warna film, sutradara, durasi, pendapatan, genre, judul, tahun rilis, bahasa, negara, anggaran, skor IMDB, pemain, serta jumlah suka pada Facebook. Melalui preprocessing, data mentah yang masih memiliki ketidakkonsistenan, nilai kosong, atau format yang tidak sesuai akan dibersihkan dan dipersiapkan sehingga siap untuk digunakan pada tahap analisis lebih lanjut.
## Konteks
Dataset film yang digunakan (movie_sample_dataset.csv) berisi informasi seperti warna film, nama sutradara, durasi, pendapatan (gross), genre, judul film, tahun rilis, bahasa, negara, anggaran (budget), skor IMDB, pemain, hingga jumlah like Facebook. Data ini berjumlah 99 baris dan 13 kolom.
## Problem Statemant
Dataset film yang digunakan masih mengandung berbagai permasalahan, seperti:
1. Nilai kosong (NaN)
2. Penulisan atribut yang tidak konsisten ("Color" vs "color")
3. Data tidak standar (N/A)
4. Tipe data tidak sesuai
5. Informasi "Genre" masih tergabung
6. Penulisan yang belum konsisten (huruf kapital vs huruf kecil)
## Tujuan
Tujuan dari preprocessing ini adalah:
1. Membersihkan data dari nilai hilang
2. Membersihkan data tidak konsisten
3. Membersihkan data tidak standar
4. Melakukan transformasi tipe data agar sesuai dengan kebutuhan analisis
5. Melakukan normalisasi teks untuk memastikan konsistensi
6. Menyimpan data yang sudah bersih dalam file baru sehingga siap untuk digunakan dalam analisis lebih lanjut.
## Dataset
Dataset yang digunakan adalah movie_dataset.csv, berisi berbagai atribut film seperti:
1. Warna film
2. Nama sutradara
3. Durasi
4. Pendapatan (gross)
5. Genre
6. Judul film
7. Tahun rilis
8. Bahasa
9. Negara
10. Anggaran (budget)
11. Skor IMDB
12. Pemain
14. Jumlah suka di Facebook

Dataset ini kemudian diproses menggunakan Python dan library Pandas.

Jumlah data: 99 baris x 13 kolom
## Hasil
Setelah dilakukan preprocessing:
1. Data kosong pada kolom penting seperti gross dan budget berhasil dihapus.
2. Ketidakkonsistenan teks (“Color” vs “color”) berhasil dinormalisasi.
3. Nilai tidak standar seperti “N/A” telah ditangani.
4. Tipe data telah diubah sesuai format yang benar.
5. Data sudah konsisten setelah dinormalisasi.
6. Data bersih disimpan ke dalam file baru movie_dataset_cleaned.csv.
## Kesimpulan
Proses preprocessing membantu menemukan masalah awal dalam dataset, terutama inkonsistensi penulisan dan potensi nilai yang tidak standar. Setelah dibersihkan, dataset akan lebih siap digunakan untuk analisis atau pemodelan lebih lanjut.
## Rekomendasi
1. Lakukan pembersihan teks dengan str.lower() pada kolom teks seperti color.
2. Periksa nilai kosong pada kolom penting (budget, gross, imdb_score) dan tentukan apakah akan dihapus atau diisi.
3. Simpan dataset bersih dalam file movie_dataset_cleaned.csv untuk digunakan pada tahap analisis berikutnya.
4. Lanjutkan ke tahap Exploratory Data Analysis (EDA) untuk mencari insight dari data film.
