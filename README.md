# Pemweb5

1. Pengertian Bootstrap
   Bootstrap adalah framework front-end open-source berbasis HTML, CSS, dan JavaScript yang dirancang untuk mempermudah dan mempercepat pengembangan antarmuka web (UI).   Kegunaan: Membantu developer membuat tampilan web yang responsif (rapi di HP, tablet, maupun laptop) secara cepat tanpa harus menuliskan seluruh style CSS dan komponen interaktif dari awal.

2.  Memasang Bootstrap
   Ada 3 cara utama untuk menggunakan Bootstrap pada sebuah proyek:   CDN (Content Delivery Network): Memasang link tag <link> (CSS) dan <script> (JS) langsung dari server pihak ketiga di file HTML.Package Manager (NPM / Yarn): Mengunduh package Bootstrap melalui Terminal dengan perintah npm install bootstrap untuk proyek berbasis bundler atau Node.js.Download File Lokal: Mengunduh bundle file CSS & JS langsung dari situs resmi Bootstrap, lalu menyimpannya di folder proyek dan dihubungkan via path relatif.

3. Grid dan Breakpoint
   Class Grid: Sistem tata letak berbasis Flexbox 12 kolom yang terdiri dari struktur container, row, dan col. Sistem ini digunakan untuk mengatur susunan serta tata letak elemen secara presisi.

Kegunaan Breakpoint: Menjadi batasan/titik pemicu ukuran lebar layar (seperti sm, md, lg, xl, xxl) tempat tata letak halaman web akan menyesuaikan diri secara otomatis saat ukuran perangkat berubah.

4. Class Bootstrap
   Lima class bawaan Bootstrap beserta kegunaannya:   container: Menampung, memberi margin, dan membatasi lebar konten di tengah layar.d-flex: Mengubah mode display suatu elemen menjadi Flexbox untuk memudahkan pengaturan alur tata letak.btn: Memberikan style dasar pada tag button atau link agar berbentuk tombol interaktif.text-center: Mengatur posisi teks agar berada di tengah (center-aligned).shadow: Memberikan efek bayangan pada kotak/elemen UI seperti card.

5. Gambar Responsif
   Untuk membuat gambar responsif agar ukurannya otomatis menyesuaikan lebar layar perangkat, tambahkan class img-fluid pada tag <img>.   Contoh penggunaannya:   HTML<img src="gambar.jpg" class="img-fluid" alt="Contoh Gambar">
