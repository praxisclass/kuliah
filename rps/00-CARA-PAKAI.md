# Bahan RPS Mata Kuliah Inti D3 TI, dan cara memasukkannya

Berkas di folder ini adalah **bahan siap input**, bukan dokumen RPS jadi. Isinya sudah
disusun mengikuti kolom isian di OBC, jadi dosen tinggal menyalin, menyesuaikan dengan
kelasnya, lalu menyimpan.

## Cakupan

16 mata kuliah berkelompok **Inti** pada Kurikulum D3 Teknologi Informasi 2026. Kelompok
"Inti" diambil apa adanya dari data kurikulum di sistem, bukan tafsiran. Mata kuliah AIK,
MKWN, Pendukung, Diferensiasi, Pilihan, Capstone, Magang, dan Tugas Akhir tidak termasuk.

| Berkas | Kode | Mata kuliah | Sem | SKS |
|---|---|---|---|---|
| `sem1-pengantar-ti.md` | OBE0502201 | Pengantar Teknologi Informasi | 1 | 2 |
| `sem1-algoritma-pemrograman-dasar.md` | OBE0502202 | Algoritma dan Pemrograman Dasar | 1 | 4 |
| `sem1-logika-matematika-diskrit.md` | OBE0502203 | Logika Informatika dan Matematika Diskrit | 1 | 3 |
| `sem2-pemrograman-berorientasi-objek.md` | OBE0502204 | Pemrograman Berorientasi Objek | 2 | 4 |
| `sem2-struktur-data-algoritma.md` | OBE0502205 | Struktur Data dan Algoritma | 2 | 3 |
| `sem2-sistem-operasi.md` | OBE0502206 | Sistem Operasi | 2 | 3 |
| `sem2-basis-data.md` | OBE0502301 | Basis Data | 2 | 4 |
| `sem3-pemrograman-web-frontend.md` | OBE0502302 | Pemrograman Web Frontend | 3 | 3 |
| `sem3-pemrograman-web-backend.md` | OBE0502303 | Pemrograman Web Backend | 3 | 4 |
| `sem3-rekayasa-perangkat-lunak.md` | OBE0502304 | Rekayasa Perangkat Lunak | 3 | 3 |
| `sem3-desain-antarmuka-ux.md` | OBE0502305 | Desain Antarmuka dan UX | 3 | 3 |
| `sem3-jaringan-komputer.md` | OBE0502401 | Jaringan Komputer | 3 | 3 |
| `sem3-cloud-computing-fundamental.md` | OBE0502402 | Cloud Computing Fundamental | 3 | 2 |
| `sem4-pemrograman-mobile.md` | OBE0502306 | Pemrograman Mobile Cross-Platform | 4 | 4 |
| `sem4-keamanan-sistem-informasi.md` | OBE0502403 | Keamanan Sistem Informasi | 4 | 3 |
| `sem5-devops-cicd.md` | OBE0502404 | DevOps dan CI/CD | 5 | 2 |

## Cara memasukkan ke OBC

Urutannya mengikat. CPMK harus disetujui kaprodi sebelum Sub-CPMK bisa disandarkan padanya.

1. **Dosen koordinator** membuka `CPMK & Sub-CPMK`, memilih mata kuliahnya, lalu menyalin
   bagian **CPMK** dari berkas bahan. Kolom "CPL terkait" diisi sesuai yang tertulis;
   angkanya sudah dicocokkan dengan matriks CPL yang berlaku di sistem, jangan diubah
   tanpa membicarakannya dengan kaprodi.
2. **Kaprodi** menyetujui CPMK lewat `CPL & CPMK`.
3. **Dosen** kembali ke `CPMK & Sub-CPMK` dan memasukkan **Sub-CPMK**. Tiap baris di tabel
   bahan sudah setara satu Sub-CPMK, dan nama kolomnya sama dengan nama isian di formulir.
4. **Dosen** membuka `RPS`, menyusun RPS memakai bagian **Rencana pembelajaran mingguan**,
   **Referensi**, dan **Prasyarat** dari berkas bahan, lalu mengajukannya.
5. **Kaprodi** menyetujui RPS.

## Arti tiap kolom Sub-CPMK

| Kolom di bahan | Isian di OBC | Catatan |
|---|---|---|
| Kode | `kode` | Penomoran X.Y: X nomor CPMK, Y urutan Sub-CPMK di bawahnya |
| Rumusan | `deskripsi` | Satu kemampuan yang bisa diamati, bukan daftar topik |
| Minggu | `minggu` | Pekan pelaksanaan; pekan 8 dan 16 disediakan untuk ATS dan AAS |
| Bobot | `bobot` | Porsi nilai mata kuliah, satu MK totalnya 100 |
| Materi | `materi` | Pokok bahasan pekan itu |
| Bentuk pembelajaran | `bentukPembelajaran` | Kuliah, Praktikum, Seminar, atau gabungannya |
| Metode | `metodeSCL` | Metode berpusat mahasiswa yang dipakai |
| Tugas terstruktur | `tugasTerstruktur` | Yang dikerjakan di luar kelas dengan panduan |
| Belajar mandiri | `belajarMandiri` | Yang dipelajari sendiri |
| Platform | `platform` | Perkakas yang dipakai pekan itu |
| Asesmen formatif | `assessmentFormatif` | Untuk umpan balik, tidak dikirim ke perhitungan capaian |
| Asesmen sumatif | `assessmentSumatif` | Yang menghasilkan nilai |
| Bentuk asesmen | `bentukAsesmen` | Pilih satu: TUGAS, KUIS, UJIAN, PROYEK, PRESENTASI, PRAKTIK, OBSERVASI, LAINNYA |

## Yang harus dosen sesuaikan, jangan disalin bulat-bulat

Bahan ini menyediakan kerangka yang sudah selaras dengan CPL prodi. Empat hal berikut
tetap keputusan dosen pengampu, dan memang seharusnya berbeda antar kelas:

1. **Bobot penilaian.** Angka di bahan adalah usulan yang totalnya 100. Sesuaikan dengan
   penekanan Anda, asalkan totalnya tetap 100.
2. **Kasus dan konteks.** Ganti contoh kasus dengan yang dekat dengan mahasiswa Anda.
   Konteks UMKM dan pariwisata dipakai di bahan ini karena itu penciri prodi.
3. **Perkakas.** Platform yang disebut adalah yang lazim, bukan keharusan. Pakai yang
   benar-benar tersedia di lab.
4. **Referensi.** Tahun terbit perlu Anda periksa sendiri terhadap koleksi perpustakaan.
   Bahan ini menyebut edisi yang beredar luas, tetapi ketersediaannya berbeda tiap kampus.

## Catatan kejujuran tentang bahan ini

Rumusan CPMK dan Sub-CPMK di sini diturunkan dari CPL yang benar-benar dipikul tiap mata
kuliah menurut matriks di sistem, dan kata kerjanya sengaja dipilih yang dapat diamati
(merancang, membangun, menguji, mengukur), bukan "memahami" atau "mengetahui" yang tidak
bisa dinilai.

Yang belum dan tidak bisa dikerjakan dari luar: **rubrik penilaian rinci**. Rubrik yang
baik menyebut perbuatan pada tiap tingkat mutu, dan itu menuntut pengetahuan tentang
mahasiswa yang diajar. Bahan ini menyebut bentuk asesmennya, dosen yang menetapkan
kriteria mutunya.
