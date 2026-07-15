# 🌐 eBook MATA KULIAH JARINGAN KOMPUTER

### Modul Pembelajaran Berbasis Sub-CPMK untuk Program Studi D3 Teknik Informatika

![Status](https://img.shields.io/badge/Status-Ebook%20Pembelajaran-blue)
![Tingkat](https://img.shields.io/badge/Tingkat-D3%20Vokasi-green)
![SKS](https://img.shields.io/badge/SKS-3-orange)
![Semester](https://img.shields.io/badge/Semester-III%20Gasal-purple)
![Kurikulum](https://img.shields.io/badge/Kurikulum-KUR--D3TI--2026-blueviolet)

### 🎓 Universitas Muhammadiyah Magelang (UNIMMA)
### Program Studi D3 Teknik Informatika

| Atribut | Nilai |
|:---|:---|
| **Kode Mata Kuliah** | `OBE0502401` |
| **Kelompok MK** | Inti - Wajib Prodi |
| **CPL Pendukung** | CPL-3 |
| **Prasyarat** | - (tidak ada) |
| **Semester** | 3 (Gasal) |

---

## 📖 Deskripsi Mata Kuliah

Mata kuliah ini membahas konsep jaringan komputer modern: model **OSI dan TCP/IP**, IP addressing (IPv4/IPv6), routing, switching, DNS, HTTP/HTTPS, dasar konfigurasi router dan switch (Mikrotik/Cisco), wireless networking, dan dasar troubleshooting. Praktikum menggunakan simulator (Packet Tracer) dan perangkat fisik di lab. Bekal untuk peran junior network admin dan persiapan sertifikasi **MTCNA/CCNA**.

---

## 🎯 Capaian Pembelajaran Mata Kuliah (CPMK)

| Kode | Rumusan CPMK | CPL |
|:---:|:---|:---:|
| **CPMK-1** | Menjelaskan model OSI dan TCP/IP serta keterkaitan antar lapisan | CPL-3 |
| **CPMK-2** | Menerapkan IP addressing dan subnetting untuk perancangan jaringan | CPL-3 |
| **CPMK-3** | Mengonfigurasi routing dan switching pada perangkat jaringan | CPL-3 |
| **CPMK-4** | Mengonfigurasi layanan jaringan (DNS, DHCP, NAT) dan wireless | CPL-3 |
| **CPMK-5** | Mendiagnosis dan memperbaiki gangguan jaringan dasar | CPL-3 |

---

## 📋 Pemetaan Sub-CPMK ke Bab eBook

| Bab | Kode Sub-CPMK | Rumusan Sub-CPMK | CPMK | Tahap / Bahan Kajian | File |
|:---:|:---:|:---|:---:|:---|:---|
| **1** | **1.1** | Mhs mampu menjelaskan fungsi 7 lapisan OSI & 4 lapisan TCP/IP, melalui studi kasus pengiriman data, runtut & benar | CPMK-1 | OSI, TCP/IP, topologi (1 pertemuan) | [jarkom-bab-1-foundation.md](./jarkom-bab-1-foundation.md) |
| **1** | **1.2** | Mhs mampu menganalisis enkapsulasi-dekapsulasi antar lapisan dengan tangkapan paket Wireshark, hingga PDU tiap lapisan teridentifikasi tepat | CPMK-1 | PDU, header, framing (1 pertemuan) | (sama) |
| **2** | **2.1** | Mhs mampu menjelaskan struktur pengalamatan IPv4 & IPv6 (kelas, netmask, CIDR) beserta perannya | CPMK-2 | IP kelas, CIDR, IPv6 (1 pertemuan) | [jarkom-bab-2-ip-subnetting.md](./jarkom-bab-2-ip-subnetting.md) |
| **2** | **2.2** | Mhs mampu menghitung subnet IPv4 metode VLSM berdasarkan kebutuhan host studi kasus, hingga blok teralokasi tanpa tumpang tindih | CPMK-2 | Subnetting, FLSM/VLSM (1 pertemuan) | (sama) |
| **3** | **3.1** | Mhs mampu mengonfigurasi switching, VLAN, & inter-VLAN routing di Cisco Packet Tracer, hingga host antar-VLAN terhubung sesuai kebijakan | CPMK-3 | Switch, VLAN, trunking (1 pertemuan) | [jarkom-bab-3-switching-routing.md](./jarkom-bab-3-switching-routing.md) |
| **3** | **3.2** | Mhs mampu mengonfigurasi static & default routing pada multi-router Packet Tracer, hingga tabel routing terbentuk & ping berhasil | CPMK-3 | Cisco IOS, static route (1 pertemuan) | (sama) |
| **3** | **3.3** | Mhs mampu menerapkan dynamic routing OSPF single-area pada jaringan skala menengah, hingga konvergen tanpa routing loop | CPMK-3 | OSPF, neighbor adjacency (1 pertemuan) | (sama) |
| **4** | **4.1** | Mhs mampu mengonfigurasi DHCP & DNS pada router/server, hingga klien dapat IP otomatis & resolusi nama berhasil | CPMK-4 | DHCP pool, DNS record (1 pertemuan) | [jarkom-bab-4-network-services.md](./jarkom-bab-4-network-services.md) |
| **4** | **4.2** | Mhs mampu mengonfigurasi NAT/PAT pada router gateway, hingga host privat mengakses jaringan publik | CPMK-4 | NAT statis/dinamis, PAT (1 pertemuan) | (sama) |
| **4** | **4.3** | Mhs mampu mengonfigurasi jaringan nirkabel (SSID, WPA2) pada access point, hingga klien terasosiasi & terkoneksi | CPMK-4 | Wireless, SSID, WPA2 (1 pertemuan) | (sama) |
| **5** | **5.1** | Mhs mampu mengonfigurasi Mikrotik RouterOS (firewall, bandwidth) sesuai skenario jaringan kecil | CPMK-5 | RouterOS, firewall, queue (1 pertemuan) | [jarkom-bab-5-mikrotik-troubleshooting.md](./jarkom-bab-5-mikrotik-troubleshooting.md) |
| **5** | **5.2** | Mhs mampu mendiagnosis & memperbaikan gangguan konektivitas berlapis dengan ping/traceroute/sniffer, hingga layanan pulih sesuai indikator | CPMK-5 | Troubleshooting OSI, tools (1 pertemuan) | (sama) |

---

## 🧭 Filosofi Pembelajaran

> 🕌 *"Dan Kami jadikan bagi kamu pendengaran, penglihatan, dan hati nurani, agar kamu bersyukur."*
> *(QS. An-Nahl [16]: 78)*

Ayat ini mengingatkan bahwa kemampuan berkomunikasi (termasuk komunikasi data antar komputer via jaringan) adalah nikmat Allah yang harus disyukuri dan dimanfaatkan untuk kebaikan. Jaringan komputer, dalam perspektif Islam, adalah wasilah (perantara) **silaturahim digital** yang menghubungkan umat manusia lintas batas geografis. Setiap praktisi jaringan yang membangun infrastruktur komunikasi yang andal, sejatinya turut memperkuat tali ukhuwah antar Muslim dan antar umat manusia.

---

## 📑 Daftar Bab

1. [Bab 1: Foundation Jaringan (OSI, TCP/IP, Wireshark)](jarkom-bab-1-foundation.md)
2. [Bab 2: IP Addressing & Subnetting (IPv4, IPv6, VLSM)](jarkom-bab-2-ip-subnetting.md)
3. [Bab 3: Switching & Routing (VLAN, Static Route, OSPF)](jarkom-bab-3-switching-routing.md)
4. [Bab 4: Network Services (DHCP, DNS, NAT, Wireless)](jarkom-bab-4-network-services.md)
5. [Bab 5: Mikrotik RouterOS & Troubleshooting](jarkom-bab-5-mikrotik-troubleshooting.md)

---

### ✅ eBook LENGKAP - Semua 5 Bab Tersedia

---

> 💡 **Cara membaca eBook ini:**
>
> - Diagram interaktif berbasis **Mermaid** akan tampil otomatis di GitHub, GitLab, VS Code (dengan ekstensi Markdown Preview Mermaid), dan Obsidian.
> - Blok `💡`, `⚠️`, `🎯`, `💻`, `🕌` adalah callout tematik (tips, peringatan, tujuan belajar, lab praktik, refleksi islami).
> - Lab konfigurasi Cisco IOS dan Mikrotik RouterOS dapat diikuti di **Cisco Packet Tracer** (gratis, download dari NetAcad) dan **Mikrotik CHR** (gratis, jalankan di VirtualBox).
> - eBook disusun **satu file MD per bab**, lengkap dan siap dipakai.
