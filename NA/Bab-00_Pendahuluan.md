# Bab 0. Pendahuluan: Peta Kompetensi, Cara Belajar, dan Etika Profesi

## Capaian pembelajaran bab

Sesudah mempelajari bab ini mahasiswa mampu:

1. Menjelaskan kedudukan mata kuliah Network Administrator pada kurikulum D3
   Teknologi Informasi beserta keterkaitannya dengan mata kuliah lain.
2. Memetakan unit kompetensi SKKNI Bidang Jaringan Komputer terhadap
   pertemuan perkuliahan.
3. Menyiapkan lingkungan kerja praktikum di komputer sendiri.
4. Menjelaskan batas wewenang dan tanggung jawab administrator jaringan dalam
   mengelola aset milik pihak lain.
5. Menunjukkan sikap amanah dan jujur pada situasi kerja yang konkret.

Capaian ini menopang seluruh CPMK mata kuliah, dan menjadi prasyarat sikap
sebelum mahasiswa menyentuh perangkat apa pun pada pertemuan berikutnya.

## Peta konsep

```
Bab 0 Pendahuluan
|-- Mengapa mata kuliah ini ada
|-- Posisi mata kuliah pada kurikulum
|-- Peta kompetensi
|   |-- Unit kompetensi SKKNI
|   |-- Skema sertifikasi Junior Network Administrator
|   `-- CPMK dan Sub-CPMK
|-- Cara belajar
|   |-- Beban waktu
|   |-- Perangkat lunak
|   `-- Bukti kerja yang dikumpulkan
|-- Etika profesi
|   |-- Batas wewenang
|   |-- Perubahan terdokumentasi
|   `-- Kerahasiaan
`-- Nilai Al-Islam dan Kemuhammadiyahan
    |-- Amanah
    |-- Kejujuran
    |-- Ta'awun
    `-- Menjaga harta
```

---

## 0.1 Mengapa mata kuliah ini ada

Bayangkan sebuah kantor kabupaten dengan tiga lantai. Lantai satu melayani
masyarakat, lantai dua tempat staf administrasi, lantai tiga ruang pimpinan.
Ada enam puluh komputer, dua server di ruang tersendiri, satu sambungan
internet, dan satu jaringan nirkabel untuk tamu.

Suatu pagi, internet di lantai dua mati. Staf tidak dapat mengirim laporan.
Pimpinan memanggil teknisi. Teknisi datang, mencabut dan memasang kembali
beberapa kabel, dan akhirnya berkata bahwa ia akan mengganti satu perangkat.
Dua jam kemudian jaringan hidup kembali. Tidak ada yang tahu persis apa
penyebabnya, dan tidak ada catatan tertulis tentang apa yang telah diubah.

Seminggu kemudian, jaringan mati lagi.

Keadaan seperti ini bukan sekadar soal teknis. Jaringan yang tidak
terdokumentasi membuat setiap gangguan menjadi tebakan, setiap perbaikan
menjadi percobaan, dan setiap percobaan meninggalkan perubahan yang tidak
diketahui siapa pun. Mata kuliah ini disusun untuk mengakhiri kebiasaan itu.

Administrator jaringan bekerja pada tiga hal sekaligus:

- **Merancang**, agar jaringan yang dibangun dapat dipahami dan diulang.
- **Mengelola**, agar layanan berjalan dengan mutu yang dapat diukur.
- **Memulihkan**, agar gangguan dituntaskan dengan urutan yang jelas, bukan
  dengan mencabut kabel secara acak.

Ketiga hal itu akan kalian kerjakan bertahap, mulai dari menghitung alamat
sampai menerbitkan layanan ke lingkungan komputasi awan.

## 0.2 Posisi mata kuliah pada kurikulum

Mata kuliah ini berkode KPT0502324 dan berbobot 3 SKS. Bahan kajiannya
terdiri atas administrasi sistem dan komputasi awan, dengan porsi praktik
5.610 menit dari total 8.160 menit, atau 68,7 persen. Angka itu berarti
sebagian besar waktu kalian berada di laboratorium, bukan di ruang kuliah.

Keterkaitannya dengan mata kuliah lain:

| Mata kuliah | Hubungannya |
|---|---|
| Networking | Menyediakan konsep dasar jaringan yang kalian gunakan sejak pertemuan kedua |
| Computer Networking Database | Menjadi landasan ketika layanan server mulai menggunakan basis data |
| Operating System | Menjadi landasan ketika kalian memasang dan mengelola sistem operasi server |
| Ethical Hacking | Melihat jaringan yang sama dari sisi penyerang, sehingga kalian tahu apa yang harus dikunci |
| Kerja Praktek | Tempat seluruh keterampilan mata kuliah ini dipertanggungjawabkan di dunia kerja |

Perlu dicatat: dokumen kurikulum yang beredar di program studi tidak
mencantumkan prasyarat untuk mata kuliah ini. Karena itu kalian tidak akan
ditolak hanya karena belum lulus mata kuliah tertentu, tetapi kalian
sendiri yang akan merasakan kesulitannya bila konsep dasar jaringan belum
dikuasai. Bagian 0.4 menyebutkan apa yang dapat kalian lakukan untuk
mengejar ketinggalan itu.

## 0.3 Peta kompetensi

Mata kuliah ini tidak disusun dari daftar topik, melainkan dari unit
kompetensi kerja. Artinya, tiap pertemuan melatih satu kemampuan yang
memang dipergunakan pada pekerjaan administrator jaringan.

### Unit kompetensi SKKNI

Acuannya SKKNI Kategori Informasi dan Komunikasi, Golongan Pokok
Telekomunikasi, Bidang Jaringan Komputer, pada Kepmenaker Nomor 321 Tahun
2016. Unit yang dilatih pada mata kuliah ini:

| Kode unit | Judul unit | Pertemuan |
|---|---|---|
| J.611000.004.01 | Merancang pengalamatan jaringan | 2 |
| J.611000.012.02 | Mengonfigurasi switch pada jaringan | 3 |
| J.611000.013.02 | Mengonfigurasi routing dalam satu autonomous system | 5 |
| J.611000.014.02 | Mengonfigurasi routing antar autonomous system | 6 |
| J.611000.010.02 | Memasang jaringan nirkabel | 7 |
| J.611000.017.01 | Mengidentifikasi sumber kerusakan | 13, 14 |
| J.611000.018.01 | Memperbaiki kerusakan konfigurasi jaringan | 14 |
| J.611000.020.01 | Mengoptimalkan kinerja sistem jaringan | 13 |
| J.611000.021.02 | Memelihara jaringan | 13, 14 |
| J.611000.022.01 | Melakukan backup dan restore konfigurasi perangkat | 14 |

Unit di atas belum mencakup administrasi server dan komputasi awan. Kedua
bagian itu bersumber dari bahan kajian mata kuliah yang tertulis pada
dokumen kurikulum, bukan dari SKKNI. Keadaan ini wajar: SKKNI menyusun
kompetensi kerja pada satu bidang, sedangkan mata kuliah menyusun kemampuan
lulusan yang lebih luas dari satu jabatan.

Catatan penting: SKKNI dapat direvisi. Sebelum kalian menyusun berkas
sertifikasi yang sesungguhnya, periksa dulu apakah Kepmenaker 321/2016
masih berlaku, atau sudah diganti oleh keputusan yang lebih baru. Status
mutakhirnya belum dicek pada naskah ini.

### Skema sertifikasi

Selain SKKNI, terdapat skema sertifikasi Junior Network Administrator pada
LSP Informatika, dengan lima unit yang diujikan: pengalamatan jaringan,
jaringan nirkabel, konfigurasi switch, routing dalam satu autonomous
system, dan routing antar autonomous system. Kelima unit itu seluruhnya
terlatih pada mata kuliah ini, pada pertemuan 2, 3, 5, 6, dan 7.

Artinya, sesudah pertemuan ketujuh kalian sudah menyentuh seluruh unit yang
diujikan pada skema itu. Bila kalian berminat mengambil sertifikasinya,
berkasilah pada lima pertemuan tersebut, sebab nilainya menjadi bukti
pendukung yang kuat.

### CPMK yang dilatih

| CPMK | Ringkasnya | Pertemuan |
|---|---|---|
| CPMK-1 | Merancang pengalamatan jaringan | 1, 2 |
| CPMK-2 | Mengonfigurasi switch dan routing | 3, 4, 5, 6 |
| CPMK-3 | Memasang jaringan nirkabel terkendali | 7 |
| CPMK-4 | Memasang dan mengamankan layanan server | 9, 10, 11, 12 |
| CPMK-5 | Memantau, mencadangkan, dan memulihkan | 13, 14 |
| CPMK-6 | Menerapkan virtualisasi dan komputasi awan | 15 |

## 0.4 Cara belajar pada mata kuliah ini

### Beban waktu

Beban mata kuliah 8.160 menit per semester. Bila tersebar pada 14
pertemuan pembelajaran, setiap pertemuan menuntut sekitar 583 menit, yang
terbagi atas praktik sekitar 401 menit dan teori sekitar 182 menit. Dari
angka itu, waktu tatap muka praktikum 180 menit. Sisanya, sekitar 221 menit
per pertemuan, dikerjakan sebagai tugas terstruktur dan belajar mandiri.

Konsekuensinya jelas: kalian tidak akan selesai bila hanya hadir di
laboratorium. Lembar kerja praktikum dirancang menyisakan pekerjaan rumah
yang harus diselesaikan sebelum pertemuan berikutnya, sebab pertemuan
berikutnya selalu bertumpu pada hasil pertemuan sebelumnya.

### Perangkat lunak yang diperlukan

| Perangkat lunak | Kegunaan | Pertemuan |
|---|---|---|
| Cisco Packet Tracer | Simulasi perangkat jaringan | 2 sampai 7 |
| VirtualBox | Menjalankan mesin virtual server | 8 sampai 14 |
| Citra Ubuntu Server | Sistem operasi yang dikelola | 8 sampai 14 |
| Perangkat lunak pengolah berkas teks | Menulis laporan dan dokumentasi | Semua |

Bila komputer kalian tidak mampu menjalankan mesin virtual, laporkan pada
pertemuan pertama. Laboratorium menyediakan komputer yang lebih memadai,
dan pengaturan kelompok kerja akan disesuaikan.

### Bukti kerja yang dikumpulkan

Penilaian tidak bertumpu pada ujian saja. Yang dikumpulkan:

1. Laporan praktikum tiap pertemuan, berisi tangkapan layar dan penjelasan.
2. Berkas konfigurasi perangkat, yang menjadi bukti bahwa pekerjaan dapat
   diulang.
3. Proyek rancang bangun, dibangun bertahap dari pertemuan 2 sampai 15.
4. Demonstrasi dan presentasi pada akhir semester.

Kumpulkan laporan pada folder yang rapi sejak pertemuan pertama. Struktur
folder yang disarankan:

```
Network-Administrator/
|-- 00-Laporan/
|   |-- Pertemuan-01_Inventarisasi.md
|   `-- Pertemuan-02_Rencana-Alamat.md
|-- 01-Konfigurasi/
|   |-- switch-lantai1.cfg
|   `-- router-utama.cfg
|-- 02-Topologi/
|   `-- topologi-instansi.pkt
`-- 03-Proyek/
    `-- dokumentasi-proyek.md
```

## 0.5 Etika profesi

Administrator jaringan memegang kunci seluruh data organisasi. Ia dapat
membaca surat elektronik pimpinan, membuka berkas keuangan, dan mematikan
layanan tanpa meninggalkan jejak. Karena itu etika pada profesi ini bukan
hiasan, melainkan syarat kerja.

### Batas wewenang

Bekerjalah hanya pada perangkat dan layanan yang menjadi tanggung jawab
kalian. Menguji keamanan server milik organisasi lain, meski dengan niat
baik, adalah pelanggaran hukum, bukan sekadar pelanggaran etika.

Perubahan apa pun pada perangkat produksi harus melalui izin tertulis,
disertai rencana pengembalian bila perubahan itu gagal. Izin lisan cukup
untuk laboratorium, tetapi tidak pernah cukup untuk jaringan yang sedang
melayani masyarakat.

### Perubahan harus terdokumentasi

Sebelum mengubah konfigurasi, tulis tiga hal:

1. Apa yang akan diubah, dan mengapa.
2. Apa yang mungkin rusak akibat perubahan itu.
3. Bagaimana mengembalikan keadaan bila perubahan itu gagal.

Tiga baris itu menyelamatkan kalian dari dua hal: tuduhan bahwa kalian
merusak jaringan, dan ketidaktahuan tentang apa yang telah kalian lakukan
semalam.

### Kerahasiaan

Kata sandi, kunci akses, alamat surel staf, dan isi berkas yang tidak
sengaja terbaca tidak boleh diceritakan kepada siapa pun, termasuk kepada
rekan kerja yang tidak berkepentingan. Berbagi kata sandi, meski dengan
alasan membantu, membuat jejak audit menjadi tidak berguna.

## 0.6 Nilai Al-Islam dan Kemuhammadiyahan

UNIMMA menetapkan nilai Al-Islam dan Kemuhammadiyahan sebagai penciri
institusional yang melekat pada seluruh mata kuliah. Pada mata kuliah ini
nilai itu diwujudkan pada empat hal berikut.

**Amanah.** Mengelola jaringan berarti memegang amanah atas aset yang bukan
milik sendiri. Setiap akun yang kalian buat, setiap berkas yang kalian
salin, dan setiap konfigurasi yang kalian ubah dilakukan atas nama
kepercayaan orang lain. Amanah tidak cukup diniatkan; ia harus tampak pada
catatan yang tertulis.

**Kejujuran (shidq).** Bila gangguan terjadi karena kesalahan kalian
sendiri, katakan demikian. Kesalahan yang dilaporkan jujur dapat
ditangani bersama, sedangkan kesalahan yang disembunyikan akan muncul
kembali dalam bentuk yang lebih merugikan.

**Ta'awun.** Penanganan gangguan dikerjakan berpasangan. Rekan pasangan
bukan penonton: ia berkewajiban memeriksa apa yang kalian kerjakan, dan
bersedia dimintai pertanggungjawaban bersama. Kerja berpasangan menutup
kelemahan yang paling umum pada administrator pemula, yaitu terlalu yakin
pada pekerjaannya sendiri.

**Menjaga harta (hifz al-mal).** Konfigurasi jaringan adalah harta
organisasi yang tidak kasatmata. Mencadangkannya secara teratur, dan
menguji bahwa cadangan itu benar-benar dapat dipulihkan, termasuk menjaga
harta. Cadangan yang tidak pernah diuji pemulihannya bukan cadangan,
melainkan harapan.

## 0.7 Contoh kasus

**Kasus.** Pada Jumat sore, seorang staf meminta kalian membuka akses ke
satu folder bersama, sebab ia harus menyelesaikan laporan sebelum Senin.
Atasan kalian sedang tidak di tempat, dan pesan singkatnya tidak dibalas.
Staf itu mendesak, dan mengatakan bahwa izin sudah diberikan secara lisan.

**Pertanyaan.** Apa yang kalian lakukan?

**Pembahasan.** Ada tiga kepentingan yang bertemu pada kasus ini: kebutuhan
staf yang mendesak, wewenang atasan yang tidak dapat diwakili, dan tanggung
jawab kalian atas keamanan data.

Langkah yang bijak:

1. Catat permintaan itu secara tertulis, berisi nama staf, waktu, folder
   yang diminta, dan alasannya.
2. Berikan akses paling kecil yang masih memungkinkan pekerjaan itu selesai,
   bukan akses penuh ke seluruh folder bersama.
3. Tetapkan batas waktu akses, misalnya sampai Senin pagi, dan tuliskan
   pada catatan yang sama.
4. Laporkan kepada atasan pada hari kerja berikutnya, dan minta
   pengesahan atas tindakan yang sudah kalian ambil.

Langkah itu memenuhi ketiga kepentingan sekaligus: pekerjaan staf selesai,
wewenang atasan tidak dilangkahi, dan jejaknya tertulis sehingga kalian
tidak sendirian bila kelak ada pemeriksaan.

Kesalahan yang harus dihindari: menolak tanpa solusi, atau mengiyakan tanpa
catatan. Keduanya sama-sama merugikan, hanya berbeda arahnya.

## 0.8 Latihan

1. Sebutkan tiga akibat yang timbul bila jaringan tidak terdokumentasi,
   lalu urutkan menurut besar kerugiannya. Jelaskan alasan urutan kalian.
2. Beban praktik mata kuliah ini 5.610 menit. Bila tersebar pada 14
   pertemuan, berapa menit praktik per pertemuan? Berapa jam?
3. Ambil satu unit kompetensi SKKNI pada bagian 0.3, lalu tuliskan dengan
   kata-kata sendiri apa yang akan kalian kerjakan bila unit itu diberikan
   sebagai tugas.
4. Sebutkan dua contoh perubahan konfigurasi yang memerlukan rencana
   pengembalian tertulis, dan dua contoh yang tidak memerlukannya.
5. Menurut kalian, mengapa kerja berpasangan diwajibkan pada penanganan
   gangguan? Berikan satu alasan teknis dan satu alasan nonteknis.
6. Buat struktur folder laporan kalian sendiri, berbeda dari contoh pada
   bagian 0.4, lalu jelaskan kelebihannya.
7. Tuliskan satu pengalaman kalian, atau orang yang kalian kenal, tentang
   layanan yang rusak karena perubahan yang tidak dicatat. Apa yang
   seharusnya dilakukan?

**Rubrik penilaian latihan.** Tiap nomor dinilai pada tiga tingkat.
*Tepat*: jawaban benar, disertai alasan yang dapat dipertanggungjawabkan.
*Sebagian*: jawaban benar tanpa alasan, atau alasan ada tetapi arahnya
kurang tepat. *Belum*: jawaban keliru, atau menyalin pernyataan buku tanpa
pengolahan. Latihan ini bersifat formatif, nilainya tidak masuk nilai
akhir, tetapi menjadi bahan refleksi yang dikumpulkan pada pertemuan
berikutnya.

## Rangkuman

- Mata kuliah ini melatih tiga hal sekaligus: merancang, mengelola, dan
  memulihkan jaringan.
- Porsi praktik 68,7 persen, sehingga kehadiran dan penyelesaian tugas
  praktikum menentukan keberhasilan kalian lebih besar daripada kehadiran
  kuliah teori.
- Unit kompetensi SKKNI dan skema Junior Network Administrator menjadi
  acuan isi, sehingga yang kalian latih adalah kemampuan kerja, bukan
  sekadar topik kuliah.
- Etika profesi diwujudkan pada batas wewenang, dokumentasi perubahan, dan
  kerahasiaan.
- Nilai AIK hadir sebagai amanah, kejujuran, ta'awun, dan menjaga harta.

## Glosarium

| Istilah | Arti |
|---|---|
| Amanah | Kepercayaan yang wajib dijaga, pada konteks ini berupa aset dan data milik pihak lain |
| Autonomous system | Sekumpulan jaringan yang dikelola oleh satu organisasi dengan kebijakan routing sendiri |
| Bukti kerja | Hasil nyata yang dikumpulkan sebagai dasar penilaian |
| Cadangan | Salinan konfigurasi atau data yang disimpan untuk keperluan pemulihan |
| CPMK | Capaian pembelajaran mata kuliah |
| SKKNI | Standar Kompetensi Kerja Nasional Indonesia |
| Sub-CPMK | Capaian pembelajaran yang lebih rinci, ditetapkan per pertemuan |
| Ta'awun | Tolong-menolong dalam kebaikan, pada konteks ini kerja berpasangan saat menangani gangguan |

## Rujukan

| Sumber | Kedudukan | Status |
|---|---|---|
| Kurikulum Prodi Teknologi Informasi D3, UNIMMA | Acuan bahan kajian dan beban | ✓ dokumen program studi |
| Kepmenaker Nomor 321 Tahun 2016 | Acuan unit kompetensi | ⏳ status berlakunya perlu dicek |
| Skema Sertifikasi Junior Network Administrator, LSP Informatika | Acuan unit yang diujikan | ✓ dokumen LSP |
| RPS KPT0502324 | Acuan capaian dan penilaian | ✓ tersusun pada folder kerja ini |
