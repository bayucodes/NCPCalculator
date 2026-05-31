# Kalkulator NCP (Nutritional Care Process)

[![License: MIT](https://img.shields.io/badge/License-MIT-teal.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Aplikasi kalkulator berbasis web interaktif untuk mempermudah perhitungan proses asuhan gizi klinik bagi praktisi kesehatan, dietisien, maupun mahasiswa gizi. Alat ini dikembangkan dengan mengacu pada standar rumus gizi klinik Kementerian Kesehatan RI dan standar internasional (WHO).

## 🧑‍💻 Dikembangkan Oleh
Aplikasi ini dirancang dan dikembangkan oleh:
* **Muhamad Adji Bayu Saputra, S.Tr.Gz.**

---

## ✨ Fitur Utama & Modul Perhitungan

Kalkulator ini dirancang secara sistematis ke dalam beberapa kategori utama untuk mencakup asuhan gizi dewasa hingga anak:

1. **Antropometri & Status Gizi**
   * Perhitungan IMT / BMI (Body Mass Index) lengkap dengan indikator visual.
   * Berat Badan Ideal (BBI) menggunakan rumus Broca yang dimodifikasi.
   * Estimasi BB berdasarkan %LiLA (Lingkar Lengan Atas) Frisancho untuk pasien *bedrest*.
   * Estimasi Tinggi Badan (TB) Chumlea dari Tinggi Lutut.
   * Estimasi TB menggunakan Rentang Lengan (*Arm Span*).

2. **Kebutuhan Gizi & Energi Gizi Klinik**
   * **Mifflin-St Jeor:** Rumus standar untuk pasien rawat jalan atau kondisi obesitas.
   * **Harris-Benedict:** Rumus konvensional yang diintegrasikan dengan Faktor Aktivitas (FA) dan Faktor Stres (FS).
   * **Parenteral / Formula Instan:** Perhitungan cepat (25-30 kkal/kg) untuk kondisi klinis akut.

3. **Kondisi Pasien Khusus (Penyakit Dalam)**
   * **Gagal Ginjal (GGK / CKD):** Rumus spesifik untuk pasien Non-Dialisis, Hemodialisis (HD), dan CAPD.
   * **Sirosis Hati:** Manajemen perhitungan energi khusus penyakit liver.
   * **Luka Burn / Bakar (Curreri):** Perhitungan hipermetabolisme ekstrem pada pasien trauma luka bakar.

4. **Anak & Pediatri**
   * **Catch-up Growth (Kejar Tumbuh):** Kalkulasi target kalori anak dengan kondisi gizi kurang/buruk.
   * **Schofield / WHO:** Perhitungan energi basal terkalibrasi khusus anak-anak.

5. **Kelebihan Teknis & Antarmuka**
   * 🌙 Dukungan Penuh **Dark Mode** & **Light Mode** untuk kenyamanan mata pengguna saat bekerja di klinik/rumah sakit.
   * 📱 Desain **Fully Responsive** yang ramah digunakan melalui *smartphone*, tablet, maupun desktop.
   * 🧮 Dilengkapi pembagian **Makronutrien otomatis** (Karbohidrat, Protein, Lemak) beserta penjelasan langkah per langkah (*Step-by-step*).

---

## 🚀 Cara Menjalankan Project

Aplikasi ini dibuat murni menggunakan teknologi *frontend vanilla* sehingga tidak memerlukan instalasi *backend* atau *framework* yang rumit.

1. **Clone repositori ini:**
```bash
   git clone https://github.com/bayucodes/NCPCalculator.git