# 📚 Analisis Tingkat Kegemaran Membaca Masyarakat Indonesia (2024)

![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Dataset](https://img.shields.io/badge/dataset-2024-blue)
![Model](https://img.shields.io/badge/LLM-IBM_Granite_3.3_8B-informational)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## 🧠 Project Overview

Proyek ini bertujuan untuk menganalisis tingkat literasi membaca dan faktor-faktor yang memengaruhinya di berbagai provinsi di Indonesia berdasarkan data survei tahun 2024. Latar belakang dari proyek ini adalah pentingnya literasi membaca dalam mendukung pembangunan nasional serta perlunya pemahaman terhadap kesenjangan antarwilayah untuk merumuskan intervensi kebijakan yang tepat sasaran.

Permasalahan utama yang dianalisis adalah perbedaan kebiasaan membaca antar provinsi serta kaitannya dengan akses internet dan faktor lainnya. Pendekatan yang digunakan meliputi eksplorasi data, transformasi data untuk keperluan analisis, pemanfaatan Language Model (LLM) untuk analisis lanjutan, serta visualisasi temuan utama.

---

## 📁 Raw Dataset

Dataset mentah yang digunakan dalam proyek ini dapat diakses di tautan berikut:
- **Source**: [Dataset BSP (Pendidikan)  ](https://www.bps.go.id/id/statistics-table/3/TlROMldrTjVjVzEwVWtkbmRUSk5abkk0T0U5Q1FUMDkjMyMwMDAw/tingkat-kegemaran-membaca-masyarakat-dan-unsur-penyusunnya-menurut-provinsi.html?year=2024)
- **Scope**: 38 provinsi di Indonesia
- **Key columns**: `Provinsi`, `Tingkat Kegemaran Membaca`, `Frekuensi Membaca`, `Durasi Membaca1`, `Jumlah Buku yang Dibaca`, `Frekuensi Akses Internet`, `Durasi Akses Internet1`

---

## 🔍 Insight & Findings

1. **Kesenjangan Regional:** Terdapat variasi signifikan dalam minat baca antar provinsi. Provinsi di Pulau Jawa dan beberapa wilayah di Sumatra dan Sulawesi menunjukkan tingkat keterlibatan membaca yang lebih tinggi dibanding wilayah timur Indonesia.
2. **Frekuensi vs. Durasi Membaca:** Durasi membaca cenderung tinggi di hampir semua provinsi, namun frekuensinya beragam. Hal ini menunjukkan bahwa ketika masyarakat membaca, mereka cenderung meluangkan waktu cukup lama, namun tidak semua menjadikan membaca sebagai kebiasaan rutin.
3. **Pengaruh Akses Internet:** Akses internet yang luas tidak selalu berbanding lurus dengan minat baca yang tinggi. Hal ini mengindikasikan adanya pengaruh faktor lain seperti budaya, pendidikan, dan kondisi sosial ekonomi yang lebih dominan.
4. **Anomali:** Beberapa provinsi menunjukkan pola data yang tidak biasa, seperti akses internet tinggi namun frekuensi membaca rendah, atau minat baca tinggi namun jumlah buku yang dibaca relatif sedikit. Hal ini menunjukkan perlunya studi lebih mendalam secara lokal.

---

## 🧠 AI Support Explanation

Proyek ini menggunakan Language Model dari Replicate (ibm-granite/granite-3.3-8b-instruct) untuk membantu proses analisis data. Model ini digunakan untuk:

- 🔠 **Classification**  
  Mengelompokkan provinsi ke dalam kategori literasi baca Tinggi, Sedang, dan Rendah berdasarkan pola data.

- 📑 **Summarization**  
  Memberikan ringkasan dalam bahasa alami mengenai tren dan perbedaan utama dalam kebiasaan membaca di seluruh provinsi.

- 💡 **Recommendation Generation**  
  Menghasilkan rekomendasi berbasis data yang disesuaikan dengan karakteristik tiap wilayah.

- 🧭 **Anomaly Detection**  
  Mengidentifikasi provinsi-provinsi dengan pola data yang tidak biasa yang menyimpang dari tren umum.

- 🧩 **Grouping**  
  Mengelompokkan provinsi ke dalam kategori-kategori berbeda berdasarkan kesamaan dalam perilaku membaca dan data akses internet mereka.

Pemanfaatan LLM membantu dalam menghasilkan wawasan dan output kreatif yang melengkapi pendekatan analisis data konvensional.

---

## 💬 Output

Seluruh proses dilakukan menggunakan Google Colab dan file dataset CSV. Semua prompt dan output disusun sebagai bagian dari analisis. Untuk melihat detail prompt dan hasilnya:

- [Check Here](https://github.com/mriaer/granite-literacy-classification/blob/main/CapstoneProject.ipynb)

---

## 📌 Recommendations

1. **Perluasan Infrastruktur Digital di Wilayah Timur**  
   Fokus pada Papua, Maluku, dan Nusa Tenggara dengan memperluas akses internet dan literasi digital.

2. **Program Literasi Lokal dan Intervensi Sosial**  
   Mengadakan mobil perpustakaan dan pelatihan literasi berbasis budaya lokal.

3. **Replikasi Praktik Terbaik dari Provinsi dengan Minat Tinggi**  
   Misalnya DI Yogyakarta dan Bangka Belitung, untuk menjadi model nasional.

---

## 👥 Author

- Ridho Nugroho  
- Peserta Hackathon Hacktiv8 x IBM – AI for Data Classification & Summarization  
- Tahun: 2025

