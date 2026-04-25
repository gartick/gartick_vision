# Julian Plaza

Website portofolio statis bertema pixel-art untuk Julian Plaza — 3D artist & web creator.

## Struktur File

```
index.html      — Halaman utama
guide.html      — Halaman tutorial & panduan
portfolio.html  — Halaman koleksi karya
style.css       — Semua styling & animasi
script.js       — Engine animasi background & efek interaktif
```

## Cara Menjalankan

Tidak memerlukan build tool. Cukup buka `index.html` langsung di browser, atau gunakan live server:

```bash
# Dengan Python
python3 -m http.server 8080

# Dengan Node.js (npx)
npx serve .
```

Kemudian buka `http://localhost:8080` di browser.

## Teknologi

- HTML5, CSS3, Vanilla JavaScript
- Tidak ada dependensi eksternal JS
- Font: Press Start 2P, Silkscreen, VT323 (Google Fonts)
- Web Audio API untuk efek suara 8-bit
