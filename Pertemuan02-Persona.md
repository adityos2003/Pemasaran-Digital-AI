Minggu 2: 
Digital Customer Journey & Persona

Teori yang Dibahas:
Konsep Customer Journey (Awareness -> Consideration -> Conversion -> Retention).
Pemetaan titik sentuh (touchpoint) & titik masalah (pain points).
Pembuatan Buyer Persona statis vs Predictive AI Persona.

Praktik & Implementasi:
Aktivitas: Mengolah data mentah ulasan konsumen (review Google/Shopee) menjadi profil target pasar.Eksplorasi Tool: Menggunakan HubSpot Make My Persona & Prompt Engineering (ChatGPT) untuk mengekstrak pola perilaku konsumen.Output: Dokumen visual Digital Customer Journey Map dan 2 profil Buyer Persona.


📄 Bagian 1: Ringkasan Modul Ajar (Untuk Pengajar/LMS)
Mata Kuliah: Pemasaran Digital berbasis AI

Pertemuan: 2
Topik: Digital Customer Journey & Persona

Acuan Pustaka: Chaffey & Ellis-Chadwick (2019) – Customer Relationship Management & Journey Mapping; Kingsnorth (2022) – Customer Insights, Personas, and Personalisation.

Estimasi Waktu: 3 x 50 menit (Luring/Daring)

📚 Bagian 2: Rangkuman Teori Singkat (Bahan Kuliah)
1. Konsep Digital Customer Journey (Siklus Pelanggan)
Pemasaran digital tidak berhenti pada transaksi pertama, melainkan mencakup 4 tahapan utama:

Awareness (Kesadaran): Konsumen baru menyadari memiliki masalah atau kebutuhan (misal: mencari tempat kerja yang tenang dengan wifi cepat).

Consideration (Pertimbangan): Konsumen membandingkan beberapa opsi produk/merek berdasarkan ulasan, harga, dan fitur.

Conversion (Keputusan Pembelian): Konsumen melakukan transaksi (di e-commerce, landing page, atau toko fisik).

Retention & Advocacy (Loyalitas): Pelanggan kembali membeli (repeat order) dan merekomendasikan produk kepada orang lain.

2. Touchpoints & Pain Points
Touchpoints (Titik Sentuh): Semua saluran/interaksi di mana konsumen bertemu dengan brand Anda (misal: Iklan Instagram, Ulasan Google Maps, Chat WhatsApp, Kemasan Produk).

Pain Points (Titik Masalah): Kendala atau kekhawatiran yang dialami konsumen pada setiap tahap (misal: respon chat lambat, ongkir mahal, deskripsi produk tidak jelas).

3. Buyer Persona Statis vs. Predictive AI Persona
Statis (Tradisional): Dibuat berdasarkan asumsi atau survei sampel kecil yang jarang diperbarui (contoh: "Budi, usia 25 tahun, suka kopi").

Predictive AI Persona: Dibuat dengan menganalisis data mentah berukuran besar (Big Data ulasan konsumen, komentar media sosial) menggunakan AI/NLP untuk mengekstrak sentimen, motivasi tersembunyi, dan pola perilaku secara real-time.

🛠️ Bagian 3: Panduan Praktikum & Prompt Engineering
Pada praktikum minggu ini, mahasiswa akan mengolah data mentah ulasan (reviews) dari Google Maps atau Shopee dari sebuah brand nyata menggunakan AI untuk menghasilkan Buyer Persona dan Customer Journey Map.

Langkah Kerja Mahasiswa:
Pengumpulan Data Mentah: Mahasiswa mencari produk/brand di Shopee atau Google Maps, lalu menyalin (copy) 10–15 ulasan positif dan negatif dari pembeli nyata.

Ekstraksi Persona dengan ChatGPT / Claude: Gunakan Prompt 1 di bawah ini untuk mengolah data ulasan menjadi profil Buyer Persona.

Pemetaan Journey dengan ChatGPT: Gunakan Prompt 2 untuk menyusun Customer Journey Map.

Visualisasi: Opsional, gunakan platform gratis HubSpot Make My Persona (hubspot.com/make-my-persona) untuk membuat kartu persona visual yang rapi.

🤖 Koleksi Prompt AI untuk Pertemuan 2
Prompt 1: Ekstraksi Buyer Persona dari Data Ulasan Mentah

Kamu adalah seorang pakar Customer Insights & Market Research. 
Berikut adalah kumpulan data mentah ulasan konsumen mengenai produk [Nama Produk/Brand, misal: Skincare X / Kopi Y]:

---
[Tempelkan 10-15 ulasan konsumen dari Shopee/Google Maps di sini]
---

Berdasarkan data ulasan di atas, analisislah dan buatkan 1 profil Buyer Persona yang paling representatif dengan format berikut:
1. Demografi & Latar Belakang (Usia, Pekerjaan, Gaya Hidup)
2. Utama Motivasi / Goals (Apa yang dicari konsumen dari produk ini?)
3. Pain Points / Frustrasi Utama (Apa keluhan atau ketakutan utama mereka?)
4. Faktor Pembeli (Apa alasan utama yang membuat mereka akhirnya mau membeli?)

Prompt 2: Pemetaan Digital Customer Journey & Pain Points
Berdasarkan profil Buyer Persona yang telah dibuat sebelumnya untuk produk [Nama Produk/Brand], petakan Digital Customer Journey dalam bentuk tabel yang mencakup 4 tahap: Awareness, Consideration, Conversion, dan Retention.

Untuk setiap tahap, rinci aspek berikut:
- Aktivitas Konsumen (Apa yang mereka lakukan?)
- Digital Touchpoints (Channel/Platform apa yang mereka gunakan?)
- Pain Points (Apa hambatan mereka di tahap ini?)
- Rekomendasi Solusi Digital (Strategi/AI Tools apa yang bisa diterapkan brand untuk membantu konsumen di tahap ini?)

📝 Bagian 4: Draf Berkas Pertemuan2-Persona.md untuk Repositori GitHub
Anda dapat membuat berkas baru di repositori GitHub Anda dengan nama Pertemuan2-Persona.md dan menempelkan draf di bawah ini:
# 📂 Pertemuan 2: Digital Customer Journey & Persona

Repositori ini berisi panduan materi dan modul praktikum untuk **Pertemuan 2** mata kuliah Pemasaran Digital berbasis AI.

---

## 🎯 Tujuan Pembelajaran
1. Memahami konsep *Customer Journey* (Awareness → Consideration → Conversion → Retention).
2. Mampu mengidentifikasi *Digital Touchpoints* dan *Pain Points* konsumen.
3. Mampu mengekstrak data mentah ulasan publik menjadi *Predictive AI Persona* menggunakan teknik *Prompt Engineering*.

---

## 📌 Pokok Bahasan
- **Kerangka Teori:** *Customer Relationship Management & Journey Mapping* (Chaffey, 2019; Kingsnorth, 2022).
- **Aktivitas Praktikum:**
  1. Pengumpulan data ulasan (*reviews*) dari Google Business / E-commerce.
  2. Ekstraksi *Buyer Persona* menggunakan ChatGPT / Claude.
  3. Desain visual persona menggunakan **HubSpot Make My Persona**.

---

## 🤖 Koleksi Prompt AI Pertemuan 2

### Prompt A: Analisis Data Mentah Ulasan
> "Kamu adalah seorang pakar Customer Insights. Analisis data mentah ulasan berikut: [Tempelkan ulasan]. Ekstrak menjadi 1 profil Buyer Persona yang mencakup: Demografi, Motivasi Utama, Pain Points, dan Trigger Pembelian."

### Prompt B: Pemetaan Customer Journey Map
> "Berdasarkan persona di atas, buatkan tabel Digital Customer Journey (Awareness, Consideration, Conversion, Retention) beserta Touchpoints, Pain Points, dan Rekomendasi Solusi Pemasaran Digital untuk [Nama Produk]."

---

## 📤 Tugas & Output Minggu Ini
- **Output:** Dokumen PDF/Gambar berisi **2 Profil Buyer Persona** dan **Tabel Digital Customer Journey Map**.
- **Penyetoran:** Unggah ke LMS / Vinesa sesuai tenggat waktu yang ditentukan.
