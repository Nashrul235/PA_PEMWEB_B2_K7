Gelato Store Platform
Platform digital ini adalah website e-commerce untuk penjualan berbagai varian rasa ice cream gelato. Tujuan utamanya adalah untuk memudahkan proses jual beli gelato, memberikan kemudahan bagi admin dalam mengelola inventaris dan pengguna, serta menghubungkan penjual dengan pembeli potensial.

Fitur Utama
Fitur Pengguna
Registrasi dan Login: Pengguna dapat membuat akun baru atau masuk ke akun yang sudah terdaftar.
Home: Mengakses halaman utama yang menampilkan daftar menu gelato.
About: Mengetahui filosofi dari toko gelato.
Panduan: Panduan tentang cara menyimpan gelato dengan baik dan benar.
Pencarian Produk: Mencari produk gelato tertentu.
Filter dan Sortir: Menyaring produk berdasarkan kategori (buah, dessert, permen) dan mengurutkan harga.
Kontak: Menampilkan informasi kontak toko (email dan WhatsApp).
Dark Mode: Mengubah tampilan ke mode malam atau siang.
Tambah ke Favorit: Menambahkan produk gelato ke daftar favorit.
Tambah ke Keranjang: Menambahkan produk ke keranjang belanja.
Keranjang Belanja: Menampilkan produk yang ada di keranjang belanja, dengan opsi checkout.
Checkout: Melakukan pemesanan dan mengirim informasi ke admin.
Hapus Keranjang: Menghapus produk dari keranjang belanja.
Hamburger Menu: Mengakses menu di perangkat mobile.
Logout: Keluar dari akun pengguna.
Fitur Admin
Login Admin: Akses ke dashboard admin menggunakan username dan password.
Manajemen Produk: Menambah, mengedit, atau menghapus varian rasa gelato, lengkap dengan deskripsi, foto, harga, dan stok.
Manajemen Pengguna: Melihat, menambah, mengedit, atau menghapus data pengguna.
Logout Admin: Keluar dari dashboard admin.
Arsitektur Kelas
Pelanggan: Setiap pelanggan dapat melakukan pemesanan banyak produk.
Keranjang Belanja: Banyak produk dapat ditambahkan ke keranjang belanja, dan satu pelanggan dapat mengakses beberapa keranjang.
Checkout: Proses checkout dikelola oleh admin, dan admin dapat mengelola beberapa status checkout.
Admin: Mengelola produk, pengguna, serta memproses status checkout pelanggan.
Teknologi yang Digunakan
Frontend: HTML, CSS, JavaScript, dan framework frontend (React/Vue/Angular)
Backend: Node.js/Express atau PHP/Laravel untuk API dan logika bisnis
Database: MySQL/PostgreSQL untuk manajemen data produk, pengguna, dan transaksi
Authentication: JSON Web Token (JWT) atau session-based untuk autentikasi pengguna dan admin
Version Control: Git untuk kolaborasi dan manajemen versi
