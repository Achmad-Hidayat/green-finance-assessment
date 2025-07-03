# 🧪 ETL Assessment – Green Finance (Premium Batch 1)

## Tugas Analisis Green Finance

Hai! Kami dari **Kelompok 1 Premium Class Batch 1** telah menjalankan sebuah misi menarik: menganalisis proyek-proyek energi hijau Indonesia menggunakan Python.

### 👥 Anggota Kelompok:

1. Achmad (09.011.DB2025)
2. Ayi (09.046.DB2025)
3. Nasri (10.003.DB2025)
4. Ulandari (10.041.DB2025)

Tugas ini adalah bagian dari pelatihan **ECO Techno Leaders**, dengan tujuan membekali peserta kemampuan teknis dan pemahaman terhadap konsep *Green Finance*. Berikut ini adalah hasil analisis kami, yang kami kerjakan dengan penuh semangat dan kerja sama tim.

---

## 💸🌱 Apa Itu Green Finance?

**Green Finance** adalah sistem pembiayaan yang mendukung proyek-proyek yang ramah lingkungan dan berkelanjutan, seperti pembangunan PLTS, pengelolaan limbah, dan transportasi hijau. Tujuannya adalah mendukung pertumbuhan ekonomi sekaligus menjaga keberlanjutan lingkungan.

Di tengah krisis iklim global, pendekatan ini penting bagi Indonesia untuk mendukung transisi energi bersih dan pencapaian Net Zero Emissions.

---

## 🎯 Latar Belakang & Tujuan Tugas

Program ini bertujuan:

* Mengembangkan keterampilan analisis data berbasis Python
* Membekali peserta dengan kemampuan teknis menilai proyek energi terbarukan
* Menghasilkan alat bantu penilaian proyek berbasis data

Kami diberikan 5 dataset:

* Lingkungan (Environmental)
* Sosial (Social)
* Ekonomi (Economic)
* Keuangan (Financial)
* Spasial (Geospatial)

Dan diminta untuk menjawab 7 soal + 1 bonus menggunakan Python dengan logika pemrograman dasar.

---

## 🏞️ Tantangan Green Finance di Indonesia

Implementasi Green Finance menghadapi berbagai tantangan:

* 🌱 Dampak lingkungan yang harus diukur secara objektif
* 🤝 Risiko sosial seperti konflik lahan
* 📈 Kelayakan ekonomi dan ketertarikan investor

Sayangnya, penilaian proyek sering dilakukan manual. Padahal data tersedia di berbagai sumber. Oleh karena itu, tugas ini hadir untuk:

* Menyatukan data lintas dimensi
* Menggunakan Python untuk membantu pengambilan keputusan

---

## ✅ Output Tugas

Setiap soal menunjukkan analisis data konkret:

* 📌 **Soal 1**: Menghitung efisiensi CO₂ per juta rupiah proyek PLTS
* 📌 **Soal 2**: Rata-rata CO₂ dari proyek PLTM
* 📌 **Soal 3**: Cek status sosial proyek melalui input interaktif
* 📌 **Soal 4**: Menyaring proyek berdaya tarik tinggi & konflik rendah
* 📌 **Soal 5**: Menghitung total investasi lokasi efisien
* 📌 **Soal 6**: Fungsi modular dengan error handling pembagian nol
* 📌 **Soal 7**: Rata-rata output energi dengan pengecekan data hilang
* 🎁 **Bonus ML**: Prediksi daya tarik investasi proyek baru

---

## 📈 Pembelajaran & Hasil

### 💻 Keterampilan Python yang Diasah:

* If-Else, For & While Loop
* List & Dictionary
* Function & Modularisasi
* Try-Except (Error Handling)
* Machine Learning dasar (Decision Tree Classifier)

### 🛠️ Produk Akhir:

* Script analisis berbasis Python
* Output terstruktur per soal
* Dokumentasi dalam format markdown dan Jupyter

### 🌱 Dampak:

* Memberikan gambaran nyata cara Python bantu kebijakan Green Finance
* Alat bantu pengambilan keputusan berbasis data
* Mendukung visi pembangunan hijau Indonesia

---

## 🧪 Metodologi yang Digunakan

1. 📊 **Pengolahan Data**: pandas + Excel merging
2. 🧠 **Logika Python**: struktur dasar & pengambilan keputusan
3. 🛡️ **Error Handling**: menjaga program tetap jalan
4. 🌳 **ML (Bonus)**: Decision Tree untuk klasifikasi investasi
5. 📋 **Markdown + Jupyter**: integrasi narasi dan kode

---

## ❓ Kenapa Metode Ini?

Karena semua proyek nyata melibatkan data beragam, maka:

* Python memudahkan automasi dan pengolahan data besar
* Library seperti pandas, sklearn, dan openpyxl sangat relevan
* Notebook memungkinkan hasil + dokumentasi dalam satu file

---
# ❓ Penjelasan JAWABAN?
## 📁 Dataset yang Digunakan
- `Economic_Dataset.xlsx`
- `Social_Dataset.xlsx`
- `Environmental_Dataset.xlsx`
- `Geospatial_Dataset.xlsx`
- `Financial_Dataset.xlsx`

Pastikan kelima file ini ada dalam satu folder dengan notebook ini.

---

## 🧾 Struktur Notebook

| Bagian | Deskripsi |
|--------|-----------|
| **Cell 1** | Import dan load seluruh dataset |
| **Cell 2–8** | Soal 1–7: Python dasar (if, loop, dict, function, try-except) |
| **Cell 9** | Bonus: Decision Tree Classifier |
| **Markdown ini** | Penjelasan dokumentasi tugas |

---

## 🧩 Penjelasan

### 🔹 Soal 1 – If-Else & Aritmatika
Menghitung efisiensi CO2 per biaya investasi untuk proyek PLTS. Hasil dikategorikan sebagai `High` atau `Low`.

### 🔹 Soal 2 – For Loop & List
Menghitung rata-rata pengurangan emisi CO2 dari semua proyek PLTM.

### 🔹 Soal 3 – While Loop & Input
Menerima input `Project_ID` lalu menampilkan `Land_Status` dan `Tingkat_Konflik`. (interaktif, bisa di-skip saat testing)

### 🔹 Soal 4 – Dictionary Filtering
Filter proyek yang memiliki `Daya_Tarik_Investasi` tinggi dan `Tingkat_Konflik` rendah.

### 🔹 Soal 5 – Function
Membuat fungsi untuk menghitung total investasi dari proyek dengan `Efisiensi_Lokasi` tinggi.

### 🔹 Soal 6 – Fungsi Modular + Error Handling
Buat fungsi `compute_co2_efficiency()` yang menghindari pembagian nol saat menghitung rasio CO2/investasi.

### 🔹 Soal 7 – Try-Except dalam Loop
Cek output energi (`Energy_Output`) untuk sejumlah proyek. Tangani `KeyError` jika data tidak ditemukan.

### ⭐ Bonus – Decision Tree
Bangun model klasifikasi `Daya_Tarik_Investasi` berdasarkan:
- `GDP_Growth`
- `CO2_Reduction`
- `Investment_Cost`

---

## ▶️ Cara Menjalankan Notebook

1. Jalankan semua cell secara berurutan dari atas ke bawah.
2. Jika perlu install dependencies:

```bash
pip install pandas scikit-learn openpyxl
```

3. Untuk soal 3 (interaktif input), aktifkan bagian `while True:` dan jalankan di terminal/CLI jika diperlukan.

---

## 👥 Kolaborasi
Tiap anggota kelompok wajib memahami logika di balik tiap cell. Silakan berdiskusi, tapi semua harus bisa menjelaskan alur kerja script-nya.

Semoga sukses membangun analisis data untuk masa depan hijau Indonesia! 🇮🇩💡
