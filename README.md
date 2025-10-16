# 🍵 Bakul Teh - Website Toko Teh

Website modern untuk Bakul Teh, sebuah toko teh yang menyajikan kehangatan tradisi dan kesegaran inovasi dalam setiap seduhan.

## 📋 Deskripsi Proyek

Bakul Teh adalah website bisnis teh yang didirikan pada tahun 2022 oleh Fakturozi. Website ini menampilkan berbagai varian teh unggulan dengan tampilan yang menarik dan user-friendly.

## ✨ Fitur Utama

- Hero Section - Tampilan pembuka yang menarik dengan background image
- Tentang Kami - Informasi tentang sejarah dan filosofi Bakul Teh
- Menu Produk - Menampilkan 10 varian teh unggulan dengan harga
- Responsive Design - Tampilan yang optimal di semua perangkat (desktop, tablet, mobile)
- Footer Informatif - Informasi kontak, jam operasional, dan lokasi dengan Google Maps
- Social Media Integration - Link ke Instagram Bakul Teh

## 🎨 Menu Teh Unggulan

1. Jasmine Tea - Rp 2.500
2. Lemon Tea - Rp 5.000
3. Apple Tea - Rp 5.000
4. Lychee Tea - Rp 6.000
5. Mango Tea - Rp 5.000
6. Blackcurrant Tea - Rp 5.000
7. Thai Tea - Rp 13.000
8. Lychee Tea Boba - Rp 19.000
9. Teh Oolong Murni - Rp 17.000
10. Sparkling Hibiscus Tea - Rp 18.000

## 🛠 Teknologi yang Digunakan

- HTML5 - Struktur halaman web
- CSS3 - Styling dan layout
- Bootstrap 5.3.3 - Framework CSS untuk responsive design
- Bootstrap Icons - Icon library
- Google Maps Embed - Integrasi peta lokasi

## 📁 Struktur Folder


Tugas_RPL/
├── index.html              # File HTML utama
├── Images/                 # Folder untuk gambar
│   ├── logo.png           # Logo Bakul Teh
│   ├── header.jpg         # Background hero section
│   └── lemontea.png       # Gambar menu produk
└── README.md              # File dokumentasi ini


## 🚀 Cara Menjalankan

### Metode 1: Langsung di Browser
1. Download atau clone repository ini
2. Buka file index.html dengan browser (Chrome, Firefox, Edge, dll)
3. Website akan langsung terbuka dan dapat dilihat

### Metode 2: Menggunakan Live Server (Recommended)
1. Install extension Live Server di VS Code
2. Klik kanan pada file index.html
3. Pilih "Open with Live Server"
4. Website akan terbuka di browser dengan auto-reload

### Metode 3: Menggunakan Local Server
bash
# Menggunakan Python
python -m http.server 8000

# Atau menggunakan Node.js (http-server)
npx http-server

Kemudian buka http://localhost:8000 di browser.

## 📍 Informasi Lokasi

Alamat: Jl. Panglima Polim, Kidul Rel Kereta Api  
Koordinat: -7.16193968333937, 111.87823209316595  
Telepon: 0857-0449-7669  
Jam Operasional: Senin - Minggu, 09:00 - 21:00  

## 🔗 Social Media

- Instagram: [@bakulteh.indonesia](https://www.instagram.com/bakulteh.indonesia)

## 📝 Customization

### Mengganti Logo
1. Siapkan file logo (format PNG/JPG)
2. Letakkan di folder Images/
3. Update path di file index.html:
html
<img src="./Images/nama-logo-baru.png" alt="Logo">


### Mengganti Background Hero Section
1. Siapkan gambar background (minimal 1920x1080px)
2. Letakkan di folder Images/
3. Update CSS di bagian .hero-section:
css
background: linear-gradient(...), url('./Images/nama-background-baru.jpg') ...


### Mengganti Warna Tema
Update variabel CSS di bagian <style>:
css
:root {
    --bs-tea-primary: #006400;    /* Hijau Tua */
    --bs-tea-secondary: #3CB371;  /* Hijau Sedang */
}


### Update Google Maps
1. Dapatkan koordinat lokasi dari Google Maps
2. Update di bagian iframe Google Maps:
html
src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d...!2d[LONGITUDE]!3d[LATITUDE]..."


## 🎯 To-Do / Pengembangan Selanjutnya

- [ ] Tambah fitur order online
- [ ] Integrasi dengan WhatsApp Business
- [ ] Tambah halaman gallery/testimoni
- [ ] Implementasi shopping cart
- [ ] Tambah fitur dark mode
- [ ] SEO optimization
- [ ] Performance optimization

## 👨‍💻 Developer

Website ini dikembangkan untuk Bakul Teh Indonesia

## 📄 Lisensi

Copyright © 2025 Bakul Teh. Semua Hak Dilindungi.

## 🤝 Kontribusi

Untuk saran atau feedback, silakan hubungi:
- Email: info@bakulteh.com (jika ada)
- Instagram: [@bakulteh.indonesia](https://www.instagram.com/bakulteh.indonesia)

---

Dibuat dengan ❤ untuk Pecinta Teh 🍵
