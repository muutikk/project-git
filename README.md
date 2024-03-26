# Project Git
Pada Project kali ini adalah membuat repository yang berisi Tugas Python 5: OOP

## Tugas Python 5: OOP
Pada Tugas Python 5: OOP terdapat 2 Task, yaitu:
1. Basic OOP
2. Inheritance & Polymorphism

### Basic OOP
Memiliki memiliki tiga metode:
1. extract(): akan membaca data dari sebuah file CSV (Misalkan, marketing_data.csv)
2. transform(): akan melakukan pembersihan dan transformasi sederhana pada data (seperti mengubah format tanggal atau membersihkan nilai yang kosong)
3. store(): akan menyimpan data yang telah ditransformasi ke dalam struktur data DataFramet.

### Inheritance & Polymorphism
Memiliki class TargetedMarketingETL yang mewarisi dari MarketingDataETL.
Memiliki metode segment_customers() yang mengelompokkan pelanggan berdasarkan kriteria tertentu (misalnya, pengeluaran total atau kategori produk yang dibeli).
Mendemonstrasikan polymorphism dengan meng-override metode transform() dalam TargetedMarketingETL untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi.