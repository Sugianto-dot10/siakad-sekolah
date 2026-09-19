# Sistem Informasi Akademik (SIAKAD) - SMK Mulia Buana

Aplikasi Sistem Informasi Akademik berbasis web yang dikembangkan khusus untuk mengelola administrasi pendidikan, manajemen ujian, dan rekapitulasi nilai Kurikulum Merdeka di **SMK Mulia Buana**. Dibangun menggunakan *framework* Laravel.

## 🚀 Fitur Utama

- **Manajemen Data Induk:** Pengelolaan data Siswa, Guru, Kelas, dan Mata Pelajaran (Umum & Kejuruan).
- **Set Pembelajaran:** Pemetaan otomatis jadwal dan guru pengampu berdasarkan kelas.
- **Portal Ujian Terpadu:** 
  - Penjadwalan ujian otomatis dengan filter dinamis.
  - Integrasi dengan Google Form untuk pelaksanaan ujian.
  - Pembuatan Kode Unik/Kartu Ujian bagi siswa yang telah menyelesaikan administrasi.
- **Manajemen Nilai Kurikulum Merdeka:** 
  - Input nilai dinamis berdasarkan jenis ujian (Sumatif Tengah Semester, Akhir Semester, Akhir Tahun).
  - Kalkulasi otomatis Nilai Murni dan Rata-rata Lingkup Materi (TP1, TP2, TP3).
- **Cetak Rapor Otomatis:** Pembuatan dokumen Laporan Hasil Belajar Siswa yang siap cetak (PDF/Print) lengkap dengan capaian kompetensi.
- **Multi-Role Access:** Hak akses khusus untuk Admin, Guru/Wali Kelas, dan Siswa.

## 🛠️ Teknologi yang Digunakan

- **Backend:** Laravel (PHP)
- **Database:** MySQL
- **Frontend:** HTML, CSS (Bootstrap 5), JavaScript (jQuery, AJAX)
- **Library Tambahan:** DataTables

## ⚙️ Panduan Instalasi (Untuk Pengembangan Lokal)

Ikuti langkah-langkah berikut untuk menjalankan aplikasi ini di komputer lokal (localhost):

1. **Clone repository ini**
   ```bash
   git clone [https://github.com/Sugianto-dot10/siakad-sekolah.git](https://github.com/Sugianto-dot10/siakad-sekolah.git)
