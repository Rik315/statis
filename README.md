# Perjalanan — Wisata Indonesia

Situs statis sederhana untuk mengenalkan beberapa destinasi wisata di Indonesia. Halaman utama dibuat dengan HTML murni tanpa framework, CSS, JavaScript, atau proses build. File di folder `about` merupakan contoh dropdown terpisah yang menggunakan HTML dan CSS.

## Fitur saat ini

- Beranda dengan pengantar dan tautan untuk menuju bagian destinasi.
- Navigasi berdasarkan wilayah: Jawa Barat, Jawa Tengah, Jawa Timur, Nusa Tenggara Timur, dan Papua Barat Daya.
- Tautan destinasi unggulan yang menuju ke informasi Kawah Putih, Candi Borobudur, Gunung Bromo, Labuan Bajo, dan Raja Ampat dll.
- Bagian Tentang Kami dan tautan kembali ke bagian atas halaman.
- Struktur semantik dasar, teks alternatif gambar, navigasi berlabel, dan tautan untuk melewati navigasi ke konten utama.

## Struktur proyek

```text
.
├── beranda/
│   └── index.html     # Halaman utama Perjalanan          
├── destinasi /
│   ├── Jawa-Barat / 
│   ├── Jawa-Tengah /       
│   └── Jawa-Timur /
│    (diatas hanya contoh. silahkan tambahkan wisatanya lagi. )
├── about/
│   └── about.html      # Contoh dropdown tautan eksternal;  
└── README.md
```

## Menjalankan secara lokal

Tidak perlu instalasi atau server. Buka `beranda/index.html` langsung di browser.

Untuk mengambil proyek dari GitHub melalui terminal:

```bash
git clone https://github.com/Rik315/statis.git
cd statis
```

Setelah itu, buka `beranda/index.html` di browser.

## Catatan pengembangan

Halaman ini memang ditujukan sebagai pengenalan dan sumber inspirasi tentang destinasi wisata di Indonesia, bukan sebagai layanan perjalanan atau pemesanan. Karena itu, informasi seperti harga tiket dan pemesanan tidak termasuk dalam cakupan situs. Fitur pencarian atau filter destinasi belum tersedia; fitur tersebut memerlukan JavaScript atau implementasi lain di luar HTML murni. Agar nyaman digunakan di berbagai ukuran layar, tahap berikutnya yang disarankan adalah menambahkan CSS responsif.
