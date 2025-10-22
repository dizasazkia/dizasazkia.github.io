---
title: "Pengantar Unit Testing"
date: 2025-09-07 07:30:00
categories: [Software Testing and Quality Assurance]
tags: [STQA]
image: /assets/images/unit-testing.png
---

# Pengantar Unit Testing 

## Pengertian
**Unit Testing** adalah jenis pengujian perangkat lunak yang berfokus pada **unit terkecil dalam sistem**, seperti fungsi, method, atau class.  
Tujuannya adalah memastikan setiap komponen bekerja dengan benar secara **terpisah**, tanpa bergantung pada bagian lain dari sistem.

Unit testing biasanya menjadi **tahap awal pengujian** sebelum dilanjutkan ke integration testing, functional testing, atau end-to-end testing.

---

## Analogi
Unit testing dapat dianalogikan seperti **memeriksa setiap komponen mobil secara terpisah** sebelum dirakit menjadi satu mobil utuh.  
Jika setiap komponen lolos uji, maka sistem yang terbentuk juga akan berkualitas tinggi.  
Sebaliknya, jika ada kesalahan, kita tahu masalahnya berasal dari unit tertentu, bukan keseluruhan sistem.

---

## Manfaat Unit Testing
1. **Mendeteksi bug lebih awal** sebelum kode diintegrasikan.  
2. **Meningkatkan kualitas kode** dengan memastikan fungsionalitas berjalan sesuai harapan.  
3. **Menghemat waktu dan biaya** karena perbaikan dini lebih efisien.  
4. **Mempermudah refactoring** tanpa takut merusak fungsionalitas lama.  
5. **Memberikan dokumentasi hidup** karena test case dapat menunjukkan cara kerja fungsi secara nyata.  
6. **Meningkatkan kepercayaan diri developer** saat melakukan perubahan kode.

---

## Pola Dasar Unit Testing (AAA Pattern)
Pendekatan umum dalam menulis unit test terdiri dari tiga tahap:

1. **Arrange** — Menyiapkan kondisi awal, data, dan objek yang diperlukan.  
2. **Act** — Menjalankan fungsi atau metode yang akan diuji.  
3. **Assert** — Memverifikasi hasil eksekusi dengan nilai yang diharapkan.

Pola ini membantu menjaga struktur test tetap jelas dan mudah dibaca.

---

## Framework Unit Testing Populer

### 1. JUnit 5 (Java)
Framework standar untuk pengujian di ekosistem Java.  
**Keunggulan:**  
- Integrasi penuh dengan IDE dan build tools.  
- Struktur berbasis anotasi.  
- Ekosistem yang matang dan luas.

**Cocok digunakan untuk:**  
Java, Kotlin, dan Scala.

---

### 2. Jest (JavaScript)
Framework testing buatan Meta, populer di dunia frontend.  
**Keunggulan:**  
- Konfigurasi minimal (*zero-config*).  
- Mendukung *snapshot testing*.  
- Cepat dan mudah digunakan.

**Cocok digunakan untuk:**  
React, Node.js, TypeScript, dan proyek JavaScript modern.

---

### 3. Pytest (Python)
Framework sederhana namun kuat untuk berbagai jenis proyek Python.  
**Keunggulan:**  
- Sintaks mudah dibaca dan ringkas.  
- Mendukung fixtures dan reporting yang detail.  
- Dapat digunakan untuk aplikasi web, API, maupun data science.

---

## Contoh Implementasi
Beberapa contoh uji sederhana yang dapat dibuat dengan framework di atas:
- **Shopping Cart Test (Pytest):** memeriksa penambahan dan penghapusan item dari keranjang belanja.  
- **Bank Account Test (JUnit):** menguji fungsi setoran dan penarikan agar saldo sesuai harapan.

---

## Kesimpulan
Unit testing merupakan **fondasi penting dalam pengujian perangkat lunak**.  
Dengan menerapkannya secara konsisten, developer dapat menulis kode yang lebih **andal, mudah dipelihara, dan minim bug**.  
Framework seperti JUnit, Jest, dan Pytest membantu mempercepat proses ini dan meningkatkan kualitas hasil pengembangan.

---
