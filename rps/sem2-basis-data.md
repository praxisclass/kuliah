# Bahan RPS: Basis Data

**Kode** OBE0502301 · **Semester** 2 · **4 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-3** (Pengetahuan) Menguasai konsep teoretis pemrograman, rekayasa perangkat lunak, basis data, jaringan, dan keamanan informasi secara umum.
- **CPL-8** (Keterampilan Khusus) Mampu merancang, mengembangkan, menguji, dan men-deploy aplikasi web full-stack modern dengan praktik clean code, secure coding, dan deployment ke cloud.
- **CPL-9** (Keterampilan Khusus) Mampu merancang, mengembangkan, dan mempublikasikan aplikasi mobile cross-platform untuk kebutuhan UMKM, pariwisata, dan industri kreatif.

**Prasyarat**: OBE0502203 Logika Informatika dan Matematika Diskrit.

**Catatan penempatan**: memikul tiga CPL karena basis data menjadi tulang punggung
aplikasi web maupun mobile yang dibangun di semester berikutnya. Rancangan yang salah di
sini akan terbawa ke seluruh mata kuliah setelahnya, jadi porsi perancangan sengaja
diberi bobot besar sebelum masuk ke kueri.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Merancang model data dari kebutuhan nyata sampai bentuk normal ketiga | CPL-3 |
| CPMK-2 | Membangun basis data relasional beserta batasan integritasnya | CPL-3, CPL-8 |
| CPMK-3 | Menyusun kueri untuk mengambil dan mengubah data, termasuk penggabungan dan pengelompokan | CPL-8 |
| CPMK-4 | Menghubungkan basis data dengan aplikasi secara aman dan menjaga kinerjanya saat data bertambah | CPL-8, CPL-9 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Mengenali entitas, atribut, dan hubungan dari uraian kebutuhan satu usaha nyata | 1-2 | 10 | Model entitas hubungan, kardinalitas, kunci | Kuliah, Praktikum | Case Study | Menyusun model data untuk satu UMKM setempat | Membaca bab pemodelan data | Alat gambar model data | Koreksi model antar kelompok | Model entitas hubungan beserta penjelasannya | TUGAS |
| 1.2 | Menormalkan model sampai bentuk normal ketiga dan menjelaskan mengapa perlu | 3-4 | 10 | Ketergantungan fungsional, bentuk normal pertama sampai ketiga, kelebihan data | Kuliah | Problem-Based Learning | Menormalkan tabel bermasalah yang disediakan dosen | Latihan soal normalisasi | Lembar kerja | Pembahasan bersama | Hasil normalisasi beserta langkahnya | TUGAS |
| 2.1 | Membangun basis data beserta kunci, batasan, dan jenis data yang tepat | 5 | 10 | Bahasa definisi data, kunci utama dan asing, batasan nilai | Praktikum | Praktik terbimbing | Menerapkan model pekan lalu menjadi basis data nyata | Latihan mandiri | Peladen basis data, klien SQL | Pemeriksaan skema saat praktikum | Skema basis data yang berjalan | PRAKTIK |
| 3.1 | Menyusun kueri pengambilan data dengan penyaringan, pengurutan, dan pembatasan | 6 | 10 | Perintah select, penyaringan, pengurutan, pembatasan hasil | Praktikum | Praktik terbimbing | Mengerjakan dua puluh kueri berjenjang | Latihan mandiri | Klien SQL, data contoh | Kuis pendek | Kumpulan kueri beserta hasilnya | PRAKTIK |
| 3.2 | Menyusun kueri penggabungan antar tabel dan pengelompokan beserta penyaringan kelompok | 7 | 10 | Penggabungan, pengelompokan, fungsi agregat | Praktikum | Problem-Based Learning | Menjawab pertanyaan bisnis memakai kueri | Latihan mandiri | Klien SQL | Umpan balik saat praktikum | Kumpulan kueri penjawab pertanyaan bisnis | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan langsung di basis data | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 2.2 | Menjaga keutuhan data memakai transaksi dan batasan saat terjadi perubahan berbarengan | 9-10 | 10 | Transaksi, sifat transaksi, penguncian, kegagalan di tengah jalan | Kuliah, Praktikum | Case Study | Menguji perilaku dua transaksi berbarengan | Membaca bab transaksi | Klien SQL dua sesi | Diskusi hasil percobaan | Laporan percobaan transaksi | PRAKTIK |
| 4.1 | Menghubungkan basis data dengan program tanpa membuka celah penyisipan kueri | 11-12 | 10 | Sambungan aplikasi, kueri berparameter, hak akses pengguna basis data | Praktikum | Problem-Based Learning | Menyambungkan program ke basis data dengan kueri berparameter | Membaca panduan keamanan kueri | Lingkungan pemrograman, basis data | Uji coba penyisipan kueri di kelas | Kode sambungan beserta bukti amannya | PRAKTIK |
| 4.2 | Mempercepat kueri lambat memakai indeks dan membuktikan perbaikannya dengan pengukuran | 13-14 | 10 | Indeks, rencana eksekusi, biaya indeks | Praktikum | Case Study | Memperbaiki kueri lambat pada data besar | Membaca cara membaca rencana eksekusi | Klien SQL, data besar | Pembahasan rencana eksekusi bersama | Laporan sebelum dan sesudah beserta angkanya | TUGAS |
| 4.3 | Menyajikan rancangan basis data satu kasus nyata beserta alasan keputusannya | 15 | 5 | Penyajian rancangan, mempertanggungjawabkan keputusan | Seminar | Collaborative Learning | Menyiapkan bahan sajian | Berlatih menjelaskan rancangan | Bahan tayang | Gladi dengan umpan balik teman | Penyajian rancangan | PRESENTASI |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat asesmen pekan 9 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 2.2 sampai 4.3 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.
- Beaulieu, A. (2020). *Learning SQL* (3rd ed.). O'Reilly Media.

**Pendukung**

- Dokumentasi resmi sistem basis data yang dipakai prodi.
- OWASP. Panduan pencegahan penyisipan kueri (edisi terbaru yang tersedia).

## Sarana yang diperlukan

Lab dengan peladen basis data yang bisa diakses tiap mahasiswa, klien SQL, dan satu
kumpulan data berukuran cukup besar untuk latihan indeks. Data kecil tidak akan
memperlihatkan bedanya, dan pelajaran indeks jadi hampa.
