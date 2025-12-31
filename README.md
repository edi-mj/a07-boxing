# A07 Boxing

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Website pemesanan tiket pertandingan tinju yang dikembangkan sebagai tugas aplikasi mata kuliah Dasar Pemrograman Web. Proyek ini menyajikan informasi seputar dunia tinju dan menyediakan fitur pemesanan tiket untuk berbagai pertandingan boxing.

## Fitur Utama

- **Homepage** - Informasi sejarah boxing dan profil petinju legendaris dunia
- **Pemesanan Tiket** - Form interaktif untuk membeli tiket pertandingan dengan validasi JavaScript
- **Halaman Evaluasi** - Dokumentasi spesifikasi dan checklist pengerjaan proyek
- **Tentang Kami** - Informasi tim pengembang dan pembagian tugas

## Struktur Proyek

```
a07-boxing/
├── index.html           # Halaman utama
├── order.html           # Halaman pemesanan tiket
├── evaluation.html      # Halaman evaluasi proyek
├── about_us.html        # Halaman tentang tim
├── script.js            # Validasi form pemesanan
├── styles/              # File CSS untuk styling
│   ├── style.css        # Global styling
│   ├── index.css        # Styling homepage
│   ├── order.css        # Styling form pemesanan
│   ├── evaluation.css   # Styling halaman evaluasi
│   └── about_us.css     # Styling halaman about us
└── images/              # Asset gambar dan logo
```

## Teknologi yang Digunakan

- **HTML5** - Struktur dan markup halaman web
- **CSS3** - Styling dan layout responsif menggunakan Grid dan Flexbox
- **JavaScript** - Validasi form dan interaktivitas halaman

## Cara Menjalankan

1. Clone repository ini

   ```bash
   git clone https://github.com/edi-mj/a07-boxing.git
   ```

2. Buka file `index.html` menggunakan browser favorit Anda

3. Navigasi ke halaman lain melalui menu yang tersedia

## Validasi Form

Form pemesanan tiket dilengkapi dengan validasi JavaScript untuk:

- Nama lengkap (minimal 3 karakter, hanya huruf)
- Nomor telepon (minimal 10 digit, hanya angka)
- Pemilihan tiket pertandingan
- Jumlah tiket (maksimal 5 tiket per transaksi)
- Alamat lengkap
- Email format yang valid
- Kode promo (opsional)

## Demo

Kunjungi halaman demo: [A07 Boxing](https://edi-mj.github.io/a07-boxing/)

## Tim Pengembang

**Dasar Pemrograman Web IF 2A - DPW2023-2-A07**

| Nama                    | NIM          | Tugas            |
| ----------------------- | ------------ | ---------------- |
| Maulana Ardiansyah      | 230411100159 | Homepage         |
| Muhammad Junaidi        | 230411100171 | Halaman Form     |
| Angger Maulana Effendi  | 230411100155 | Halaman Evaluasi |
| Restu Ishariyadi Ya'Qub | 230411100162 | Halaman About Us |

## Catatan

Proyek ini dibuat untuk keperluan akademik dengan fokus pada validasi form client-side menggunakan JavaScript. Tampilan website tidak dioptimalkan untuk berbagai perangkat (non-responsive).

## Lisensi

Proyek ini dibuat untuk keperluan akademik mata kuliah Dasar Pemrograman Web semester genap 2023-2024.

---

Dibuat dengan semangat belajar oleh Tim A07
