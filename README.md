# UTS_VISUALISASI-DATA_KELOMPOK-2
# 🛍️ Interactive Customer Analytics Dashboard

Sebuah visualisasi interaktif yang dibangun menggunakan D3.js untuk eksplorasi perilaku belanja, demografi, dan tingkat respons kampanye pemasaran.

## 🚀 Live Demo (Visualisasi yang Telah Di-deploy)

Visualisasi ini di-deploy menggunakan GitHub Pages.

**[Akses Dashboard Interaktif di Sini]([https://www.google.com/search?q=URL_GITHUB_PAGES_ANDA](https://ruli19.github.io/UTS_VISUALISASI-DATA_KELOMPOK-2/))**
*(Ganti URL ini dengan tautan GitHub Pages Anda setelah di-deploy, contoh: `https://username.github.io/nama-repositori`)*

## 🎯 Tujuan Proyek

Visualisasi ini bertujuan untuk memungkinkan analisis terpandu (guided analysis) terhadap segmen pelanggan. Dengan memanfaatkan **Filter Dinamis Global**, pengguna dapat membandingkan pola belanja, pendapatan, usia, dan kinerja saluran pembelian antara subkelompok pelanggan yang berbeda (misalnya, membandingkan kelompok "Graduation" dengan "PhD", atau kelompok berpendapatan tinggi).

## 🛠️ Fitur Interaktif Utama

Proyek ini menerapkan interaksi tingkat lanjut yang dikoordinasikan di seluruh 5 visualisasi:

1.  **Kueri Dinamis (Dynamic Query Filters):** Filter global (Pendidikan, Status Pernikahan, Pendapatan, Jumlah Anak) diterapkan secara *real-time* ke semua bagan.
2.  **Transisi Halus (Animation):** Menggunakan D3 Transitions (`.transition()`) untuk pembaruan bagan yang mulus setelah pemfilteran.
3.  **Detail-on-Demand (Tooltip):** Menyediakan nilai data yang presisi saat mengarahkan kursor ke elemen bagan.
4.  **Brushing & Linking (Scatter Plot):** Memungkinkan seleksi kelompok pelanggan (brush) pada Scatter Plot Pengeluaran vs. Pendapatan, menampilkan statistik ringkasan seleksi tersebut dalam sebuah popup.
5.  **Zooming & Panning:** Scatter Plot mendukung kontrol manual untuk memperbesar/memperkecil (zoom) dan menggeser (pan) untuk melihat outlier atau kluster secara rinci.
6.  **Koordinasi Multi-Tampilan:** Kelima bagan diperbarui secara bersamaan setiap kali filter global berubah.

## 📜 Rationale Desain & Proses Pengembangan (Write-up)

Sesuai kriteria tugas, *write-up* (termasuk alasan mendalam untuk setiap keputusan desain, alokasi waktu, dan gambaran umum proses pengembangan) telah **di-embed langsung** di bagian **`Header`** dari [Halaman Visualisasi Interaktif](https://www.google.com/search?q=URL_GITHUB_PAGES_ANDA) untuk menyajikan konteks analisis secara langsung kepada pembaca.

## 📁 Struktur Repositori

```
/
├── index.html        # File utama: HTML, CSS, JavaScript (D3.js) dan Write-up.
├── marketing_campaign.csv # File data sumber (tab-delimited).
└── README.md         # Dokumen ini.
```

## 📚 Sumber Data & Acknowledge

  * **Data Source:** [Marketing Campaign Dataset](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign) dari Kaggle.
  * **Visualization Library:** [D3.js v7](https://d3js.org/)
  * **Inspirasi Desain:** Konsep *Coordinated Multiple Views* (CMV) dan teknik *Brushing & Linking* dari eksplorasi data.

## ⚙️ Cara Menjalankan Secara Lokal

Jika Anda ingin menjalankan proyek ini di komputer Anda tanpa mengandalkan GitHub Pages:

1.  **Clone repositori** ini.
2.  Pastikan `index.html` dan `marketing_campaign.csv` berada dalam satu folder.
3.  Buka `index.html` di browser web modern. (Anda mungkin perlu menggunakan *live server* di beberapa browser untuk memuat file CSV dengan benar, terutama jika ada masalah CORS).
