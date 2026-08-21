# Bahan RPS: Cloud Computing Fundamental

**Kode** OBE0502402 · **Semester** 3 · **2 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-8** (Keterampilan Khusus) Mampu merancang, mengembangkan, menguji, dan men-deploy aplikasi web full-stack modern dengan praktik clean code, secure coding, dan deployment ke cloud.

**Prasyarat**: OBE0502206 Sistem Operasi. Sebaiknya diambil bersamaan atau setelah
OBE0502401 Jaringan Komputer.

**Catatan penempatan**: hanya 2 SKS, jadi godaan terbesarnya adalah menjejalkan seluruh
layanan penyedia cloud. Tahan diri. Yang dituju adalah mahasiswa mampu menerbitkan
aplikasinya sendiri, mengatur akses, dan memperkirakan biayanya. Kedalaman layanan khusus
diserahkan ke mata kuliah DevOps di semester lima.

**Peringatan biaya**: seluruh praktik dirancang agar muat di lapisan gratis penyedia
layanan. Sepakati batas anggaran dan matikan sumber daya seusai praktikum, dan jadikan itu
bagian dari penilaian, bukan sekadar imbauan.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Menjelaskan model layanan dan penyebaran cloud beserta pilihan yang tepat untuk satu kebutuhan | CPL-8 |
| CPMK-2 | Menerbitkan aplikasi ke layanan cloud beserta penyimpanan dan basis datanya | CPL-8 |
| CPMK-3 | Mengatur hak akses dan menjaga rahasia aplikasi di lingkungan cloud | CPL-8 |
| CPMK-4 | Memperkirakan dan mengendalikan biaya layanan yang dipakai | CPL-8 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Membandingkan model layanan cloud dan memilih yang sesuai untuk satu kasus UMKM | 1-2 | 10 | Model layanan, model penyebaran, tanggung jawab bersama penyedia dan penyewa | Kuliah | Case Study | Menyusun rekomendasi model untuk satu kasus | Membaca dokumentasi penyedia | Lembar kerja | Diskusi kelompok | Rekomendasi tertulis beserta alasannya | TUGAS |
| 2.1 | Menyalakan mesin virtual dan menjalankan aplikasi di atasnya | 3-4 | 15 | Mesin virtual, wilayah dan zona, sambungan aman ke mesin | Praktikum | Praktik terbimbing | Menerbitkan aplikasi sederhana ke mesin virtual | Latihan mandiri di lapisan gratis | Penyedia cloud, terminal | Pemeriksaan hasil terbit di kelas | Aplikasi berjalan beserta catatan langkahnya | PRAKTIK |
| 2.2 | Memakai penyimpanan objek dan basis data terkelola untuk aplikasi yang diterbitkan | 5-6 | 15 | Penyimpanan objek, basis data terkelola, cadangan otomatis | Praktikum | Problem-Based Learning | Memindahkan berkas dan data aplikasi ke layanan terkelola | Membaca dokumentasi layanan | Penyedia cloud | Uji pemulihan data di kelas | Aplikasi bersambung layanan terkelola | PRAKTIK |
| 3.1 | Mengatur hak akses sehingga tiap komponen hanya bisa mengakses yang diperlukannya | 7 | 10 | Identitas dan hak akses, peran, kunci akses, hak paling sedikit | Praktikum | Case Study | Menyusun peran akses untuk satu aplikasi | Membaca panduan hak akses penyedia | Penyedia cloud | Uji coba melampaui hak oleh teman | Konfigurasi hak akses beserta ujinya | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan sebagai kerja di konsol penyedia | — | — | — | — | — | — | Ujian praktik | UJIAN |
| 3.2 | Menyimpan rahasia aplikasi tanpa menaruhnya di dalam kode | 9-10 | 10 | Berkas lingkungan, brankas rahasia, akibat rahasia yang terlanjur tersimpan di repositori | Praktikum | Problem-Based Learning | Memindahkan rahasia dari kode ke brankas | Membaca kasus kebocoran rahasia nyata | Penyedia cloud, repositori | Pemeriksaan repositori terhadap rahasia | Bukti rahasia tak lagi di kode | PRAKTIK |
| 4.1 | Memperkirakan biaya bulanan satu rancangan sebelum menyalakannya | 11-12 | 10 | Kalkulator biaya, satuan tagihan, biaya tersembunyi seperti lalu lintas keluar | Kuliah, Praktikum | Case Study | Menyusun perkiraan biaya dua rancangan berbeda | Menelaah daftar harga penyedia | Kalkulator biaya penyedia | Pembahasan perkiraan bersama | Perkiraan biaya beserta perbandingannya | TUGAS |
| 4.2 | Memantau pemakaian dan mematikan sumber daya yang tidak dipakai | 13-15 | 15 | Pemantauan pemakaian, peringatan anggaran, kebersihan sumber daya | Praktikum, Seminar | Project-Based Learning | Menerbitkan proyek akhir beserta peringatan anggaran, lalu membersihkannya | Mempelajari fitur pemantauan penyedia | Penyedia cloud | Tinjauan kemajuan mingguan | Proyek terbit, bukti pemantauan, dan bukti pembersihan | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat proyek pekan 13 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.2 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- Dokumentasi resmi penyedia cloud yang dipakai prodi, khususnya bagian panduan awal dan harga.
- Erl, T., Mahmood, Z., & Puttini, R. (2013). *Cloud Computing: Concepts, Technology & Architecture*. Prentice Hall.

**Pendukung**

- Panduan lapisan gratis penyedia beserta batasannya, dibaca sebelum praktikum pertama.

## Sarana yang diperlukan

Akun penyedia cloud dengan lapisan gratis untuk tiap mahasiswa atau tiap kelompok, kartu
pembatas anggaran bila penyedia menuntut kartu, dan terminal. Sepakati sejak awal siapa
yang bertanggung jawab mematikan sumber daya, sebab tagihan yang lahir dari kelalaian
praktikum sulit dijelaskan ke bagian keuangan.
