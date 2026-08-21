# Bahan RPS: Jaringan Komputer

**Kode** OBE0502401 · **Semester** 3 · **3 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-3** (Pengetahuan) Menguasai konsep teoretis pemrograman, rekayasa perangkat lunak, basis data, jaringan, dan keamanan informasi secara umum.

**Prasyarat**: OBE0502206 Sistem Operasi.

**Catatan penempatan**: mata kuliah ini menopang Cloud Computing yang berjalan sejajar,
dan DevOps di semester lima. Untuk vokasi, bukti kemampuannya adalah jaringan yang benar
menyala dan gejala gangguan yang benar terdiagnosis, bukan hafalan lapisan model jaringan.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Menjelaskan perjalanan data antar perangkat beserta peran tiap lapisan protokol | CPL-3 |
| CPMK-2 | Merancang pengalamatan jaringan untuk satu kebutuhan nyata | CPL-3 |
| CPMK-3 | Membangun dan menguji jaringan kecil beserta layanan dasarnya | CPL-3 |
| CPMK-4 | Mendiagnosis gangguan jaringan berdasarkan bukti, bukan dugaan | CPL-3 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Menelusuri perjalanan satu permintaan dari peramban sampai peladen dan kembali | 1-2 | 10 | Model lapisan, enkapsulasi, protokol yang terlibat pada satu permintaan | Kuliah, Praktikum | Case Study | Menangkap dan membaca lalu lintas satu permintaan | Membaca bab pengantar jaringan | Penganalisis lalu lintas jaringan | Pembacaan hasil tangkapan bersama | Laporan penelusuran beserta tangkapan layarnya | TUGAS |
| 2.1 | Menghitung pembagian alamat jaringan untuk kebutuhan sejumlah perangkat tertentu | 3-4 | 15 | Pengalamatan, subnet, gerbang, penetapan alamat otomatis | Kuliah, Praktikum | Problem-Based Learning | Merancang pembagian alamat untuk denah lab | Latihan soal pengalamatan | Lembar kerja, penghitung subnet | Kuis pendek | Rancangan pengalamatan beserta perhitungannya | TUGAS |
| 3.1 | Membangun jaringan kecil yang saling terhubung beserta pengujiannya | 5-6 | 15 | Perangkat jaringan, penyambungan, penghalaan dasar, pengujian sambungan | Praktikum | Praktik terbimbing | Membangun topologi pada simulator dan pada perangkat nyata bila tersedia | Latihan mandiri di simulator | Simulator jaringan, perangkat lab | Pemeriksaan topologi saat praktikum | Jaringan berjalan beserta bukti pengujiannya | PRAKTIK |
| 3.2 | Menyalakan layanan dasar jaringan dan membuktikan layanan itu melayani | 7 | 10 | Penamaan, penetapan alamat otomatis, layanan berbagi berkas | Praktikum | Praktik terbimbing | Menyalakan layanan penamaan dan penetapan alamat | Membaca dokumentasi layanan | Mesin virtual, simulator | Uji layanan oleh teman | Layanan berjalan beserta catatan konfigurasinya | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7, dikerjakan sebagai kerja lab | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 3.3 | Menerapkan penyaringan lalu lintas untuk membatasi akses sesuai kebutuhan | 9-10 | 10 | Penyaring paket, aturan izin dan tolak, urutan aturan | Praktikum | Problem-Based Learning | Menyusun aturan penyaring untuk satu kebutuhan | Membaca dokumentasi penyaring | Mesin virtual | Uji tembus aturan oleh kelompok lain | Aturan penyaring beserta bukti ujinya | PRAKTIK |
| 4.1 | Mendiagnosis gangguan jaringan secara berurutan dari lapisan bawah ke atas | 11-12 | 10 | Urutan pemeriksaan, perkakas diagnosis, membaca gejala | Praktikum | Case Study | Mendiagnosis jaringan yang sengaja dirusak dosen | Berlatih memakai perkakas diagnosis | Perkakas diagnosis jaringan | Pembahasan langkah diagnosis di kelas | Laporan diagnosis beserta buktinya | PRAKTIK |
| 4.2 | Menyusun dokumentasi jaringan yang cukup bagi orang lain untuk merawatnya | 13-15 | 15 | Dokumentasi topologi, daftar alamat, prosedur pemulihan | Praktikum, Seminar | Project-Based Learning | Menyusun dokumen jaringan proyek akhir | Mempelajari contoh dokumentasi jaringan | Pengolah kata, alat gambar topologi | Tinjauan kemajuan mingguan | Dokumen jaringan beserta penyajiannya | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat proyek pekan 13 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.2 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- Kurose, J. F., & Ross, K. W. (2021). *Computer Networking: A Top-Down Approach* (8th ed.). Pearson.
- Odom, W. (edisi terbaru). *CCNA 200-301 Official Cert Guide*. Cisco Press. Dipakai untuk bagian praktik pengalamatan dan penghalaan.

**Pendukung**

- Dokumentasi perkakas diagnosis jaringan yang dipakai di lab.

## Sarana yang diperlukan

Lab dengan simulator jaringan, mesin virtual, dan bila memungkinkan perangkat jaringan
nyata untuk sekurangnya satu pertemuan. Simulator memadai untuk sebagian besar capaian,
tetapi menyentuh perangkat nyata sekali saja mengubah pemahaman mahasiswa tentang kabel,
lampu indikator, dan gejala gangguan fisik.
