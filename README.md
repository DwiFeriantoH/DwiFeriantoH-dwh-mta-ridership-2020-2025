# Nama Kelompok
1. Vincentius Putra Mahardika (24031554110)
2. Dwi Ferianto Hamzah (24031554019)
3. Salma Latifa Kamil (24031554089)

## Latar Belakang

Pandemi COVID-19 memberikan pengaruh besar terhadap pola mobilitas masyarakat, khususnya pada penggunaan transportasi umum di wilayah metropolitan New York. Jumlah pengguna beberapa moda transportasi mengalami penurunan cukup besar pada awal pandemi, kemudian mulai menunjukkan proses pemulihan pada tahun-tahun berikutnya.

Melalui proyek ini, data ridership harian MTA akan diolah menggunakan alur **Extract, Transform, Load (ETL)**, kemudian disusun ke dalam bentuk Data Warehouse agar dapat dianalisis menggunakan OLAP. Analisis ini bertujuan untuk melihat tren penggunaan transportasi umum dari waktu ke waktu, membandingkan jumlah pengguna antar moda transportasi, serta melihat persentase pemulihan dibandingkan kondisi sebelum pandemi.

## Tujuan Proyek

Tujuan dari proyek ini adalah:

1. Melakukan proses ekstraksi data dari dataset MTA Daily Ridership Data 2020–2025.
2. Melakukan transformasi data agar format data lebih seragam dan siap digunakan dalam Data Warehouse.
3. Melakukan load data ke PostgreSQL/Supabase sebagai database penyimpanan.
4. Merancang star schema untuk kebutuhan Data Mart dan OLAP.
5. Membuat cube OLAP menggunakan Atoti.
6. Menampilkan insight melalui visualisasi atau Atoti Widget.

## Dataset

Sumber dataset:  
https://data.ny.gov/Transportation/MTA-Daily-Ridership-Data-2020-2025/vxuj-8kew/about_data

Dataset ini memiliki granularitas harian dan mencakup data tahun 2020 sampai 2025. Setiap baris data merepresentasikan data pada satu tanggal tertentu. Beberapa atribut utama dalam dataset meliputi tanggal, jumlah ridership atau traffic pada setiap moda transportasi, serta persentase perbandingan terhadap hari prapandemi yang sebanding.

