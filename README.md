[README.md](https://github.com/user-attachments/files/33416851/README.md)
# LYNK — Luxury Minimalist Landing Page

Website landing page toko online LYNK dengan kategori produk campuran, gaya luxury minimalis (hitam, krem, aksen emas), dan pemesanan melalui WhatsApp.

## Isi folder
- `index.html` — struktur halaman dan katalog contoh
- `style.css` — desain responsif untuk desktop, tablet, dan ponsel
- `script.js` — filter kategori, pencarian, urut harga, favorit, menu mobile, dan pemesanan WhatsApp

## Cara membuka di VS Code
1. Ekstrak ZIP ke folder yang mudah ditemukan.
2. Buka VS Code → **File → Open Folder...** → pilih folder `lynk_website`.
3. Buka `index.html`.
4. Jika memakai ekstensi **Live Server**, klik kanan `index.html` → **Open with Live Server**. Alternatif: buka `index.html` langsung dengan browser.

## WAJIB disesuaikan sebelum website dipublikasikan
1. Buka `script.js`.
2. Cari baris:
   `const WHATSAPP_NUMBER = "6281234567890";`
3. Ganti nomor contoh dengan nomor WhatsApp bisnis kamu. Gunakan format kode negara tanpa `+`, spasi, atau strip. Contoh format Indonesia: `62812XXXXXXXX`.
4. Di `index.html`, ubah nama, harga, deskripsi, kategori, dan foto produk contoh sesuai katalog asli. Setiap produk menggunakan class `product-card` dan atribut `data-name`, `data-category`, `data-price`, `data-order`.
5. Ganti tautan media sosial jika ingin menambahkan Instagram atau marketplace.

## Catatan
- Produk dan harga yang tampil adalah contoh untuk demo, bukan penawaran produk nyata.
- Foto menggunakan URL gambar eksternal dari Unsplash sehingga membutuhkan koneksi internet.
- Font Google Fonts juga memerlukan koneksi internet; jika tidak tersedia, website menggunakan font cadangan.
- Website ini merupakan landing page statis. Pemesanan diarahkan ke WhatsApp; belum ada database, login, keranjang, stok otomatis, payment gateway, atau panel admin.
- Fitur favorit hanya perubahan visual selama halaman terbuka dan tidak disimpan permanen.
