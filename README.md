# Cek Ongkir Ekspedisi (RajaOngkir API)

Aplikasi web kalkulasi biaya pengiriman kurir ekspedisi domestik di Indonesia yang terintegrasi langsung dengan REST API RajaOngkir (Komerce API).

## Fitur Utama
- **Pilihan Kurir Domestik**: Mendukung pengecekan tarif JNE, POS, TIKI, SiCepat, J&T, dll.
- **Perhitungan Berat Otomatis**: Menghitung estimasi ongkir berdasarkan kota asal, kota tujuan, dan bobot kiriman paket.
- **Respons Cepat**: Permintaan HTTP cURL ke endpoint API resmi dengan parsing data JSON langsung ke antarmuka.

## Teknologi
- PHP (cURL Client)
- RESTful API (RajaOngkir / Komerce API)
- HTML5 & CSS3

## Panduan Instalasi
1. Letakkan berkas pada direktori server lokal Anda (htdocs).
2. Konfigurasikan API Key Anda pada variabel \ atau melalui environment variable RAJAONGKIR_API_KEY.
3. Buka berkas melalui browser:
   `
   http://localhost/cek-ongkir-rajaongkir/ongkir1web.php
   `
"@
        gitignore = @"
.env
.vscode/
.idea/
Thumbs.db
.DS_Store
