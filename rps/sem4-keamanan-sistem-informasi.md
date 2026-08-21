# Bahan RPS: Keamanan Sistem Informasi

**Kode** OBE0502403 · **Semester** 4 · **3 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-3** (Pengetahuan) Menguasai konsep teoretis pemrograman, rekayasa perangkat lunak, basis data, jaringan, dan keamanan informasi secara umum.
- **CPL-8** (Keterampilan Khusus) Mampu merancang, mengembangkan, menguji, dan men-deploy aplikasi web full-stack modern dengan praktik clean code, secure coding, dan deployment ke cloud.

**Prasyarat**: OBE0502303 Pemrograman Web Backend, OBE0502401 Jaringan Komputer.

**Catatan penempatan dan etika**: seluruh praktik pengujian dilakukan **hanya** pada
sasaran yang disediakan prodi. Sepakati dan tandatangani aturan itu pada pertemuan pertama,
dan jadikan pelanggarannya berkonsekuensi akademik. Ini bukan formalitas: mahasiswa yang
menguji sistem pihak lain tanpa izin melanggar hukum, dan prodi ikut menanggung akibatnya.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Menjelaskan prinsip keamanan informasi dan menilai risiko pada satu sistem | CPL-3 |
| CPMK-2 | Menerapkan kendali keamanan pada aplikasi yang dibangunnya sendiri | CPL-8 |
| CPMK-3 | Menguji keamanan aplikasi pada sasaran yang diizinkan dan melaporkan temuannya | CPL-8 |
| CPMK-4 | Menyusun prosedur tanggap insiden dan pemulihan sederhana | CPL-3 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Menjelaskan kerahasiaan, keutuhan, dan ketersediaan pada satu sistem nyata beserta ancamannya | 1-2 | 10 | Prinsip keamanan, pemodelan ancaman sederhana, aset dan dampak | Kuliah | Case Study | Memodelkan ancaman satu aplikasi yang pernah dibangun | Membaca bab pengantar keamanan | Templat pemodelan ancaman | Diskusi model ancaman antar kelompok | Dokumen pemodelan ancaman | TUGAS |
| 1.2 | Menilai risiko dan mengurutkan prioritas penanganannya | 3 | 10 | Kemungkinan dan dampak, peringkat risiko, penerimaan risiko | Kuliah | Problem-Based Learning | Menyusun peringkat risiko untuk kasus yang sama | Latihan penilaian risiko | Lembar kerja risiko | Umpan balik dosen | Daftar risiko berperingkat beserta alasannya | TUGAS |
| 2.1 | Menerapkan autentikasi dan pengelolaan sesi yang aman | 4-5 | 10 | Penyimpanan kata sandi, sesi dan token, pembatasan percobaan masuk | Praktikum | Praktik terbimbing | Memperbaiki autentikasi aplikasi sendiri | Membaca panduan autentikasi OWASP | Aplikasi latihan | Uji coba menembus autentikasi teman | Kode beserta bukti perbaikannya | PRAKTIK |
| 2.2 | Menutup celah pada pengolahan masukan dan keluaran aplikasi | 6-7 | 10 | Penyisipan kueri, skrip lintas situs, pemalsuan permintaan, unggahan berkas | Praktikum | Problem-Based Learning | Memperbaiki aplikasi sengaja rentan yang disediakan dosen | Membaca sepuluh risiko teratas aplikasi web | Aplikasi sengaja rentan | Pembahasan temuan bersama | Laporan perbaikan beserta bukti sebelum dan sesudah | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7 | — | — | — | — | — | — | Ujian tertulis dan analisis kasus | UJIAN |
| 2.3 | Melindungi data saat disimpan dan saat dikirim | 9-10 | 10 | Penyandian data, sertifikat dan lapisan aman, pengelolaan kunci, data pribadi | Kuliah, Praktikum | Case Study | Menyalakan sambungan aman dan menyandikan data sensitif | Membaca panduan penyandian data | Aplikasi latihan, sertifikat uji | Pemeriksaan sambungan di kelas | Konfigurasi beserta buktinya | PRAKTIK |
| 3.1 | Menguji keamanan aplikasi pada sasaran yang diizinkan secara berurutan dan tercatat | 11-12 | 10 | Tahapan pengujian, perkakas pemindai, pencatatan langkah, batas kewenangan | Praktikum | Case Study | Menguji aplikasi sengaja rentan dan mencatat langkahnya | Membaca kaidah pengujian yang sah | Lab pengujian terisolasi | Pemeriksaan catatan langkah | Catatan pengujian beserta buktinya | PRAKTIK |
| 3.2 | Menyusun laporan temuan yang dapat ditindaklanjuti pengembang | 13 | 10 | Struktur laporan temuan, tingkat keparahan, langkah perbaikan | Kuliah, Praktikum | Collaborative Learning | Menyusun laporan atas temuan pekan lalu | Membaca contoh laporan temuan | Pengolah kata | Tinjauan sejawat atas laporan | Laporan temuan | TUGAS |
| 4.1 | Menyusun prosedur tanggap insiden dan pemulihan untuk satu sistem kecil | 14-15 | 15 | Tahapan tanggap insiden, cadangan dan pemulihan, komunikasi saat insiden | Praktikum, Seminar | Project-Based Learning | Menyusun prosedur dan menguji pemulihan cadangan | Mempelajari contoh prosedur tanggap insiden | Mesin virtual, dokumen prosedur | Uji pemulihan dilakukan di kelas | Prosedur beserta bukti uji pemulihannya | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat prosedur dan uji pemulihan pekan 14 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.1 | — |

Total bobot: 100.

---

## Aturan etika praktik, wajib disepakati pekan pertama

1. Pengujian hanya pada sasaran yang disediakan prodi di lab terisolasi.
2. Dilarang menguji sistem kampus, sistem pihak ketiga, atau sistem milik teman tanpa izin tertulis.
3. Temuan pada sistem nyata yang tidak sengaja ditemukan wajib dilaporkan ke dosen, bukan diumumkan atau dimanfaatkan.
4. Perkakas pengujian tidak dibawa keluar lab dalam keadaan siap pakai untuk sasaran luar.

## Referensi

**Utama**

- OWASP. *OWASP Top Ten* dan *Web Security Testing Guide* (edisi yang berlaku).
- Stallings, W., & Brown, L. (2018). *Computer Security: Principles and Practice* (4th ed.). Pearson.

**Pendukung**

- Undang-Undang Nomor 27 Tahun 2022 tentang Pelindungan Data Pribadi, dibaca langsung dari naskah resminya untuk bagian kewajiban pengendali data. ⚠️ Periksa peraturan pelaksananya yang terbit belakangan sebelum dikutip di kelas.
- Dokumentasi perkakas pengujian yang dipakai di lab.

## Sarana yang diperlukan

Lab terisolasi dari jaringan kampus, aplikasi sengaja rentan untuk latihan, mesin virtual
yang boleh dirusak, dan perkakas pengujian. Isolasi jaringan bukan pilihan, melainkan
syarat menjalankan mata kuliah ini dengan bertanggung jawab.
