# Project UTS Pemrograman Web

## Nama: Fadhil Syafiq Abdullah
## NIM: 312510161
## Kelas: I251B
## Mata Kuliah: Pemrograman Web

## BukuPedia Website Pemesanan Buku
BukuPedia adalah aplikasi website sederhana untuk simulasi pemesanan buku secara online. Proyek ini dibuat menggunakan HTML, CSS, dan JavaScript dengan data dummy dari file `data.js`, sehingga tidak membutuhkan server aplikasi atau database.

## Fitur
1. Login: validasi email dan password akun demo.
2. Dashboard: sapaan berdasarkan waktu dan ringkasan data.
3. Katalog/Stok: sampul, judul, kode, edisi, stok, harga, 4. 4. 4.pencarian, dan tambah stok.
4. Checkout: keranjang, jumlah buku, data pemesan, metode pembayaran, dan penyimpanan pesanan.
5. Tracking: pencarian nomor DO, detail, dan riwayat pengiriman.
6. Laporan dan Riwayat: menampilkan transaksi yang tersimpan di browser.

## Fungsi File
`index.html` Form login dan modal daftar/lupa password.
`dashboard.html` Sapaan, ringkasan, dan navigasi.
`stok.html` Katalog, pencarian, dan tambah stok.
`checkout.html` Keranjang dan formulir pemesanan.
`tracking.html` Pencarian dan detail pengiriman.
`laporan.html` Ringkasan dan tabel pesanan.
`riwayat.html` Daftar transaksi.
`style.css` mengatur warna, tata letak, tombol, tabel, form, modal, dan responsivitas.
`app.js` Validasi, event, manipulasi DOM, keranjang, checkout, tracking, laporan, dan riwayat.
`data.js` Data demo pengguna, katalog buku, dan tracking.
`img/` Lima gambar sampul buku.

## Data dan Fungsi JavaScript
`data.js` memiliki tiga variabel:
- `dataPengguna`: akun demo berisi nama, email, password, dan role.
- `dataKatalogBuku`: kode, nama, jenis, edisi, stok, harga, dan jalur sampul buku.
- `dataTracking`: informasi pengiriman berdasarkan nomor DO, status, dan riwayat perjalanan.
Fungsi penting di `app.js`:
- Login/logout: memeriksa akun demo, menyimpan sesi, dan menghapus sesi saat keluar.
- Dashboard: menampilkan sapaan waktu lokal dan menghitung ringkasan.
- Katalog: membuat kartu dan tabel secara dinamis, memfilter pencarian, serta menambahkan buku ke keranjang.
- Keranjang/checkout: mengubah jumlah, menghapus item, menghitung total, dan menyimpan pesanan.
- Tracking: mencari nomor DO dan menampilkan detail pengiriman.
- Laporan/riwayat: membaca pesanan dari `localStorage` dan menampilkannya.
Fungsi pembantu `rupiah()` memformat harga, `angkaHarga()` mengambil angka dari teks harga, `getCart()`/`saveCart()` mengelola keranjang, dan `getOrders()`/`saveOrders()` mengelola pesanan. Event `DOMContentLoaded` menjalankan inisialisasi setelah HTML selesai diparsing.

## Link Youtube:
https://youtu.be/-TzCBWPEZqg?si=BBzcLJbCdY7fxPtr
