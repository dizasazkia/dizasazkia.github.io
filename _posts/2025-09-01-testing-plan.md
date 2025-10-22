---
title: "Testing Plan"
date: 2025-09-01 07:30:00
categories: [Software Testing and Quality Assurance]
tags: [STQA]
image: /assets/images/testing-plan.png
---

# Test Plan

## Pengertian
**Test Plan** adalah dokumen panduan yang menjelaskan bagaimana proses pengujian perangkat lunak dilakukan.  
Di dalamnya terdapat ruang lingkup, strategi, sumber daya (tim, alat, data uji), dan jadwal pelaksanaan.  
Tujuannya agar pengujian berjalan **terarah, efisien, dan terdokumentasi dengan baik.**

---

## Tujuan
- Menjelaskan apa yang diuji dan bagaimana cara mengujinya.  
- Memastikan perangkat lunak mencapai kualitas yang diterima pengguna.  
- Mengoptimalkan waktu, biaya, dan tenaga.  
- Menjadi dokumentasi referensi untuk proyek selanjutnya.

---

## Komponen Utama (IEEE 829)

**1. Plan Identifier**  
Kode unik untuk membedakan dokumen antar proyek atau versi, agar mudah dikelola dan direvisi.

**2. References**  
Berisi dokumen atau standar pendukung seperti spesifikasi sistem dan pedoman QA.

**3. Introduction**  
Menjelaskan tujuan, ruang lingkup, dan fokus pengujian secara umum.

**4. Test Items**  
Fitur, modul, atau komponen perangkat lunak yang menjadi objek pengujian.

**5. Software Risk Issues**  
Identifikasi risiko yang mungkin muncul, misalnya fitur kompleks, integrasi baru, atau kebutuhan yang tidak jelas.

**6. Features to be Tested / Not to be Tested**  
Menentukan fitur yang akan diuji dan fitur yang dikecualikan beserta alasannya (misalnya sudah stabil atau tidak termasuk rilis).

**7. Approach**  
Menjelaskan strategi pengujian: jenis testing (unit, integration, system, acceptance), metode (black-box atau white-box), dan teknik (manual atau otomatis).

---

## Kriteria Pengujian

**Pass Criteria**  
- Semua test case berjalan sesuai harapan.  
- Tidak ada bug kritis.  
- Fitur berfungsi sesuai spesifikasi.

**Fail Criteria**  
- Test case gagal atau bug mayor muncul.  
- Perilaku sistem tidak sesuai spesifikasi.

Kriteria ini memastikan hasil uji dapat dievaluasi secara objektif.

---

## Kriteria Tambahan
**Suspension Criteria:** pengujian dihentikan sementara jika ditemukan bug besar.  
**Resumption Criteria:** pengujian dilanjutkan kembali setelah masalah diperbaiki.

---

## Komponen Pendukung
- **Test Deliverables:** hasil nyata dari pengujian seperti laporan bug dan test summary.  
- **Environmental Needs:** konfigurasi hardware, software, dan data uji.  
- **Responsibilities:** pembagian peran seperti tester, QA lead, dan developer.  
- **Schedule:** jadwal mulai, periode eksekusi, retest, dan approval hasil.  
- **Glossary & Approvals:** daftar istilah dan tanda tangan pihak terkait.

---

## Kesimpulan
Test Plan menjadi acuan utama dalam pengujian perangkat lunak.  
Dengan perencanaan yang baik, proses testing berjalan sistematis dan efisien, serta menghasilkan perangkat lunak yang berkualitas dan sesuai kebutuhan pengguna.

---

