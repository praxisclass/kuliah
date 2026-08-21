# Bahan RPS: Sistem Operasi

**Kode** OBE0502206 · **Semester** 2 · **3 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-3** (Pengetahuan) Menguasai konsep teoretis pemrograman, rekayasa perangkat lunak, basis data, jaringan, dan keamanan informasi secara umum.

**Prasyarat**: OBE0502201 Pengantar Teknologi Informasi.

**Catatan penempatan**: satu-satunya CPL yang dipikul adalah CPL pengetahuan, tetapi untuk
vokasi buktinya tetap harus berupa perbuatan. Karena itu asesmen di bawah bersandar pada
kerja di terminal dan pembacaan keadaan sistem yang sedang berjalan, bukan pada hafalan
istilah. Mata kuliah ini juga menyiapkan mahasiswa untuk DevOps di semester lima.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Menjelaskan peran sistem operasi sebagai pengelola sumber daya beserta cara kerjanya | CPL-3 |
| CPMK-2 | Mengelola proses, berkas, dan pengguna pada sistem operasi bertipe Unix lewat baris perintah | CPL-3 |
| CPMK-3 | Membaca keadaan sumber daya sistem yang sedang berjalan dan mengenali gejala kelebihan beban | CPL-3 |
| CPMK-4 | Menyiapkan lingkungan kerja terisolasi untuk menjalankan aplikasi | CPL-3 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Menjelaskan pembagian tugas antara perangkat keras, kernel, dan aplikasi pada satu perintah yang dijalankannya | 1-2 | 10 | Peran sistem operasi, kernel dan ruang pengguna, panggilan sistem | Kuliah, Praktikum | Case Study | Menelusuri apa yang terjadi saat satu perintah dijalankan | Membaca bab pengantar | Terminal Linux | Tanya jawab di kelas | Laporan penelusuran perintah | TUGAS |
| 2.1 | Mengelola berkas, hak akses, dan pengguna lewat baris perintah | 3-4 | 15 | Sistem berkas, hak akses, pengguna dan grup | Praktikum | Praktik terbimbing | Menata struktur direktori dan hak akses satu kasus | Latihan mandiri di mesin virtual | Terminal Linux, mesin virtual | Pemeriksaan hasil kerja saat praktikum | Hasil kerja di mesin beserta catatan perintah | PRAKTIK |
| 2.2 | Menjalankan, memantau, dan menghentikan proses beserta memahami keadaannya | 5-6 | 15 | Proses, keadaan proses, penjadwalan, sinyal | Kuliah, Praktikum | Problem-Based Learning | Menjalankan beban buatan lalu mengamati perilakunya | Membaca bab proses | Terminal, alat pantau proses | Kuis pendek | Laporan pengamatan proses | PRAKTIK |
| 3.1 | Membaca pemakaian memori, prosesor, dan cakram serta mengenali gejala kelebihan beban | 7 | 10 | Memori, ruang tukar, beban prosesor, kepenuhan cakram | Praktikum | Case Study | Mendiagnosis mesin yang sengaja dibuat lambat | Latihan mandiri | Alat pantau sumber daya | Umpan balik dosen atas diagnosis | Laporan diagnosis beserta buktinya | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan di terminal | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 2.3 | Menyusun skrip sederhana untuk pekerjaan berulang | 9-10 | 10 | Skrip shell, peubah, perulangan, penjadwalan tugas | Praktikum | Praktik terbimbing | Membuat skrip cadangan berkas terjadwal | Latihan mandiri | Terminal, penjadwal tugas | Tinjauan skrip antar teman | Skrip beserta bukti jalannya | PRAKTIK |
| 4.1 | Menjalankan aplikasi di dalam lingkungan terisolasi beserta alasan pemakaiannya | 11-12 | 10 | Isolasi proses, wadah aplikasi, berbagi sumber daya | Kuliah, Praktikum | Problem-Based Learning | Menjalankan satu aplikasi di dalam wadah | Membaca dokumentasi wadah | Perkakas wadah | Kuis pendek | Aplikasi berjalan di wadah beserta catatannya | PRAKTIK |
| 3.2 | Menyusun laporan pemeriksaan kesehatan satu sistem beserta usulan perbaikannya | 13-15 | 15 | Pemeriksaan menyeluruh, pencatatan, usulan perbaikan | Praktikum, Seminar | Project-Based Learning | Memeriksa satu mesin nyata dan menyusun laporan | Mempelajari contoh laporan pemeriksaan | Terminal, pengolah kata | Tinjauan kemajuan mingguan | Laporan pemeriksaan beserta penyajiannya | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat laporan pemeriksaan pekan 13 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 3.2 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- Silberschatz, A., Galvin, P. B., & Gagne, G. (2018). *Operating System Concepts* (10th ed.). Wiley.
- Shotts, W. (2019). *The Linux Command Line* (2nd ed.). No Starch Press.

**Pendukung**

- Dokumentasi resmi distribusi Linux yang dipakai di lab.
- Halaman manual sistem (`man`) sebagai rujukan utama saat praktikum.

## Sarana yang diperlukan

Lab dengan mesin virtual per mahasiswa yang boleh dirusak dan dibangun ulang, akses
terminal, dan perkakas wadah aplikasi. Mesin virtual penting: mahasiswa perlu berani salah
tanpa merusak komputer lab.
