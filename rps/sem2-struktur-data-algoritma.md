# Bahan RPS: Struktur Data dan Algoritma

**Kode** OBE0502205 · **Semester** 2 · **3 SKS** · Kelompok Inti

**CPL yang dipikul**:

- **CPL-3** (Pengetahuan) Menguasai konsep teoretis pemrograman, rekayasa perangkat lunak, basis data, jaringan, dan keamanan informasi secara umum.
- **CPL-5** (Keterampilan Umum) Mampu menyelesaikan pekerjaan TI berlingkup luas dengan menganalisis data, memilih metode tepat, dan menunjukkan kinerja bermutu serta terukur.

**Prasyarat**: OBE0502202 Algoritma dan Pemrograman Dasar.

**Catatan penempatan**: untuk jenjang vokasi, penekanannya pada **memilih** struktur data
yang tepat dan membuktikan pilihannya dengan pengukuran, bukan pada membuktikan kompleksitas
secara matematis. Karena itu tiap Sub-CPMK di bawah menuntut ukuran nyata, bukan sekadar
notasi.

---

## CPMK

| Kode | Rumusan | CPL terkait |
|---|---|---|
| CPMK-1 | Menjelaskan sifat struktur data dasar beserta biaya operasinya | CPL-3 |
| CPMK-2 | Mengimplementasikan struktur data dan algoritma dasar dalam program yang berjalan | CPL-3, CPL-5 |
| CPMK-3 | Membandingkan kinerja beberapa pilihan penyelesaian berdasarkan pengukuran, bukan dugaan | CPL-5 |
| CPMK-4 | Memilih struktur data yang tepat untuk satu kasus nyata dan mempertanggungjawabkan pilihannya | CPL-5 |

---

## Sub-CPMK dan rencana pembelajaran mingguan

| Kode | Rumusan | Minggu | Bobot | Materi | Bentuk pembelajaran | Metode | Tugas terstruktur | Belajar mandiri | Platform | Asesmen formatif | Asesmen sumatif | Bentuk asesmen |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1.1 | Menjelaskan biaya operasi sisip, hapus, dan cari pada larik dan senarai berkait | 1-2 | 10 | Larik, senarai berkait, biaya operasi, notasi pertumbuhan | Kuliah, Praktikum | Problem-Based Learning | Menyusun tabel biaya operasi beserta alasannya | Membaca bab struktur data dasar | Lingkungan pemrograman | Pembahasan bersama | Tabel biaya beserta penjelasan | TUGAS |
| 2.1 | Mengimplementasikan tumpukan dan antrean beserta pemakaiannya pada kasus nyata | 3-4 | 10 | Tumpukan, antrean, penerapan pada riwayat dan antrean tugas | Praktikum | Praktik terbimbing | Membangun tumpukan dan antrean dari nol | Latihan mandiri | Lingkungan pemrograman | Kuis pendek | Kode beserta ujinya | PRAKTIK |
| 2.2 | Mengimplementasikan pencarian berurutan dan pencarian bagi dua beserta syarat pemakaiannya | 5 | 10 | Pencarian berurutan, pencarian bagi dua, prasyarat data terurut | Praktikum | Problem-Based Learning | Membandingkan dua cara pencarian pada data besar | Latihan mandiri | Lingkungan pemrograman, pengukur waktu | Umpan balik saat praktikum | Kode beserta hasil pengukuran | PRAKTIK |
| 2.3 | Mengimplementasikan sekurang-kurangnya dua algoritma pengurutan dan menjelaskan bedanya | 6-7 | 10 | Pengurutan sederhana, pengurutan bagi dan kuasai, kestabilan | Kuliah, Praktikum | Praktik terbimbing | Mengimplementasikan dua algoritma pengurutan | Membaca bab pengurutan | Lingkungan pemrograman | Kuis pendek | Kode dua algoritma beserta penjelasan | PRAKTIK |
| — | **Asesmen Tengah Semester** | 8 | 15 | Cakupan pekan 1 sampai 7 | — | — | — | — | — | — | Ujian praktik di lab | UJIAN |
| 3.1 | Mengukur waktu jalan beberapa penyelesaian pada ukuran data yang berbeda dan menyajikannya | 9-10 | 10 | Pengukuran waktu, pengaruh ukuran data, penyajian hasil ukur | Praktikum | Case Study | Mengukur dan membuat grafik perbandingan | Membaca cara mengukur yang wajar | Pengukur waktu, pengolah grafik | Diskusi hasil ukur di kelas | Laporan pengukuran beserta grafik | TUGAS |
| 3.2 | Menyimpulkan pilihan terbaik dari hasil pengukuran, termasuk mengakui bila selisihnya tidak berarti | 11 | 5 | Membaca hasil ukur, batas kesimpulan, kejujuran data | Kuliah | Collaborative Learning | Menulis kesimpulan atas data pekan lalu | Membaca contoh laporan yang jujur | Pengolah kata | Tinjauan sejawat | Kesimpulan tertulis | TUGAS |
| 2.4 | Mengimplementasikan tabel hash atau pohon pencarian untuk pencarian cepat | 12-13 | 10 | Tabel hash, pohon pencarian, tabrakan kunci | Praktikum | Praktik terbimbing | Membangun penyimpan data berkunci | Latihan mandiri | Lingkungan pemrograman | Kuis pendek | Kode beserta ujinya | PRAKTIK |
| 4.1 | Memilih struktur data untuk satu kasus nyata dan membuktikan pilihannya dengan pengukuran | 14-15 | 20 | Penggabungan seluruh materi pada satu kasus | Praktikum, Seminar | Project-Based Learning | Mengerjakan studi kasus pilihan struktur data | Mempelajari kasus serupa | Repositori kode, pengukur waktu | Tinjauan kemajuan | Laporan studi kasus beserta kode dan pengukuran | PROYEK |
| — | **Asesmen Akhir Semester** | 16 | — | Dinilai lewat studi kasus pekan 14 sampai 15 | — | — | — | — | — | — | Sudah tercakup pada Sub-CPMK 4.1 | — |

Total bobot: 100.

---

## Referensi

**Utama**

- Goodrich, M. T., Tamassia, R., & Goldwasser, M. H. (2013). *Data Structures and Algorithms in Python*. Wiley. Atau padanan untuk bahasa yang dipakai prodi.
- Cormen, T. H., Leiserson, C. E., Rivest, R. L., & Stein, C. (2022). *Introduction to Algorithms* (4th ed.). MIT Press. Dipakai sebagai rujukan, bukan bacaan wajib penuh.

**Pendukung**

- Dokumentasi struktur data bawaan bahasa yang dipakai, termasuk biaya operasinya.

## Sarana yang diperlukan

Lab komputer dengan lingkungan pemrograman, alat pengukur waktu jalan, dan pengolah grafik
sederhana untuk menyajikan hasil pengukuran.
