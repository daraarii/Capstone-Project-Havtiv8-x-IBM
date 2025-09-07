# Capstone-Project-Havtiv8-x-IBM

# 📖 Analisis Indeks Pembangunan Literasi Masyarakat (IPLM) 2023

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk **menganalisis Indeks Pembangunan Literasi
Masyarakat (IPLM)** di Indonesia, mengidentifikasi akar masalah literasi
antarwilayah, serta memberikan rekomendasi berbasis data untuk mendukung
pemerataan kualitas literasi sebagai fondasi pembangunan SDM dan
transformasi digital.

Capstone Project ini merupakan bagian dari **Hactiv8 x IBM**, dengan
dukungan teknologi **IBM Granite** untuk summarization, classification,
dan recommendation.

------------------------------------------------------------------------

## 🎯 Objective

-   Menganalisis kondisi IPLM di berbagai daerah di Indonesia.\
-   Mengidentifikasi disparitas antarwilayah dalam akses dan kegiatan
    literasi.\
-   Memberikan pengetahuan dasar untuk program pemerataan literasi dan
    pembangunan SDM.\
-   Menyediakan rekomendasi bagi pemerintah, Samsung Hactive, dan IBM
    Indonesia dalam mendorong literasi digital yang inklusif.

------------------------------------------------------------------------

## 🛠️ Tools & AI Support

-   **Google Colab** → Python compiler untuk preprocessing, analisis,
    dan modelling.\
-   **IBM Granite** →
    -   Summarization: merangkum laporan literasi.\
    -   Classification: mengklasifikasikan isu literasi (akses,
        pemerataan, partisipasi).\
    -   Recommendation: menyusun rekomendasi kebijakan berbasis data.\
-   **Data Visualization** → Menyajikan visualisasi skor IPLM,
    persebaran UPLM, serta ketimpangan antarwilayah.

------------------------------------------------------------------------

## 📂 Dataset

-   **Sumber:** [data.go.id -- Indeks Pembangunan Literasi Masyarakat
    2023](https://data.go.id/dataset/dataset/indeks-pembangunan-literasi-masyarakat-2023)\
-   **Keterangan Kolom:**
    -   `Prov` : Nama Provinsi\
    -   `Kodprov` : Kode Provinsi\
    -   `Kabkot` : Nama Kabupaten/Kota\
    -   `Kodkabkot` : Kode Kabupaten/Kota\
    -   `Lat`, `Long` : Koordinat geografis\
    -   `UPLM1–UPLM7` : Sub-indeks literasi (akses, standar
        perpustakaan, koleksi, tenaga, kunjungan, anggota, partisipasi
        masyarakat)\
    -   `SKOR IPLM` : Nilai indeks rata-rata\
    -   `KATEGORI IPLM` : Kategori indeks (Rendah, Sedang, Tinggi, dst.)

⚠️ Catatan: dataset masih mengandung data kosong di beberapa skor
daerah.

------------------------------------------------------------------------

## 🔄 Alur Analisis

1.  **Data Preparation** → memuat & membersihkan dataset.\
2.  **Exploratory Data Analysis (EDA)** → memahami distribusi & korelasi
    antarvariabel.\
3.  **AI Processing dengan IBM Granite** → summarization,
    classification, recommendation.\
4.  **Insight Generation** → menarik temuan penting dari analisis &
    visualisasi.\
5.  **Conclusion & Recommendation** → menyusun kesimpulan dan solusi
    tindak lanjut.

------------------------------------------------------------------------

## 📊 Hasil Analisis

-   **Provinsi dengan Skor Tertinggi:** Sulawesi Selatan (81.47), DI
    Yogyakarta (78.58).\
-   **Provinsi dengan Skor Terendah:** Papua (34.22), Papua Barat
    (51.12).\
-   **Korelasi Terkuat:** UPLM3 (Ketercukupan koleksi) → 0.69 terhadap
    SKOR IPLM.\
-   **Isu Utama:** pemerataan koleksi, kualitas fasilitas, dan
    partisipasi masyarakat.

------------------------------------------------------------------------

## ✅ Kesimpulan & Rekomendasi

-   Ada ketidakmerataan signifikan dalam literasi antarwilayah
    Indonesia.\
-   **Fokus peningkatan:**
    -   Memperkuat perpustakaan di daerah tertinggal (Papua, Papua
        Barat).\
    -   Menambah koleksi bacaan & tenaga perpustakaan (UPLM3 & UPLM4).\
    -   Mendorong keterlibatan masyarakat dalam kegiatan literasi
        (UPLM7).\
    -   Meningkatkan standar perpustakaan nasional (UPLM2).

Analisis ini diharapkan dapat mendukung pemerintah, Samsung Hactive, dan
IBM Indonesia dalam menciptakan solusi digital yang inklusif dengan
fondasi literasi yang kuat.
