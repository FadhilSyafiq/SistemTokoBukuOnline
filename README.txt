BUKU PEDIA - WEBSITE PEMESANAN BUKU

Isi folder:
- index.html       : Login, modal lupa password dan daftar
- dashboard.html   : Dashboard, greeting waktu lokal dan navigasi
- stok.html        : Katalog dinamis, pencarian dan tambah data stok dengan DOM
- checkout.html    : Keranjang, ubah jumlah/hapus item, data pemesan dan pembayaran
- tracking.html    : Tracking menggunakan dataTracking dari data.js
- laporan.html     : Ringkasan dan tabel laporan pemesanan
- riwayat.html     : History transaksi
- style.css        : Seluruh styling eksternal dan responsive
- app.js           : Validasi, manipulasi DOM, interaksi aplikasi
- data.js          : Data dummy yang diberikan (path cover disesuaikan ke file gambar)
- img/             : Lima gambar sampul buku

CARA MENJALANKAN
1. Buka login.html menggunakan browser. Untuk pengalaman terbaik, gunakan ekstensi Live Server di VS Code.
2. Login demo:
   User:  rina@gmail.com / rina123
   User:  agus@gmail.com / agus123
   Admin: siti@gmail.com / siti123
3. Untuk tracking, gunakan nomor DO 20230012 atau 20230013.

CATATAN
- Aplikasi ini adalah demo front-end tanpa backend/database.
- Keranjang, sesi login, dan transaksi disimpan di localStorage browser.
- Data tambah stok hanya berada di memori halaman saat ini; refresh akan mengembalikan data awal dari data.js.
- Fitur daftar dan lupa password berupa simulasi, sesuai konteks front-end.
