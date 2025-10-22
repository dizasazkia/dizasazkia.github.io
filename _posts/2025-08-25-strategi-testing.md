---
title: "Strategi Testing"
date: 2025-08-25 07:30:00
categories: [Software Testing and Quality Assurance]
tags: [STQA]
image: /assets/images/strategi-testing.png
---

# Testing Strategy

## Pengantar
Dalam pengembangan perangkat lunak, **testing (pengujian)** merupakan tahap penting dalam **Software Development Life Cycle (SDLC)**.  
Tahap ini memastikan perangkat lunak yang dikembangkan **berfungsi sesuai kebutuhan pengguna**, bebas dari bug, dan memiliki kualitas yang tinggi.

---

## Apa Itu Testing?
**Testing** adalah proses untuk **mengevaluasi produk perangkat lunak** agar sesuai dengan kebutuhan fungsional dan non-fungsional.  
Tujuannya adalah **menemukan kesalahan (bug)** sedini mungkin dan memastikan produk siap digunakan sebelum dirilis ke pengguna.

Testing juga berfungsi untuk:
- Mengurangi risiko kegagalan sistem.  
- Menjamin keamanan dan kestabilan aplikasi.  
- Meningkatkan kepercayaan stakeholder.  
- Menurunkan biaya perbaikan jangka panjang.  
- Meningkatkan pengalaman pengguna.  

---

## Software Testing Life Cycle (STLC)
**Software Testing Life Cycle (STLC)** adalah proses sistematis yang mengikuti beberapa fase untuk memastikan bahwa perangkat lunak yang diuji memenuhi semua persyaratan dan bebas dari cacat.

### Tahapan STLC meliputi:
1. **Test Planning**  
   - Menentukan strategi pengujian.  
   - Menetapkan lingkungan pengujian.  
   - Mengidentifikasi test case dan estimasi waktu.  
   - Menetapkan peran dan tanggung jawab tim.  

2. **Test Design**  
   - Menulis test case dan skenario uji.  
   - Membuat data pengujian.  
   - Memvalidasi hasil yang diharapkan.  
   - Menyusun *Requirement Traceability Matrix (RTM)*.

3. **Test Execution**  
   - Menjalankan pengujian berdasarkan test case.  
   - Meliputi *Unit Testing*, *Integration Testing*, *System Testing*, dan *Acceptance Testing*.  

4. **Test Reporting & Analysis**  
   - Menganalisis hasil uji dan mencatat bug.  
   - Menilai apakah sistem memenuhi kebutuhan fungsional dan non-fungsional.  
   - Menyusun rekomendasi perbaikan dan laporan hasil pengujian.  

---

## Klasifikasi Software Testing

### Berdasarkan Abstraksi
1. **Unit Testing**  
   Menguji komponen perangkat lunak terkecil seperti fungsi, metode, atau kelas secara terpisah.  
   *Contoh:* Menguji fungsi perhitungan diskon agar hasilnya akurat.  

2. **Integration Testing**  
   Menguji interaksi antar modul untuk memastikan komunikasi berjalan baik.  
   *Contoh:* Memastikan modul login dan profil pengguna saling terhubung dengan benar.  

3. **System Testing**  
   Menguji keseluruhan sistem sebagai satu kesatuan untuk memastikan semua fitur berjalan sesuai kebutuhan.  
   *Contoh:* Menguji aplikasi e-commerce agar mampu menangani ribuan pengguna dan transaksi.  

4. **Acceptance Testing**  
   Dilakukan oleh klien atau end-user untuk memvalidasi apakah sistem dapat diterima dan sesuai kebutuhan bisnis.  
   *Contoh:* Klien menguji aplikasi sebelum peluncuran ke pasar.  

---

### Berdasarkan Fungsi
1. **Functional Testing**  
   Memverifikasi apakah perangkat lunak bekerja sesuai kebutuhan fungsional.  
   *Contoh:* Menguji proses login, pembayaran, atau pendaftaran pengguna.  

2. **Non-Functional Testing**  
   Menguji aspek seperti performa, keamanan, reliabilitas, dan skalabilitas.  
   *Contoh:* Menguji kecepatan website saat pengguna meningkat drastis (misalnya saat *flash sale*).  

---

### Berdasarkan Domain
1. **Performance Testing**  
   Menguji kecepatan dan stabilitas aplikasi di bawah beban tinggi.  
   *Contoh:* Memastikan website tetap stabil saat banyak pengguna aktif bersamaan.  

2. **Security Testing**  
   Menguji apakah aplikasi aman dari ancaman seperti **SQL Injection** atau **Cross-Site Scripting (XSS)**.  
   *Contoh:* Memastikan data pengguna terlindungi dan akses hanya diberikan kepada pihak berwenang.  

3. **Usability Testing**  
   Menilai kemudahan penggunaan aplikasi oleh pengguna akhir.  
   *Contoh:* Menguji apakah pengguna dapat dengan mudah menemukan fitur dan memahami navigasi aplikasi.  

---

### Berdasarkan Struktur
1. **Black-Box Testing**  
   Penguji tidak mengetahui struktur internal kode. Fokus pada fungsi dan output sistem.  
   - **Kelebihan:** Tidak perlu memahami kode, relevan bagi end-user.  
   - **Kekurangan:** Cakupan terbatas dan sulit menemukan bug logika internal.  

2. **White-Box Testing**  
   Penguji memahami kode dan struktur internal program. Fokus pada logika dan alur program.  
   - **Kelebihan:** Menjamin cakupan kode lebih luas dan menemukan bug tersembunyi.  
   - **Kekurangan:** Membutuhkan waktu lebih lama dan pemahaman teknis tinggi.  

---

## Kesimpulan
**Software Testing** merupakan tahap krusial dalam proses **Software Development Life Cycle (SDLC)**.  
Testing memastikan perangkat lunak **berfungsi dengan baik, aman, efisien, dan memenuhi kebutuhan pengguna akhir**.  

Dengan penerapan strategi pengujian yang tepat, pengembang dapat menghasilkan produk berkualitas tinggi yang **minim bug dan disukai pengguna**.

---

*Disusun berdasarkan materi presentasi Kelompok 1 — Mata Kuliah Software Testing & Quality Assurance, Universitas Hasanuddin.*
