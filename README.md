# 🛍️ Interactive Marketing Campaign Dashboard

## Analisis Mendalam Pola Belanja dan Respons Kampanye Pemasaran

[](https://ruli19.github.io/UTS_VISUALISASI-DATA_KELOMPOK-2/)

Visualisasi interaktif ini dikembangkan menggunakan **D3.js v7** untuk memungkinkan eksplorasi terpandu (guided exploration) terhadap dataset Kampanye Pemasaran. Tujuannya adalah untuk memahami bagaimana demografi (Pendapatan, Pendidikan, Status Pernikahan) memengaruhi perilaku belanja dan tingkat respons terhadap promosi.

## 🚀 Akses Visualisasi (Live Demo)

Visualisasi ini di-deploy dan dapat diakses publik melalui GitHub Pages:

➡️ **[Akses Dashboard Interaktif di Sini](https://ruli19.github.io/UTS_VISUALISASI-DATA_KELOMPOK-2/)** ⬅️

## 🎯 Fitur Interaktif dan Animasi

Dashboard ini dirancang sebagai *Coordinated Multiple Views* (Tampilan Multi-Terkoordinasi) di mana setiap filter dan interaksi memengaruhi semua visualisasi secara serentak.

| Teknik Interaksi | Deskripsi | Visualisasi Terkait |
| :--- | :--- | :--- |
| **Kueri Dinamis (Filter Global)** | Filter `Pendidikan`, `Status Pernikahan`, rentang `Pendapatan`, dan `Jumlah Anak` diperbarui secara *real-time* dan diterapkan ke **semua 5 bagan** sekaligus. | Semua Bagan |
| **Brushing & Linking** | Pengguna dapat memilih area pada scatter plot (klik-drag) untuk melihat ringkasan statistik (Detail-on-Demand) subkelompok yang terseleksi. | Scatter Plot (Pengeluaran vs. Pendapatan) |
| **Panning & Zooming** | Menggunakan tombol khusus untuk navigasi (geser dan perbesar/perkecil) area scatter plot yang padat. | Scatter Plot (Pengeluaran vs. Pendapatan) |
| **Transisi & Animasi** | Penggunaan transisi D3 (`.transition().duration(800)`) untuk memperbarui batang (bar) dan titik (dot) secara halus, membantu pengguna melacak perubahan visual setelah filter diterapkan. | Semua Bagan Bar |
| **Detail-on-Demand** | Tooltip yang muncul saat kursor diarahkan untuk menampilkan nilai numerik dan kontekstual yang presisi. | Semua Bagan |

## 📜 Rasional Desain dan Proses Pengembangan (Write-up)

**Seluruh tulisan (write-up)** yang berisi **Alasan Keputusan Desain** (Pemilihan jenis bagan, skema warna, dll.) dan **Gambaran Umum Proses Pengembangan** (Pembagian kerja, alokasi waktu, aspek yang memakan waktu) telah **disematkan langsung di dalam bagian `Header`** di [Halaman Visualisasi Interaktif](https://ruli19.github.io/UTS_VISUALISASI-DATA_KELOMPOK-2/).

*Silakan buka tautan visualisasi di atas dan gulir ke bawah untuk melihat Laporan Pengembangan.*

## 📚 Sumber Daya dan Acknowledgements

  * **Data Source:** Dataset [Marketing Campaign](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign) yang diolah dari Kaggle.
  * **Visualization Tool:** D3.js v7
  * **Implementasi:** Proyek Tugas Besar Mata Kuliah Visualisasi Data Kelompok 2.

## 📁 Cara Mengunduh Kode Sumber (Clone Repository)

Untuk mengunduh dan menjalankan proyek ini di lingkungan lokal Anda, gunakan perintah `git clone` berikut:

```bash
git clone https://github.com/ruli19/UTS_VISUALISASI-DATA_KELOMPOK-2.git
```

Setelah di-clone, pastikan file `marketing_campaign.csv` berada di direktori yang sama dengan `index.html`.
