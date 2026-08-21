# Bahan RPS: Pemrograman Web Frontend

**Kode** OBE0502302 · **Semester** 3 · **3 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-8** (Keterampilan Khusus) Mampu merancang, mengembangkan, menguji, dan men-deploy aplikasi web full-stack modern dengan praktik clean code, secure coding, dan deployment ke cloud.

**Prasyarat**: OBE0502204 Pemrograman Berorientasi Objek.

**Catatan penempatan**: berjalan sejajar dengan Pemrograman Web Backend dan Desain
Antarmuka. Sepakati satu kasus bersama antar ketiga mata kuliah itu bila memungkinkan,
sehingga mahasiswa membangun satu produk, bukan tiga tugas terpisah yang tak pernah
bertemu.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Membangun struktur dan tata letak halaman web yang benar secara semantik dan responsif | CPL-8 |
| CPMK-2 | Membangun antarmuka bergerak memakai pustaka komponen beserta pengelolaan keadaannya | CPL-8 |
| CPMK-3 | Menghubungkan antarmuka dengan layanan data dan menangani keadaan memuat serta gagal | CPL-8 |
| CPMK-4 | Menerbitkan aplikasi frontend beserta pemeriksaan mutu dasar sebelum diterbitkan | CPL-8 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Menyusun halaman memakai penanda semantik yang benar dan lolos pemeriksaan dasar aksesibilitas | 1-2 | 10 | Struktur dokumen, penanda semantik, teks alternatif, urutan fokus | Kuliah, Praktikum | Praktik terbimbing | Membangun halaman profil usaha yang semantik | Membaca panduan penanda semantik | Editor kode, pemeriksa aksesibilitas | Pemeriksaan otomatis di kelas | Halaman beserta laporan pemeriksaan | PRAKTIK |
| 1.2 | Menata halaman agar terbaca di layar ponsel maupun layar lebar | 3-4 | 10 | Tata letak lentur, kisi, titik henti, satuan relatif | Praktikum | Problem-Based Learning | Menata ulang halaman pekan lalu agar responsif | Latihan mandiri | Editor kode, alat uji lebar layar | Uji silang di beberapa ukuran layar | Halaman responsif beserta tangkapan layarnya | PRAKTIK |
| 2.1 | Memecah antarmuka menjadi komponen yang dapat dipakai ulang | 5-6 | 10 | Komponen, properti, penyusunan komponen | Kuliah, Praktikum | Praktik terbimbing | Memecah halaman menjadi komponen | Membaca dokumentasi pustaka | Pustaka komponen pilihan prodi | Tinjauan kode teman | Kode berkomponen | PRAKTIK |
| 2.2 | Mengelola keadaan antarmuka sehingga tampilan selalu sesuai dengan datanya | 7 | 10 | Keadaan komponen, aliran data satu arah, kesalahan lazim | Praktikum | Problem-Based Learning | Membangun antarmuka bergerak sederhana | Latihan mandiri | Pustaka komponen | Kuis pendek | Antarmuka bergerak yang berjalan | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan sebagai pembangunan antarmuka di tempat | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 3.1 | Mengambil data dari layanan dan menampilkannya, termasuk saat sedang memuat dan saat gagal | 9-10 | 10 | Permintaan data, keadaan memuat, keadaan gagal, keadaan kosong | Praktikum | Case Study | Menyambungkan antarmuka ke layanan data contoh | Membaca dokumentasi layanan | Layanan data contoh | Uji coba mematikan jaringan di kelas | Antarmuka bersambung beserta tiga keadaannya | PRAKTIK |
| 3.2 | Menangani masukan pengguna beserta pemeriksaan kesalahan yang menjelaskan cara memperbaikinya | 11-12 | 10 | Formulir, pemeriksaan masukan, pesan kesalahan yang berguna | Praktikum | Problem-Based Learning | Membangun formulir bersyarat | Latihan mandiri | Editor kode | Uji coba mengisi salah oleh teman | Formulir beserta pesan kesalahannya | PRAKTIK |
| 4.1 | Memeriksa mutu dasar aplikasi sebelum diterbitkan | 13 | 10 | Pemeriksaan kinerja, aksesibilitas, dan tautan rusak | Praktikum | Praktik terbimbing | Menjalankan pemeriksaan dan memperbaiki temuan | Membaca panduan pemeriksaan mutu | Alat pemeriksa mutu halaman | Pembahasan temuan bersama | Laporan sebelum dan sesudah perbaikan | TUGAS |
| 4.2 | Menerbitkan aplikasi frontend ke layanan hos dan menyajikannya | 14-15 | 15 | Penerbitan, berkas lingkungan, domain dan sertifikat dasar | Praktikum, Seminar | Project-Based Learning | Menerbitkan proyek akhir dan menyiapkan sajian | Mempelajari dokumentasi layanan hos | Layanan hos, repositori kode | Tinjauan kemajuan mingguan | Aplikasi terbit beserta penyajiannya | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat proyek terbit pekan 14 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.2 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- MDN Web Docs. *HTML, CSS, and JavaScript references*. Mozilla. Dipakai sebagai rujukan utama karena selalu mutakhir.
- Dokumentasi resmi pustaka komponen yang dipakai prodi.

**Pendukung**

- Frain, B. (2022). *Responsive Web Design with HTML5 and CSS* (4th ed.). Packt Publishing.
- W3C. *Web Content Accessibility Guidelines* (versi yang berlaku).

## Sarana yang diperlukan

Lab komputer dengan editor kode, peramban beserta alat pengembangnya, akses internet, dan
akun layanan hos gratis untuk penerbitan.
