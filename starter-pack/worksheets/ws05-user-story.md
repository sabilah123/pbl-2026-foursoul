## WORKBOOK: LEMBAR KERJA MAHASISWA WS05

## Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria

Mata Kuliah: Konsep Sistem Informasi (KSI)

Kerangka Kerja: Project-Based Learning (PBL) Level 1

Fase Learning Spine: Fase 3 — Define (Minggu 3)

Sub-CPMK / SFIA: S-01.1 (Intermediate - Problem Framing) & S-03.1 (Intermediate -

Pemetaan SI) | SFIA BUSA L1, REQM L2

Keterkaitan Deliverable: Bahan Utama Deliverable D2 (System & Solution Design - TPL-02)

- 1. Identifikasi Kelompok & Rotasi Kepemimpinan

- Nama Kelompok: ________________________________________

- Objek UMKM Mitra: ________________________________________

- Phase Lead 3 (Define): ________________________________________ (Mahasiswa C)

- Anggota Tim: 1. ___________________ 2. ___________________ 3. ___________________

## 2. Landasan Konseptual: Analisis Sistem "What" vs "How"

Dalam tahap Systems Analysis, fokus utama tim adalah menentukan APA (What) yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, BUKAN BAGAIMANA (How) sistem dibangun secara teknis (Marakas & O'Brien, 2013).

- User Story merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola:

- \$\$\text{"Sebagai [Peran Pengguna], Saya ingin [Kemampuan/Fitur], Sehingga [Manfaat Bisnis Nyata]"}\$\$

- Acceptance Criteria (Given-When-Then) mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021).


## 3. Workspace A: Formulasi User Story Fungsional

Petakan minimal 3 User Story Utama yang langsung menjawab akar masalah pada D1 / WS04:

User Story 1 (Prioritas Utama / Core Feature)

● Sebagai (As a):

\__________________________________________________________________

(misal: Kasir Toko Kelontong)

● Saya ingin (I want to):

___________________________________________________________ (misal:

mencatat transaksi penjualan dengan memilih barang dari daftar dan menghitung total otomatis)

● Sehingga (So that):

______________________________________________________________ (misal:

waktu transaksi berkurang dan tidak terjadi kesalahan hitung uang kembalian)

User Story 2 (Fitur Manajemen Stok / Data)

● Sebagai (As a):

\__________________________________________________________________

(misal: Pemilik Usaha UMKM)

● Saya ingin (I want to):

___________________________________________________________ (misal:

melihat jumlah stok barang yang tersisa secara real-time dan mendapatkan peringatan stok menipis)

● Sehingga (So that):

______________________________________________________________ (misal:

saya dapat melakukan pemesanan ulang barang tepat waktu sebelum stok habis)

User Story 3 (Fitur Pelaporan / Informasi)

● Sebagai (As a):

\__________________________________________________________________

(misal: Pemilik Usaha UMKM)

● Saya ingin (I want to):

___________________________________________________________ (misal:

melihat ringkasan total pendapatan harian dan daftar 3 barang terlaris)

● Sehingga (So that):

______________________________________________________________ (misal: saya tidak perlu menghitung nota fisik secara manual selama 1.5 jam setiap malam)


## 4. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When- Then)

Susun kriteria penerimaan terstruktur untuk User Story 1 (mencakup Skenario Sukses dan Skenario Penanganan Eror):

Skenario 1A: Transaksi Penjualan Berhasil (Happy Path)

- Diberikan (Given):

_______________________________________________________________ (misal:

Kasir berada di layar utama transaksi dan stok produk "Teguk Boba" tersedia sebanyak 10 unit)

- Ketika (When):

\__________________________________________________________________

(misal: Kasir memasukkan jumlah pesanan 2 unit dan mengklik tombol bayar dengan nominal pas)

- Maka (Then):

\___________________________________________________________________

(misal: Sistem menampilkan bukti transaksi sukses, menghitung kembalian Rp 0, dan mengurangi stok otomatis menjadi 8 unit)

Skenario 1B: Penanganan Pembayaran Kurang / Eror (Exception Path)

- Diberikan (Given):

_______________________________________________________________ (misal:

Total belanja transaksi adalah Rp 35.000)

- Ketika (When):

\__________________________________________________________________

(misal: Kasir memasukkan nominal pembayaran Rp 30.000)

- Maka (Then):

\___________________________________________________________________

(misal: Sistem menolak transaksi, menampilkan pesan eror "Nominal pembayaran kurang Rp 5.000", dan stok barang tidak berkurang)

## 5. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)

- Tanggal Validasi: ____________________

- Narahubung Mitra: ____________________ (Pemilik / Staf Kasir)

- Hasil Konfirmasi User Story:

[ ] Seluruh User Story disetujui mitra

[ ] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada):


## 6. Verifikasi Integritas AI (TPL-07) & Pengesahan

## ● Penggunaan AI Co-pilot:

Apakah tim menggunakan AI untuk membantu merumuskan skenario Given-When-

Then? [ ] Ya [ ] Tidak (Jika Ya, wajib melampirkan formulir TPL-07: AI Usage Disclosure & Verification Note).

## Tanda Tangan Tim & Pengesahan Dosen:

- Phase Lead 3: _______________________ (Tanggal: __________)

- Dosen Coach: _______________________ (Tanggal: __________) [ ] Approved
