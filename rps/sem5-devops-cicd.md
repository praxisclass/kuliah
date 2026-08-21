# Bahan RPS: DevOps dan CI/CD

**Kode** OBE0502404 · **Semester** 5 · **2 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-8** (Keterampilan Khusus) Mampu merancang, mengembangkan, menguji, dan men-deploy aplikasi web full-stack modern dengan praktik clean code, secure coding, dan deployment ke cloud.
- **CPL-12** (Keterampilan Khusus) Mampu menganalisis kebutuhan, merancang arsitektur solusi end-to-end, dan mengelola proyek digital UMKM/pariwisata dengan metode Agile, dari konsep hingga deployment.
- **CPL-7** (Keterampilan Umum) Mampu bekerja sama dalam tim Agile, mengelola pembelajaran mandiri sepanjang hayat, dan bertanggung jawab atas hasil kerja kelompok.

**Prasyarat**: OBE0502206 Sistem Operasi, OBE0502303 Pemrograman Web Backend, OBE0502402 Cloud Computing Fundamental.

**Catatan penempatan**: 2 SKS di semester lima, berdampingan dengan persiapan magang dan
proyek akhir. Pakai **aplikasi yang sudah mahasiswa bangun di semester sebelumnya** sebagai
bahan praktik. Membangun aplikasi baru di sini akan menghabiskan seluruh waktu dan
mata kuliahnya kehilangan maksudnya.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Menjelaskan alur kerja DevOps dan alasan otomasi dibanding penerbitan manual | CPL-12 |
| CPMK-2 | Membangun alur otomasi yang menguji dan membangun perangkat lunak pada tiap perubahan | CPL-8, CPL-7 |
| CPMK-3 | Mengotomasi penerbitan ke lingkungan uji dan produksi beserta cara mengembalikannya | CPL-8 |
| CPMK-4 | Memantau aplikasi yang berjalan dan menanggapi gangguan berdasarkan data | CPL-12 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Menjelaskan hambatan pada penerbitan manual dan menunjukkan bagian yang layak diotomasi | 1-2 | 10 | Alur kerja DevOps, hambatan penerbitan manual, ukuran keberhasilan | Kuliah | Case Study | Memetakan langkah penerbitan aplikasi sendiri saat ini | Membaca bab pengantar DevOps | Lembar kerja pemetaan | Diskusi pemetaan di kelas | Peta langkah beserta usulan otomasinya | TUGAS |
| 2.1 | Menyiapkan repositori dengan alur cabang yang disepakati tim | 3 | 10 | Alur cabang, aturan penggabungan, perlindungan cabang utama | Praktikum | Praktik terbimbing | Menyiapkan aturan cabang pada repositori tim | Membaca panduan alur cabang | Repositori bersama | Pemeriksaan aturan cabang | Konfigurasi repositori beserta aturannya | PRAKTIK |
| 2.2 | Membangun alur otomasi yang menjalankan pengujian pada tiap perubahan | 4-5 | 10 | Integrasi berkelanjutan, berkas alur kerja, jalur cepat dan lambat | Praktikum | Praktik terbimbing | Membuat alur otomasi pengujian untuk aplikasi sendiri | Membaca dokumentasi layanan otomasi | Layanan otomasi, repositori | Alur dijalankan bersama di kelas | Alur otomasi berjalan beserta buktinya | PRAKTIK |
| 2.3 | Membangun wadah aplikasi yang dapat dijalankan sama di mesin mana pun | 6-7 | 10 | Berkas wadah, lapisan, ukuran wadah, berkas lingkungan | Praktikum | Problem-Based Learning | Membungkus aplikasi sendiri menjadi wadah | Membaca dokumentasi wadah | Perkakas wadah | Uji jalan wadah di mesin teman | Wadah berjalan beserta berkasnya | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan sebagai kerja otomasi di tempat | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 3.1 | Mengotomasi penerbitan ke lingkungan uji beserta pemisahannya dari produksi | 9-10 | 10 | Lingkungan uji dan produksi, rahasia per lingkungan, penerbitan otomatis | Praktikum | Praktik terbimbing | Menyiapkan penerbitan otomatis ke lingkungan uji | Latihan mandiri | Layanan otomasi, penyedia cloud | Pemeriksaan hasil terbit | Penerbitan otomatis yang berjalan | PRAKTIK |
| 3.2 | Menyiapkan cara mengembalikan penerbitan yang gagal ke keadaan sebelumnya | 11 | 10 | Penomoran versi rilis, pengembalian, migrasi basis data yang aman | Praktikum | Case Study | Menguji pengembalian rilis pada aplikasi sendiri | Membaca contoh prosedur pengembalian | Layanan otomasi | Uji pengembalian dilakukan di kelas | Bukti pengembalian berhasil beserta catatannya | PRAKTIK |
| 4.1 | Memantau aplikasi yang berjalan lewat pencatatan dan pemeriksaan kesehatan | 12-13 | 10 | Pencatatan terstruktur, titik periksa kesehatan, peringatan | Praktikum | Problem-Based Learning | Menambahkan pencatatan dan titik periksa kesehatan | Membaca panduan pemantauan | Layanan pemantauan | Uji coba mematikan layanan | Aplikasi terpantau beserta bukti peringatannya | PRAKTIK |
| 4.2 | Menanggapi satu gangguan buatan dari deteksi sampai pemulihan, lalu menuliskan pelajarannya | 14-15 | 15 | Tanggap gangguan, catatan kejadian tanpa mencari kambing hitam | Praktikum, Seminar | Project-Based Learning | Menjalankan simulasi gangguan dan menyusun catatan kejadian | Membaca contoh catatan kejadian | Layanan pemantauan, dokumen | Simulasi dinilai langsung saat berjalan | Catatan kejadian beserta penyajiannya | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat simulasi gangguan pekan 14 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.2 | — |

Total bobot: 100.

---

## Catatan tentang penilaian CPL-7 di mata kuliah ini

Kerja sama tim di sini terbukti dari **riwayat repositori dan alur otomasi**, bukan dari
kesan. Yang dibaca: siapa membuat permintaan penggabungan, siapa meninjaunya, dan apakah
tinjauan itu menghasilkan perubahan. Tim yang seluruh anggotanya menyetujui apa pun tanpa
catatan sebenarnya belum meninjau.

## Referensi

**Utama**

- Kim, G., Humble, J., Debois, P., & Willis, J. (2021). *The DevOps Handbook* (2nd ed.). IT Revolution Press.
- Dokumentasi resmi layanan otomasi dan perkakas wadah yang dipakai prodi.

**Pendukung**

- Forsgren, N., Humble, J., & Kim, G. (2018). *Accelerate*. IT Revolution Press. Untuk bagian ukuran keberhasilan penerbitan.
- Beyer, B., dkk. (2016). *Site Reliability Engineering*. O'Reilly Media. Tersedia bebas daring, dipakai untuk bagian pemantauan dan tanggap gangguan.

## Sarana yang diperlukan

Repositori bersama dengan layanan otomasi, perkakas wadah, akun penyedia cloud lapisan
gratis, dan aplikasi hasil semester sebelumnya sebagai bahan. Sediakan pula satu lingkungan
yang boleh dirusak untuk simulasi gangguan pekan 14 sampai 15.
