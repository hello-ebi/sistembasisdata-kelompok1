# Dokumentasi: Pembuatan Tabel MySQL - Kelompok 1

## Mata Kuliah: Sistem Basis Data
**Dosen Pengampu:** Bapak Ahmad Anas, S.Kom., M.Kom.

![Logo Stmik Pamitran](assets/img/logostmikpamitran.png)

## Deskripsi

Dokumentasi dari hasil kerja Kelompok 1 pada mata kuliah *Sistem Basis Data*, yang berfokus pada praktik pengelolaan data menggunakan query `SUM()`, `AVG()`, `ORDER BY`, dan `HAVING`.

---

## Daftar Anggota Kelompok 1

| Nama Lengkap                  | NIM        | Program Studi          |
|------------------------------|------------|------------------------|
| Febrian Eka Putra            | 24424020   | Teknik Informatika     |
| Zulfa Dwi Nugraha            | 244222013  | Manajemen Informatika  |
| Rizky Muhammad Nazwaril Ilham| 244242014  | Teknik Informatika     |
| Yuda Pratama                 | 244222008  | Manajemen Informatika  |

## Kontribusi

### 1. Febrian Eka Putra
- Menyusun rancangan awal.
- Membuat query menggunakan `SUM()`, `AVG()`, `ORDER BY`, dan `HAVING` untuk menjawab soal.
- Memberikan instruksi teknis ke anggota.
- Membuat dokumentasi berupa *README.md*

### 2. Zulfa Dwi Nugraha
- Mencari dan mengumpulkan 20 data yang relevan dengan isi di dalam tugas.
- Menyiapkan data mentah agar siap di-`INSERT` oleh Rizky dan Yuda ke database.

### 3. Rizki Muhammad Nazwaril Ilham
- Membuat Database Kelompok 1.
- Menulis ulang query jawaban soal yang telah disiapkan Febrian.
- `INSERT` 10 data ke tabel query menggunakan MySQL.

### 4. Yuda Pratama
- Membuat tabel **penjualan**.
- Menulis ulang query jawaban soal yang telah disiapkan Febrian.
- `INSERT` 10 data ke tabel query menggunakan MySQL.

---

## Informasi Tugas Kelompok

![Informasi Tugas Kelompok](assets/img/informasitugassistembasisdata.jpg)

---

## 📸 Screenshot Query dan Penyelesaian Tugas ✅ 

### 📌 Jawaban No. 1 — Struktur Tabel

`CREATE DATABASE`, `USE` database yang dikerjakan oleh zulfa, dan `CREATE TABLE` yang dikerjakan oleh Rizky dan Yuda.

![create table](assets/screenshots/createtable.png)

`DESC penjualan;`

![desc penjualan](assets/screenshots/descpenjualan.png)

---

### 📌 Jawaban No. 2 — Input Data ke Tabel

proses `INSERT` 20 data oleh Rizky dan Yuda dari data yang telah di riset oleh zulfa sebelumnya.

![insert into](assets/screenshots/insertinto.png)

`SELECT * FROM penjualan;`

![tampilan tabel](assets/screenshots/tabelpenjualan.png)

---

### 📌 Jawaban No. 3 — Query `SUM()`, `AVG()`, dll

#### a. Menghitung jumlah transaksi untuk setiap kategori produk menggunakan `SUM()`

![jumlah transaksi](assets/screenshots/jumlahtransaksitanpawhere.png)

**Menampilkan jumlah transaksi secara spesifik perkategori menggunakan `where`**

- Jumlah Transaksi Elektronik

![sum jumlah transaksi elektronik](assets/screenshots/jumlahtransaksielektonik.png)

- Jumlah Transaksi Pakaian

![sum jumlah transaksi pakaian](assets/screenshots/jumlahtransaksipakaian.png)

- Jumlah Transaksi Makanan

![sum jumlah transaksi makanan](assets/screenshots/jumlahtransaksimakanan.png)

- Jumlah Transaksi Keperluan Rumah Tangga

![sum jumlah transaksi keperluan](assets/screenshots/jumlahtransaksikeperluanrumahtangga.png)

---

#### b. Menghitung total pendapatan untuk setiap kategori produk memakai `SUM()`

![jumlah total penndapatan](assets/screenshots/totalpendapatantanpawhere.png)

**Menampilkan total pendapatan secara spesifik perkategori menggunakan `where`**

- Pendapatan Elektronik

![sum total pendapatan elektronik](assets/screenshots/totalpendapatanelektronik.png)

- Pendapatan Pakaian

![sum total pendapatan pakaian](assets/screenshots/totalpendapatanpakaian.png)

- Pendapatan Makanan

![sum total pendapatan makanan](assets/screenshots/totalpendapatanmakanan.png)

- Pendapatan Keperluan Rumah Tangga

![sum total pendapatan keperluan](assets/screenshots/totalpendapatankeperluanrumahtangga.png)

---

#### c. Menghitung total harga rata-rata untuk setiap kategori memakai `AVG()`

-  Total Harga Rata-rata Elektronik

![avg elektronik](assets/screenshots/avgelektronik.png)

- Total Harga Rata-rata Pakaian

![avg pakaian](assets/screenshots/avgpakaian.png)

- Total Harga Rata-rata Makanan

![avg makanan](assets/screenshots/avgmakanan.png)

- Total Harga Rata-rata Keperluan Rumah Tangga

![avg keperluan rumah tangga](assets/screenshots/avgkeperluanrumahtangga.png)

---
#### d. Menampilkan produk dengan total penjualan terbanyak memakai `ORDER BY`, `DESC`, dan `LIMIT`

![sapu lantai](assets/screenshots/produkpenjualanterbanyak.png)

Produk “Sapu Lantai” menduduki posisi tertinggi penjualan.

---

#### e. Menampilkan semua kategori dengan total penjualan diatas satu juta memakai `HAVING`

![penjualan diatas satu juta](assets/screenshots/penjualandiatassatujuta.png)

Terdapat tiga kategori yang memiliki penjualan di atas satu juta.

---

### 🗒️ Catatan Kelompok 1

Kami tidak memakai function `COUNT()` karena menurut kami isi dari tugas yang diberikan tidak ada yang cocok untuk memakai `COUNT()`, function tersebut hanya bisa menghitung jumlah baris data pada suatu kolom. Jadi jawabannya tidak akan sesuai dengan tugas yang diberikan, yang menekankan penghitungan nilai total suatu kolom dan rata-rata nilai suatu kolom. oleh sebab itu kami hanya memakai `SUM()`, dan `AVG()`. Terimakasih.

---

## 🖼️ Dokumentasi Foto

#### Febrian memberikan intruksi ke setiap anggota

![Intruksi](assets/screenshots/intruksi.png)

#### Zulfa meriset data lengkap dengan kategori jumlah dan total harganya

![Riset](assets/screenshots/upariset.jpeg)

## comingsoon akan di update
