# SENJA POS — Kasir Cloud & Dashboard Backoffice

Demo aplikasi POS untuk bakery & kopi. Satu file `index.html` (HTML + CSS + JavaScript murni), data dummy, siap GitHub Pages.

## Fitur
- Dashboard: KPI per periode, grafik tren (Chart.js), donat metode bayar, menu terlaris, transaksi terkini
- Kasir / POS: filter kategori, cari menu, keranjang, pajak PB1 10%, bayar (transaksi masuk ke Dashboard dan Riwayat)
- Riwayat Pesanan, Pelanggan, Daftar Produk, Kategori & Varian, Stok & Inventori
- Laporan Penjualan, Rekap Kasir & Shift, Pajak & Diskon
- Kelola Cabang (ganti outlet di sidebar), Printer & Struk, Pengaturan Akun
- Responsif, menu hamburger di HP

## Deploy ke GitHub Pages
```bash
git init
git add .
git commit -m "feat: initial commit"
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git branch -M main
git push -u origin main
```
Lalu Settings → Pages → Source: branch `main`, folder `/ (root)` → Save.
URL: `https://USERNAME.github.io/NAMA-REPO/`

## Tech stack
HTML5, CSS3, Vanilla JavaScript, Chart.js, Font Awesome 6, Google Fonts (Plus Jakarta Sans).
