# Website Resmi SMAN 1 Rantau Kopar

Portal web resmi profil sekolah **SMAN 1 Rantau Kopar**, Kabupaten Rokan Hilir, Provinsi Riau. Seluruh data sekolah, sejarah, statistik siswa, dan data dewan guru/PTK diambil secara akurat dan terverifikasi dari portal resmi **Kementerian Pendidikan Dasar dan Menengah RI (Kemendikdasmen)** melalui endpoint profil sekolah:
`https://sekolah.data.kemendikdasmen.go.id/profil-sekolah/B58C21A2-F5A2-48A6-9AE3-8255FAC093CC`

---

## Ringkasan Data Sekolah

| Parameter | Data Resmi |
|---|---|
| **Nama Sekolah** | SMAN 1 RANTAU KOPAR |
| **NPSN** | 10493782 |
| **Status / Bentuk** | Negeri / Sekolah Menengah Atas (SMA) |
| **Akreditasi** | Peringkat B (Nilai 88 - SK: 1857/BAN-SM/SK/2022 s.d 2027) |
| **Kurikulum** | Kurikulum SMA Merdeka |
| **SK Izin Operasional** | 421/TU/2004/2787 (TMT: 11 November 2004) |
| **Kepala Sekolah** | Zulkifli Za, S.Pd (Gol. IV/a, ASN Pengabdian >24 Tahun) |
| **Total Siswa Aktif** | **254 Siswa** (128 Laki-Laki, 126 Perempuan) |
| **Jumlah Rombel** | 9 Rombongan Belajar (Kelas 10: 95 siswa, Kelas 11: 82 siswa, Kelas 12: 77 siswa) |
| **Total Guru & PTK** | **23 PTK** (17 Guru, 6 Tenaga Kependidikan) |
| **Kualifikasi Guru** | 94.12% Bersertifikasi Pendidik (16 Guru), 88.24% ASN, 4 Magister (S2), 13 Sarjana (S1) |
| **Luas Lahan Milik** | 19.849 m² (Hampir 2 Hektar) |
| **Daya Listrik & Net** | PLN 10.600 VA • Jaringan Broadband & Seluler |
| **Fasilitas Utama** | 9 Ruang Kelas (Kondisi Baik), 1 Lab Komputer, 2 Lab IPA, 1 Lab Biologi, 1 Lab Kimia, 1 Perpustakaan |
| **Alamat** | Jl. Lintas Sekapas - Rantau Kopar, RT 01/RW 01, Dusun III Rantau Panjang, Kec. Rantau Kopar, Kab. Rokan Hilir, Prov. Riau (Kode Pos 28981) |
| **Kontak Resmi** | Telp: 081371167009 • Email: smansa.kopar@gmail.com |

---

## Struktur File Proyek

```
c:\testing xampp\
├── index.html              # Halaman web utama (modern, responsif, Tailwind CSS & Chart.js)
├── index.php               # Entry point PHP untuk XAMPP Apache
├── README.md               # Dokumentasi lengkap
├── assets/
│   ├── css/
│   │   └── style.css       # Custom styling, tema, animasi dan glassmorphism
│   └── js/
│       └── main.js         # Interaktivitas (Chart.js, counter animasi, filter & pencarian guru)
└── data/
    └── school-data.json    # Data JSON master lengkap hasil ekstraksi Kemendikdasmen
```

---

## Cara Menjalankan Website

### 1. Membuka Langsung di Web Browser
Anda dapat langsung membuka file `index.html` dengan mengklik dua kali (double click) atau klik kanan > *Open with* browser (Google Chrome, Microsoft Edge, Firefox, dll).

### 2. Menjalankan di XAMPP / Web Server Lokal
1. Pastikan folder ini berada di dalam direktori `htdocs` XAMPP (misal: `C:\xampp\htdocs\sman1rantaukopar` atau direktori web server Anda).
2. Jalankan Apache di panel kontrol XAMPP.
3. Buka browser dan akses: `http://localhost/testing xampp/` atau `http://localhost/sman1rantaukopar/`.

---

## Fitur Unggulan Website

1. **Responsif & Modern**: Tampilan bersih, profesional, dan kompatibel untuk perangkat desktop, tablet, maupun smartphone.
2. **Visualisasi Data Interaktif (Chart.js)**:
   - Diagram batang distribusi siswa per kelas (Kelas 10, 11, 12) per jenis kelamin.
   - Diagram donat rasio gender peserta didik.
   - Diagram pie status kepegawaian guru (PNS, PPPK, Honorer).
3. **Filter & Live Search Dewan Guru**: Pengunjung dapat mencari nama guru atau menyaring berdasarkan bidang keahlian (Pimpinan, Guru MIPA/Sains, Guru Bahasa & Sosial, Tenaga Kependidikan).
4. **Peta Interaktif Google Maps**: Titik koordinat sekolah langsung terhubung dengan lokasi presisi di Rantau Kopar.
5. **Formulir Kontak Online**: Memudahkan calon siswa atau wali murid mengirim pertanyaan ke pihak sekolah.
