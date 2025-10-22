---
title: "Test Scenario, Test Case and Bug Report"
date: 2025-09-01 08:30:00
categories: [Software Testing and Quality Assurance]
tags: [STQA]
image: /assets/images/test-scenario.png
---

# Test Scenario, Test Case, dan Bug Report

## Pengertian
**Test Scenario**, **Test Case**, dan **Bug Report** adalah tiga elemen penting dalam proses pengujian perangkat lunak yang saling melengkapi.  
Ketiganya digunakan untuk memastikan bahwa aplikasi berjalan sesuai kebutuhan dan bebas dari kesalahan.

- **Test Scenario**: gambaran umum tentang apa yang diuji.  
- **Test Case**: langkah-langkah detail pengujian, termasuk input, proses, dan hasil yang diharapkan.  
- **Bug Report**: laporan kesalahan yang ditemukan selama pengujian.

---

## Test Scenario
Test scenario menjelaskan *apa yang akan diuji* untuk memastikan fungsi aplikasi berjalan dengan benar.  
Setiap skenario memiliki **ID Scenario**, **deskripsi**, dan **fitur atau modul yang diuji**.

**Contoh Scenario (Aplikasi BMI):**
- **TS001**: Periksa fungsi slider input berat dan tinggi.  
- **TS002**: Periksa hasil perhitungan dan klasifikasi BMI.  
- **TS003**: Periksa fungsi penyimpanan history BMI.

---

## Test Case
Test case menjelaskan *bagaimana pengujian dilakukan*.  
Berisi langkah-langkah pengujian, data uji, hasil yang diharapkan, dan hasil aktual.  
Beberapa elemen penting dalam test case adalah:

- **ID Test Case**: penanda unik.  
- **Deskripsi**: ringkasan tujuan uji.  
- **Precondition**: kondisi awal sebelum pengujian.  
- **Test Steps**: langkah-langkah detail.  
- **Expected Result**: hasil yang diharapkan.  
- **Actual Result**: hasil nyata setelah diuji.  
- **Status**: Pass / Fail.

**Contoh Test Case (Aplikasi BMI):**
- **TC001**: Verifikasi slider berat menampilkan nilai sesuai posisi (misalnya 60 kg).  
- **TC003**: Verifikasi hasil perhitungan BMI sesuai rumus (kg/m²).  
- **TC005–TC007**: Uji kategori hasil BMI (Underweight, Normal, Overweight, Obese).  
- **TC008–TC009**: Uji penyimpanan data BMI ke halaman *history* tanpa kehilangan data sebelumnya.

---

## Bug Report
Bug report adalah laporan formal mengenai kesalahan atau kegagalan fungsi yang ditemukan selama pengujian.  
Laporan ini membantu tim pengembang memahami dan memperbaiki masalah.

**Elemen Utama Bug Report:**
- **Bug ID dan Title**: identitas dan ringkasan bug.  
- **Steps to Reproduce**: langkah untuk menampilkan bug.  
- **Expected Result** vs **Actual Result**.  
- **Severity dan Priority**: tingkat keparahan dan prioritas perbaikan.  
- **Reporter & Assignee**: siapa yang melaporkan dan siapa yang memperbaiki.

**Contoh Bug Report (Aplikasi BMI):**  
- **Bug Title:** Perhitungan BMI salah saat input berat 60kg dan tinggi 170cm.  
- **Bug ID:** BMI-001  
- **Steps:** Masukkan Berat=60, Tinggi=170, klik *Hitung*.  
- **Expected:** BMI = 20.8  
- **Actual:** BMI = 12.5  
- **Severity:** Major (High)  
- **Priority:** P2 - High  
- **Assignee:** Developer  
- **Reporter:** QA Team  

---

## Klasifikasi Bug

**Severity (Dampak Bug):**
- *Low:* tidak memengaruhi fungsi utama.  
- *Minor:* menyebabkan ketidaknyamanan kecil.  
- *Major:* fungsi utama terganggu namun aplikasi masih berjalan.  
- *Critical:* menyebabkan aplikasi gagal total.

**Priority (Urgensi Perbaikan):**
- *P1 - Urgent:* harus segera diperbaiki.  
- *P2 - High:* penting, memengaruhi banyak pengguna.  
- *P3 - Medium:* bisa diperbaiki di rilis berikutnya.  
- *P4 - Low:* bug kecil atau kosmetik.

---

## Cara Menghindari Bug
1. **Pahami Persyaratan:** seluruh tim harus memahami kebutuhan sistem dengan jelas.  
2. **Unit Testing:** deteksi bug lebih awal di tahap pengembangan.  
3. **Code Review:** lakukan pemeriksaan kode secara rutin.  
4. **Rencana Pengujian:** buat test plan yang lengkap dan realistis.  
5. **Automated Testing:** gunakan alat otomatis untuk pengujian cepat dan berulang.  
6. **Kolaborasi Tim:** jaga komunikasi antara pengembang dan penguji.

---

## Kesimpulan
Test scenario, test case, dan bug report merupakan komponen penting dalam proses QA.  
Melalui ketiganya, tim dapat menemukan dan memperbaiki bug secara sistematis sehingga perangkat lunak menjadi lebih **stabil, andal, dan siap digunakan pengguna.**

---
