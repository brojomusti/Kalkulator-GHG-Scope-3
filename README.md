# Scope 3 Emission Calculator - GHG Protocol Tool

Sebuah aplikasi web untuk menghitung emisi gas rumah kaca sesuai **GHG Protocol - Scope 3 Calculation Guidance**, cocok digunakan oleh sektor **kelapa sawit** dan sektor lainnya.

## Fitur Utama
- Hitung emisi sesuai 15 kategori Scope 3
- Upload file Excel untuk batch input
- Ekspor hasil ke CSV dan PDF
- Visualisasi emisi menggunakan Chart.js
- Bisa diinstal sebagai PWA (Progressive Web App)

## Cara Menggunakan
1. Buka file `index.html` di browser
2. Masukkan data aktivitas per kategori
3. Klik tombol hitung
4. Lihat grafik distribusi emisi
5. Ekspor hasil atau simpan sebagai PDF

## Teknologi
- HTML, CSS, JavaScript Vanilla
- Chart.js
- SheetJS (xlsx)
- PapaParse (CSV)
- jsPDF + html2canvas (PDF)
- Manifest.json dan Service Worker (untuk PWA)

## Lisensi
MIT License - lihat file LICENSE