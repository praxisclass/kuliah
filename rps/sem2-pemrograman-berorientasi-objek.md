# Bahan RPS: Pemrograman Berorientasi Objek

**Kode** OBE0502204 · **Semester** 2 · **4 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-3** (Pengetahuan) Menguasai konsep teoretis pemrograman, rekayasa perangkat lunak, basis data, jaringan, dan keamanan informasi secara umum.
- **CPL-5** (Keterampilan Umum) Mampu menyelesaikan pekerjaan TI berlingkup luas dengan menganalisis data, memilih metode tepat, dan menunjukkan kinerja bermutu serta terukur.
- **CPL-8** (Keterampilan Khusus) Mampu merancang, mengembangkan, menguji, dan men-deploy aplikasi web full-stack modern dengan praktik clean code, secure coding, dan deployment ke cloud.

**Prasyarat**: OBE0502202 Algoritma dan Pemrograman Dasar.

**Catatan penempatan**: memikul tiga CPL, termasuk CPL-8 yang bermuara pada aplikasi web.
Karena itu contoh kasusnya sebaiknya sudah berbau aplikasi nyata (entitas, layanan,
penyimpanan), bukan contoh hewan dan kendaraan yang tidak pernah mereka temui lagi.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Memodelkan masalah menjadi kelas dan objek beserta tanggung jawab masing-masing | CPL-3 |
| CPMK-2 | Membangun program berorientasi objek yang memanfaatkan pewarisan, enkapsulasi, dan polimorfisme secara tepat guna | CPL-3, CPL-5 |
| CPMK-3 | Menerapkan penanganan galat dan pengujian unit sehingga program dapat dipercaya | CPL-5 |
| CPMK-4 | Membangun satu aplikasi berlapis sederhana yang memisahkan logika, data, dan antarmuka | CPL-8 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Mengenali entitas pada satu kasus nyata dan menyatakannya sebagai kelas beserta atribut dan perilakunya | 1-2 | 10 | Konsep objek, kelas, atribut, metode, tanggung jawab kelas | Kuliah, Praktikum | Case Study | Memodelkan kelas untuk kasus penjualan UMKM sederhana | Membaca bab pengantar OOP | Editor kode, alat gambar kelas | Koreksi rancangan kelas antar kelompok | Rancangan kelas beserta kodenya | TUGAS |
| 1.2 | Membedakan tanggung jawab antar kelas sehingga satu kelas tidak mengerjakan segalanya | 3 | 5 | Kohesi, kopling, tanda kelas yang terlalu besar | Kuliah, Praktikum | Collaborative Learning | Memecah satu kelas gemuk menjadi beberapa kelas | Membaca contoh kode tertata | Repositori kode | Tinjauan kode oleh teman | Kode hasil pemecahan beserta alasannya | TUGAS |
| 2.1 | Menerapkan enkapsulasi sehingga keadaan objek hanya berubah lewat perilaku yang disediakan | 4-5 | 10 | Enkapsulasi, hak akses, pembentuk objek, validasi keadaan | Praktikum | Praktik terbimbing | Menutup akses langsung ke atribut pada kode pekan lalu | Latihan mandiri | Lingkungan pemrograman | Kuis pendek | Kode terenkapsulasi beserta ujinya | PRAKTIK |
| 2.2 | Memanfaatkan pewarisan dan polimorfisme untuk menghindari penggandaan kode | 6-7 | 10 | Pewarisan, penggantian metode, kelas abstrak, antarmuka | Kuliah, Praktikum | Problem-Based Learning | Menyatukan tiga kelas serupa memakai pewarisan | Membaca bab pewarisan | Lingkungan pemrograman | Umpan balik saat praktikum | Kode beserta penjelasan pilihan rancangannya | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan sebagai pemrograman di tempat | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 3.1 | Menangani galat yang dapat diperkirakan sehingga program tidak berhenti mendadak | 9-10 | 10 | Penanganan galat, jenis galat, pesan galat yang berguna | Praktikum | Case Study | Menambahkan penanganan galat pada program yang ada | Latihan mandiri | Lingkungan pemrograman | Uji coba merusak program teman | Kode tahan galat beserta catatan kasusnya | PRAKTIK |
| 3.2 | Menulis pengujian unit yang membuktikan perilaku kelas sesuai rancangannya | 11-12 | 10 | Pengujian unit, penamaan uji, cakupan uji secukupnya | Praktikum | Praktik terbimbing | Menulis uji untuk kelas yang dibangun sendiri | Membaca contoh berkas uji | Kerangka uji bawaan bahasa | Uji dijalankan bersama di kelas | Berkas uji beserta hasil jalannya | TUGAS |
| 4.1 | Memisahkan logika, penyimpanan, dan antarmuka pada satu aplikasi kecil | 13-14 | 15 | Pelapisan aplikasi, pemisahan tanggung jawab, penyimpanan sederhana | Praktikum | Project-Based Learning | Membangun aplikasi berlapis bertahap | Mempelajari contoh aplikasi berlapis | Repositori kode | Tinjauan kemajuan mingguan | Aplikasi berlapis yang berjalan | PROYEK |
| 4.2 | Menyajikan rancangan dan hasil aplikasinya beserta alasan pilihan strukturnya | 15 | 15 | Penyajian rancangan, membaca kode orang lain | Seminar | Collaborative Learning | Menyiapkan bahan sajian dan demonstrasi | Berlatih menjelaskan kode sendiri | Bahan tayang, repositori | Gladi dengan umpan balik teman | Penyajian dan demonstrasi | PRESENTASI |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat proyek dan penyajian pekan 13 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.1 dan 4.2 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- Horstmann, C. S. (2022). *Core Java, Volume I: Fundamentals* (12th ed.). Oracle Press. Atau padanan resmi untuk bahasa yang dipakai prodi.
- Martin, R. C. (2008). *Clean Code: A Handbook of Agile Software Craftsmanship*. Prentice Hall.

**Pendukung**

- Freeman, E., & Robson, E. (2021). *Head First Design Patterns* (2nd ed.). O'Reilly Media.
- Dokumentasi resmi bahasa dan kerangka uji yang dipakai.

## Sarana yang diperlukan

Lab komputer dengan lingkungan pemrograman dan kerangka pengujian terpasang, repositori
kode bersama untuk tinjauan kode antar mahasiswa.
