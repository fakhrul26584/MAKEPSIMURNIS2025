# Prototype Buku Program Digital — Majlis Apresiasi Pendidikan 2025

## Struktur folder GitHub

Letakkan fail seperti ini:

.
├── index.html
├── data.js
└── GAMBAR MURID/
    ├── 1 ILTIZAM/
    ├── 1 IMTIYAZ/
    ├── 1 INTISAR/
    └── ... semua folder gambar asal ...

## Cara publish ke GitHub Pages

1. Buat repository baharu.
2. Upload `index.html` dan `data.js`.
3. Extract folder `GAMBAR MURID` daripada ZIP asal dan upload folder tersebut ke repository.
4. GitHub → Settings → Pages → Deploy from branch → `main` → `/root`.
5. Buka URL GitHub Pages.

Nota:
- `data.js` sudah mengandungi data penerima dan semua rekod anugerah daripada prototype 2025.
- `MUMTAZ` diperlakukan sebagai kelas KAFA dan digabungkan dengan profile murid yang sama.
- Tujuh padanan nama fuzzy telah dianggap verified berdasarkan pengesahan pengguna.
- Prototype ini sengaja menggunakan static HTML/JS supaya boleh terus di-host melalui GitHub Pages tanpa database/server.
