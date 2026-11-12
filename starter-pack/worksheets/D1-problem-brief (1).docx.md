1. # **D1 — Problem Brief**

**Project**: Digital Problem Framing Mini Project — Laundry Que **Tim**: Salsabilah Prasong, Rifda Muthia Asysyifa, Najma Zahrani Salsabila, Hanasyah Syuhara Ratu \| **Tanggal**: \[07/11/2026\] \| **Versi**: \[v1.0\] **Template**: TPL-01

**Petunjuk**: Hapus teks dalam \[...\] dan huruf miring setelah diisi. Worksheet terkait: WS03, WS04

1. ## **1\. Profil Organisasi / Unit Usaha**

* **Nama unit usaha**: Laundry Que.

* **Jenis usaha / layanan**: Self-service laundry.

* **Lokasi**: Jl. Ki Ageng Pemanahan, Kragilan, Tamanan, Kec. Banguntapan, Kabupaten Bantul, Daerah Istimewa Yogyakarta 55191 / 450 meter dari kampus 4 Universitas Ahmad Dahlan.

* **Deskripsi singkat operasional**: \[apa yang dilakukan, siapa pengguna, kapan beroperasi\] 

\[Laundry Que merupakan layanan *self-service* laundry yang beroperasi selama 24 jam dengan sistem pembagian, 3 shift kerja per 1 karyawan selama 8 jam. Penanganan operasional usaha dilakukan secara mandiri oleh 1 karyawan mulai dari menangani kebersihan tempat usaha, menangani bagian kasir (pendaftaran hingga transaksi pembayaran pelanggan), pengawasan mesin, pemantauan stok bahan baku, hingga rekapitulasi keuangan.\]

* **Narahubung / pemilik**: Ratih Oktafiani, Staf, 08163037338

## **2\. Deskripsi Masalah Utama**

* **Masalah utama**: \[Keterbatasan efisiensi operasional karena, pada proses pendaftaran pelanggan masih melalui lembar pendaftaran manual sebelum diinput ke aplikasi, yang mengakibatkan adanya potensi *human error* saat pencatatan rekapitulasi keuangan kasir saat jam sibuk yang mengharuskan staf untuk rekap ganda (secara manual, dan aplikasi). Pengaduan kerusakan mesin cuci/pengering masih manual melalui WhatsApp. Lalu, koordinasi pemesanan stok bahan baku (sabun, pewangi, gas elpiji) yang masih dilakukan secara manual melalui *chat* *WhatsApp* ke admin pusat.\]

* **Pihak yang terdampak**: \[Staf: Menghadapi beban kerja yang beresiko, karena melayani operasional secara sendiri selama 8 jam/shift, seperti menangani antrean yang panjang saat jam sibuk, rekapitulasi keuangan ganda, dan koordinasi stok bahan baku secara manual.

Pelanggan: Mengalami potensi keterlambatan layanan saat jam sibuk, karena proses input data awal pelanggan yang bertahap.\]

* **Frekuensi / keparahan**: \[Terjadi selisih rekapitulasi keuangan terjadi saat jam operasional sibuk (terutama saat akhir pekan) sebanyak 1 kali dalam sebulan, yang memakan waktu 15-20 menit saat pencocokan manual antara rekapan lembar manual dengan rekapan pada sistem aplikasi. Kerusakan mesin terjadi 2 kali/bulan, dan setelah mesin rusak tidak langsung segera ditangani, melainkan menunggu koordinasi dari admin/teknisi mesin. Untuk pengajuan stok bahan baku 1 kali/hari namun masih melalui WhatsApp dan setelah di koordinasi ke admin tidak dibalas, hanya dibaca saja. Seberapa mengganggu nya permasalahan tersebut, mitra menjelaskan bahwa tidak terlalu mengganggu karena sudah terbiasa mengelolanya.\]

## **3\. Batasan Sistem (Scope)**

* **Diselesaikan dalam proyek ini**: \[fitur/cakupan yang dikerjakan\]

Digitalisasi pendaftaran pelanggan

Manajemen pengajuan stok bahan baku ke admin pusat

Pelaporan mesin rusak

* **Tidak diselesaikan (dan alasan)**: \[di luar cakupan \+ alasan\]

1. Perbaikan fisik pada mesin cuci atau pengering

   Karena di luar kapasitas kami, dan harus ditangani langsung oleh ahli teknisi mesin.

2. Kendala jaringan internet

   Karena disebabkan oleh pihak ketiga (jaringan error atau sedang tidak bagus).

3. Manajemen penjadwalan shift

   Karena sudah SOP dari pemilik usaha bahwa per shift dikerjakan oleh 1 orang karyawan selama 8 jam.

* **Asumsi yang dipakai**: \[asumsi kunci\]

Aplikasi yang akan dikembangkan berbasis sistem sederhana yang bisa diakses melalui *handphone* staf di tempat usaha.

## **4\. Data Kuantitatif Pendukung**

| Indikator | Nilai/Baseline | Sumber Data | Tanggal |
| :---- | :---- | :---- | :---- |
| \[waktu layanan rata-rata\] | \[1 menit / pelanggan\] | \[observasi\] | \[06/11\] |
| \[jumlah transaksi per hari\] | \[500 – 900 / hari\] | \[wawancara\] | \[06/11\] |
| \[waktu rekapitulasi keuangan\] | \[15 – 20 menit / shift\] | \[wawancara\] | \[23/10\] |
| \[waktu durasi staf per shift\] | \[1 orang / 8 jam\] | \[wawancara\] | \[23/10\] |
| \[waktu pencucian\] | \[26 menit\] | \[observasi dan wawancara\] | \[06/11\] |
| \[waktu pengeringan\] | \[45 menit\] | \[observasi dan wawancara\] | \[06/11\] |
| \[kapasitas beban mesin\] | \[9 kilogram / 1 tabung\] | \[wawancara\] | \[06/11\] |
| \[tarif layanan\] | \[Rp 10.000,00 / 1 tabung\] | \[wawancara\] | \[06/11\] |
| \[kerusakan mesin\] | \[2 kali / bulan\] | \[observasi dan wawancara\] | \[06/11\] |
| \[pemeliharaan mesin\] | \[mesin pengering \= 1 kali / minggu, mesin cuci \= 2 kali / minggu\] | \[observasi dan wawancara\] | \[06/11\] |
| \[pengisian ulang bahan baku\] | \[1 kali / hari\] | \[wawancara\] | \[06/11\] |

2. ## **5\. Pernyataan Kebutuhan Awal (ringkasan ke D2)**

* Kebutuhan inti yang akan dijawab prototipe: \[3–5 butir\]

* Staf berharap terkait kebutuhan stok bahan baku sabun, pewangi, dan gas elpiji supaya tidak chat manual melalui *WhatsApp,* karena akibat dari hal tersebut staf bolak-balik membuka antara *WhatsApp* dan aplikasi. Harapannya, pengajuan stok bahan baku bisa langsung diajukan melalui sistem supaya tidak usah lagi chat via *WhatsApp*, melainkan langsung klik saja di dalam sistem bahan baku apa saja yang ingin direstock.

* Pelaporan kerusakan mesin bisa langsung diadukan melalui sistem supaya admin pusat segera merespons dan langsung mendatangkan ahli teknisi untuk segera memperbaiki mesin yang rusak supaya tidak memperhambat proses laundry yang menyebabkan antre.

* Terkait pendaftaran pelanggan diharapkan bisa langsung tersistem di aplikasi supaya menghindari selisih saat rekapitulasi.

## **6\. Daftar Rujukan / Bukti**

* \[Observasi lapangan tanggal 23 Oktober 2026\]

* \[Wawancara pemilik tanggal 24 Oktober, dan 6 November 2026\]

* \[Dokumen pendukung lainnya\]

**Status**: ⬜ Draf → ⬜ Review Tim → ⬜ Validasi Pemilik → ⬜ Final (Gate 1\)

