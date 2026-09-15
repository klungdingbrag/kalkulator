# 🧮 Nusantara Calculator Pro

Web calculator modular untuk kebutuhan bangunan dan perhitungan DPP & PPN.

## Struktur

```text
kalkulator/
├── index.html
├── pages/
│   ├── dpp.html
│   ├── hebel.html
│   └── keramik.html
├── js/
│   ├── app.js
│   ├── config.js
│   ├── dpp.js
│   ├── hebel.js
│   └── keramik.js
├── css/
│   └── style.css
└── assets/
```

## Menambah kalkulator

1. Buat halaman baru di `pages/`.
2. Buat logika perhitungan di `js/`.
3. Tambahkan satu entry di `js/config.js`.
4. Gunakan `css/style.css` dan fungsi umum `js/app.js` agar tampilan konsisten.

## Modul saat ini

- DPP & PPN 12%
- Kalkulator Hebel / Bata Ringan
- Kalkulator Keramik
