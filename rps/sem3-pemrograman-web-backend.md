# Bahan RPS: Pemrograman Web Backend

**Kode** OBE0502303 · **Semester** 3 · **4 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-8** (Keterampilan Khusus) Mampu merancang, mengembangkan, menguji, dan men-deploy aplikasi web full-stack modern dengan praktik clean code, secure coding, dan deployment ke cloud.
- **CPL-3** (Pengetahuan) Menguasai konsep teoretis pemrograman, rekayasa perangkat lunak, basis data, jaringan, dan keamanan informasi secara umum.

**Prasyarat**: OBE0502301 Basis Data, OBE0502204 Pemrograman Berorientasi Objek.

**Catatan penempatan**: mata kuliah dengan bobot praktik terbesar di semester tiga.
Keamanan tidak ditunda sampai mata kuliah Keamanan Sistem Informasi di semester empat:
autentikasi dan penanganan masukan diajarkan di sini, sebab kebiasaan buruk yang terbentuk
sekarang akan terbawa ke proyek akhir.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Membangun layanan web yang menyediakan antarmuka pemrograman sesuai kaidah yang lazim | CPL-8 |
| CPMK-2 | Menghubungkan layanan dengan basis data beserta pengelolaan skema dan migrasinya | CPL-8, CPL-3 |
| CPMK-3 | Menerapkan autentikasi, otorisasi, dan penanganan masukan yang aman | CPL-8 |
| CPMK-4 | Menerbitkan layanan beserta pencatatan dan pemeriksaan kesehatannya | CPL-8 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Membangun layanan yang menanggapi permintaan dengan kode status dan bentuk balasan yang tepat | 1-2 | 10 | Protokol HTTP, kode status, bentuk balasan, penanganan rute | Kuliah, Praktikum | Praktik terbimbing | Membangun layanan pertama beserta beberapa rute | Membaca dokumentasi kerangka kerja | Kerangka kerja pilihan prodi, alat uji permintaan | Uji permintaan bersama di kelas | Layanan berjalan beserta catatan ujinya | PRAKTIK |
| 1.2 | Merancang antarmuka pemrograman yang ajek penamaan dan perilakunya | 3 | 10 | Perancangan sumber daya, penamaan, penomoran versi, dokumentasi | Kuliah | Case Study | Merancang antarmuka untuk satu kasus UMKM | Membaca panduan perancangan antarmuka | Alat dokumentasi antarmuka | Tinjauan rancangan antar kelompok | Dokumen rancangan antarmuka | TUGAS |
| 2.1 | Menghubungkan layanan dengan basis data beserta migrasi skemanya | 4-5 | 10 | Sambungan basis data, pemetaan objek, migrasi skema | Praktikum | Praktik terbimbing | Menyambungkan layanan ke basis data beserta migrasi | Latihan mandiri | Basis data, perkakas migrasi | Pemeriksaan migrasi saat praktikum | Layanan bersambung beserta berkas migrasinya | PRAKTIK |
| 2.2 | Menangani kesalahan layanan sehingga pemanggil menerima pesan yang berguna, bukan jejak galat | 6-7 | 10 | Penanganan kesalahan terpusat, pesan untuk pemanggil, pencatatan | Praktikum | Problem-Based Learning | Menambahkan penanganan kesalahan terpusat | Membaca contoh penanganan kesalahan | Kerangka kerja | Uji coba merusak layanan teman | Kode beserta contoh balasan kesalahannya | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan sebagai pembangunan layanan di tempat | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 3.1 | Menerapkan autentikasi dan membedakan hak akses antar peran pengguna | 9-10 | 10 | Autentikasi, sesi dan token, otorisasi berbasis peran | Kuliah, Praktikum | Case Study | Menambahkan autentikasi dan pembatasan peran | Membaca panduan autentikasi | Kerangka kerja, pustaka autentikasi | Uji coba menembus batas peran di kelas | Layanan berautentikasi beserta ujinya | PRAKTIK |
| 3.2 | Menutup celah penyisipan dan kebocoran data pada masukan maupun balasan layanan | 11-12 | 10 | Pemeriksaan masukan, kueri berparameter, penyaringan bidang balasan, rahasia di berkas lingkungan | Kuliah, Praktikum | Problem-Based Learning | Memeriksa dan memperbaiki layanan sendiri terhadap daftar periksa keamanan | Membaca sepuluh risiko teratas aplikasi web | Alat uji keamanan sederhana | Saling menguji layanan antar kelompok | Laporan pemeriksaan beserta perbaikannya | TUGAS |
| 2.3 | Menulis pengujian yang membuktikan rute layanan berperilaku benar | 13 | 10 | Pengujian rute, data uji, pemisahan basis data uji | Praktikum | Praktik terbimbing | Menulis pengujian untuk rute yang sudah dibangun | Membaca contoh berkas uji | Kerangka uji | Uji dijalankan bersama | Berkas uji beserta hasil jalannya | TUGAS |
| 4.1 | Menerbitkan layanan beserta pencatatan dan pemeriksaan kesehatannya | 14-15 | 15 | Penerbitan, berkas lingkungan, pencatatan, titik periksa kesehatan | Praktikum, Seminar | Project-Based Learning | Menerbitkan layanan proyek akhir | Mempelajari dokumentasi layanan hos | Layanan hos, repositori kode | Tinjauan kemajuan mingguan | Layanan terbit beserta penyajiannya | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat layanan terbit pekan 14 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.1 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- Dokumentasi resmi kerangka kerja backend yang dipakai prodi.
- OWASP. *OWASP Top Ten* (edisi yang berlaku) dan *Cheat Sheet Series*.

**Pendukung**

- Newman, S. (2021). *Building Microservices* (2nd ed.). O'Reilly Media. Dipakai sebagai bacaan lanjutan, bukan pola wajib untuk proyek semester ini.
- Nygard, M. T. (2018). *Release It!* (2nd ed.). Pragmatic Bookshelf.

## Sarana yang diperlukan

Lab dengan lingkungan pemrograman, basis data, alat uji permintaan, repositori kode, dan
akun layanan hos gratis. Sediakan pula satu layanan sengaja rentan untuk latihan pekan 11
sampai 12, supaya mahasiswa tidak menguji milik pihak lain.
