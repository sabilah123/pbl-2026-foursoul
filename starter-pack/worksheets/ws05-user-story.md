# **WORKBOOK: LEMBAR KERJA MAHASISWA WS05**

## **Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria**

Mata Kuliah: **Konsep Sistem Informasi (KSI)**  
Kerangka Kerja: **Project-Based Learning (PBL) Level 1**  
Fase Learning Spine: **Fase 3 — Define (Minggu 3)**  
Sub-CPMK / SFIA: **S-01.1 (Intermediate - Problem Framing) & S-03.1 (Intermediate - Pemetaan SI)** | **SFIA BUSA L1, REQM L2**  
Keterkaitan Deliverable: **Bahan Utama Deliverable D2 (System & Solution Design - TPL-02)**

### **1\. Identifikasi Kelompok & Rotasi Kepemimpinan**

- **Nama Kelompok**: Four Souls
- **Objek UMKM Mitra**: Laundry Que
- **Phase Lead 3 (Define)**: Najma Zahrani Salsabila
- **Anggota Tim**: 1. Hanasyah Syuhara Ratu 2. Rifda Muthia Asysyifa 3. Salsabila Prasong

### **2\. Landasan Konseptual: Analisis Sistem "What" vs "How"**

Dalam tahap _Systems Analysis_, fokus utama tim adalah menentukan **APA (_What_)** yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, **BUKAN BAGAIMANA (_How_)** sistem dibangun secara teknis (Marakas & O'Brien, 2013).

- **User Story** merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola:  
  \$\$\\text{"Sebagai \[Peran Pengguna\], Saya ingin \[Kemampuan/Fitur\], Sehingga \[Manfaat Bisnis Nyata\]"}\$\$
- **Acceptance Criteria (Given-When-Then)** mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021).

### **3\. Workspace A: Formulasi User Story Fungsional**

Petakan minimal **3 User Story Utama** yang langsung menjawab akar masalah pada D1 / WS04:

#### **User Story 1 (Prioritas Utama / Core Feature)**

- **Sebagai (_As a_)**: Karyawan laundry que.
- **Saya ingin (_I want to_)**: Mengajukan dan memantau kebutuhan stok sabun, pewangi, dan gas melalui aplikasi.
- **Sehingga (_So that_)**: Permintaan stok menjadi lebih terkoordinasi,mengurangi kesalahan saat berkomunikasi dengan admin, dan memastikan stok tersedia sebelum habis.

#### **User Story 2 (Fitur Penyimpanan Data)**

- **Sebagai (_As a_)**: Karyawan laundry que.
- **Saya ingin (_I want to_)**: Menginput data pelanggan yang ingin melaundry seperti nama pelanggan. nomor pelanggan, dan jenis pelayanan yang akan digunakan
- **Sehingga (_So that_)**: Proses pencatatan laundry mejadi lebih mudah dan terstruktur, mengurangi keterlembatan antrean dan mempermudah karyawan mengelola data pelanggan

#### **User Story 3 (Fitur Pelaporan / Informasi)**

- **Sebagai (_As a_)**: Karyawan laundry que.
- **Saya ingin (_I want to_)**: Melaporkan serta mengawasi kerusakan mesin cuci melalui aplikasi.
- **Sehingga (_So that_)**: Mesin yang rusak bisa segera ditemukan dan diperbaiki sehingga tidak menghambat pelayanan proses laundry.

### **4\. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When-Then)**

Susun kriteria penerimaan terstruktur untuk **User Story 1** (mencakup Skenario Sukses dan Skenario Penanganan Eror):

#### **Skenario 1A: Pelaporan Kebutuhan Stok Berhasil (Happy Path)**

- **Diberikan (_Given_)**: Karyawan mengetahui bahwa stok sabun/pewangi/gas elpiji habis, dan menginginkan agar admin segera mengirimkan kembali persediaan bahan baku.
- **Ketika (_When_)**: Karyawan mengisi formulir permintaan stok gas/sabun/gas elpiji melalui aplikasi.
- **Maka (_Then_)**: Sistem menyimpan data permintaan kebutuhan stok tersebut, dan mengirimkannya ke admin supaya persediaan stok bisa di proses.

#### **Skenario 1B: Pengajuan Stok Tidak Lengkap (Exception Path)**

- **Diberikan (_Given_)**: Karyawan mengisi formulir pengajuan stok yang dibutuhkan melalui aplikasi.
- **Ketika (_When_)**: Karyawan mengirim pengajuan tanpa mengisi jenis barang atau jumlah stok yang dibutuhkan.
- **Maka (_Then_)**: Sistem menampilkan pemberitahuan bahwa data pengajuan belum lengkap dan meminta karyawan untuk melengkapi formulir pengajuan

#### **Skenario 2A: Pendaftaran Pelanggan Berhasil (Happy Path)**

- **Diberikan (_Given_)**: Karyawan menerima pelanggan yang ingin me-laundry dan harus memasukkan data ke aplikasi.
- **Ketika (_When_)**: Karyawan masukkan data pelanggan seperti nama pelanggan, nomor whatsapp dan layanan yang ingin di gunakan.
- **Maka (_Then_)**: Sistem menyimpan data pelanggan beserta jenis layanan yang digunakan dan sistem menampilkan bahwa pendaftaran berhasil dilakukan.

#### **Skenario 2B: Pendaftaran Data Pelanggan Tidak Lengkap (Exception Path)**

- **Diberikan (_Given_)**: Karyawan menginput data pelanggan melalui aplikasi.
- **Ketika (_When_)**: Karyawan mengirim data pelanggan tidak menginput jenis layanan apa yang digunakan.
- **Maka (_Then_)**: Sistem menampilkan pemberitahuan bahwa data belum lengkap dan meminta karyawan menginput data yang belum lengkap.

#### **Skenario 3A: Pelaporan Kerusakan Mesin Berhasil (Happy Path)**

- **Diberikan (_Given_)**: Karyawan sedang menggunakan aplikasi, dan salah satu mesin laundry ada yang menggalami kerusakan.
- **Ketika (_When_)**: Karyawan melaporkan kerusakan dengan mengisi nomor mesin, dan jenis mesin apa yang menggalami kerusakan melalui aplikasi.
- **Maka (_Then_)**: Sistem menyimpan laporan tersebut dan menampilkan informasi mesin yang rusak kepada admin supaya segera ditangani.

#### **Skenario 3B: Penangganan Laporan Kerusakan Tidak Lengkap (Exception Path)**

- **Diberikan (_Given_)**: Karyawan sedang mengisi laporan kerusakan mesin melalui aplikasi.
- **Ketika (_When_)**: Karyawan mengirim laporan tanpa mengisi jenis mesin apa yang menggalami kerusakan.
- **Maka (_Then_)**: Sistem menolak laporan sementara dan menampilkan agar karyawan mengisi informasi yang masih kosong.

### **5\. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)**

- **Tanggal Validasi**: 11 November 2026
- **Narahubung Mitra**: Ratih Oktafiani (Staf)
- **Hasil Konfirmasi User Story**:  
  \[✓\] Seluruh User Story disetujui mitra  
  \[×\] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada):

### **6\. Verifikasi Integritas AI (TPL-07) & Pengesahan**

- **Penggunaan AI Co-pilot**:  
  Apakah tim menggunakan AI untuk membantu merumuskan skenario _Given-When-Then_? Tidak  
  _(Jika Ya, wajib melampirkan formulir_ **_TPL-07: AI Usage Disclosure & Verification Note_**_)_.

**Tanda Tangan Tim & Pengesahan Dosen**:

- **Phase Lead 3**: Najma Zahrani Salsabila (Tanggal: 7 November 2026)
- **Dosen Coach**: Faturahman Saputra (Tanggal: 7 November 2026) \[✓\] Approved