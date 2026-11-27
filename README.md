# smartkasir.co.id
aplikasi kasir online web based

## SmartKasir
SmartKasir adalah versi statis aplikasi kasir mobile Ketoko-style untuk UMKM
(Toko Berkah Jaya) — bisa dibuka langsung di browser HP dan diinstal sebagai
PWA (Progressive Web App). Tidak ada server atau database: semua data
tersimpan di localStorage browser masing-masing perangkat.

### Cara memakai (demo)
1. Buka situs ini di HP (Chrome Android / Safari iPhone).
2. Login demo — ID Perusahaan: `BERKAHJAYA`, User ID: `admin`, Password: `admin123`.
3. Kasir: tambah produk, bayar Tunai / E-MONEY, stok berkurang otomatis, nota
   bernomor dengan kembalian.
4. Instal sebagai aplikasi: halaman Instal di dalam aplikasi, atau
   Chrome > Tambahkan ke Layar Utama / Safari > Share > Tambah ke Layar Utama.

### Deploy
Situs statis tanpa build step. Deploy ke Vercel: Import Project → repo ini →
Framework: Other → Deploy. GitHub Pages: Settings → Pages → branch `main`.

### Catatan
Data demo (16 produk Toko Berkah Jaya) tersimpan per-perangkat dan tidak
tersinkron dengan aplikasi POS web/Desktop. Cetak struk adalah simulasi.
Aplikasi asli yang ditiru: Ketoko.co.id Mobile.
