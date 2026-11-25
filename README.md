# HAMZ PANEL (versi JavaScript)

Website statis, tanpa build tool. Langsung upload ke GitHub Pages.

## Struktur
- `index.html`    pembungkus tipis
- `css/base.css`, `css/extra.css`  tampilan
- `js/data.js`    **edit harga, kontak, spesifikasi di sini**
- `js/ui.js`      template tiap bagian halaman
- `js/fx.js`      efek: rack 3D, partikel, kalkulator, dashboard live
- `js/main.js`    titik masuk
- `assets/favicon.svg`

## Ganti harga / nomor
Buka `js/data.js`, ubah `PLANS`, `SITE.wa`, `SITE.tg`, lalu commit.

## Jalankan lokal
Modul ES tidak jalan lewat file://, pakai server:
    python3 -m http.server 8000
lalu buka http://localhost:8000
