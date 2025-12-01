# Verda Nusadaya - Website Statis

Website statis untuk PT. Verda Nusadaya - Perusahaan Agroindustri Terpercaya

## 📁 Struktur Folder

```
static-website/
├── css/
│   └── style.css              # File CSS utama
├── js/
│   └── main.js                # File JavaScript untuk interaksi
├── images/
│   └── (gambar-gambar)        # Folder untuk gambar
├── index.html                 # Halaman Beranda
├── about.html                # Halaman Tentang Kami
├── products.html              # Halaman Produk
├── contact.html               # Halaman Kontak
├── robots.txt                 # File robots.txt untuk SEO
├── sitemap.xml                # File sitemap.xml untuk SEO
└── README.md                 # Dokumentasi ini
```

## 🌐 Halaman Website

### 1. Halaman Beranda (`index.html`)
- **Hero Banner**: Gambar besar dengan slogan dan tombol CTA
- **Tentang Perusahaan**: Ringkasan profil dengan 3 fitur utama
- **Produk Unggulan**: 6 produk dengan gambar, nama, deskripsi, dan harga
- **Testimoni**: 3 testimoni pelanggan dengan rating
- **Partner**: Logo mitra perusahaan
- **Call to Action**: Tombol besar untuk menghubungi kami

### 2. Halaman Tentang Kami (`about.html`)
- **Hero Section**: Judul dan deskripsi singkat
- **Profil Perusahaan**: Informasi lengkap tentang perusahaan
- **Visi & Misi**: Tujuan dan misi perusahaan
- **Nilai-Nilai**: 6 nilai perusahaan dengan ikon
- **Sejarah**: Timeline perkembangan perusahaan
- **Tim**: 6 profil anggota tim
- **Sertifikat**: 6 sertifikat dan penghargaan

### 3. Halaman Produk (`products.html`)
- **Hero Section**: Judul dan deskripsi halaman produk
- **Produk Unggulan**: 3 produk unggulan dengan detail lengkap
- **Filter Produk**: 
  - Search bar untuk mencari produk
  - Filter kategori (Kopi, Karet, Kelapa Sawit, Lainnya)
  - Toggle view (Grid/List)
- **Daftar Produk**: 12 produk dengan:
  - Gambar produk
  - Nama dan deskripsi
  - Rating bintang
  - Spesifikasi produk
  - Harga
  - Tombol detail dan beli
- **Download Katalog**: Tombol untuk download katalog PDF

### 4. Halaman Kontak (`contact.html`)
- **Hero Section**: Judul dan deskripsi halaman kontak
- **Info Kontak**: 4 kartu informasi (alamat, telepon, email, jam operasional)
- **Form Kontak**: Form lengkap dengan:
  - Nama lengkap
  - Email
  - Nomor telepon
  - Perusahaan
  - Produk yang diminati
  - Subjek
  - Pesan
- **Google Maps**: Peta lokasi perusahaan
- **Quick Contact**: Informasi kontak langsung
- **Social Media**: Link media sosial
- **FAQ**: 5 pertanyaan yang sering diajukan

## 🎨 Fitur Desain

### Responsive Design
- **Mobile First**: Desain dioptimalkan untuk perangkat mobile
- **Breakpoints**: 
  - Mobile: < 768px
  - Tablet: 768px - 1024px
  - Desktop: > 1024px
- **Navigation**: Menu responsif dengan hamburger menu untuk mobile

### Animasi & Interaksi
- **Hover Effects**: Efek hover pada cards dan tombol
- **Smooth Scrolling**: Scroll halus untuk anchor links
- **Loading States**: Spinner untuk proses loading
- **Form Validation**: Validasi form kontak
- **Image Lazy Loading**: Loading gambar secara bertahap

### Warna & Branding
- **Primary Color**: Green (#16a34a)
- **Secondary Color**: Gray shades
- **Accent Color**: Yellow untuk badges
- **Typography**: Font sistem yang clean dan modern

## 🔧 Teknologi

### HTML5
- Semantic HTML
- Meta tags untuk SEO
- Open Graph tags
- Structured Data (JSON-LD)

### CSS3
- Flexbox & Grid Layout
- Custom Properties
- Media Queries
- Animasi CSS
- Custom scrollbar

### JavaScript (Vanilla)
- ES6+ Features
- Event Listeners
- DOM Manipulation
- Form Handling
- Local Storage (opsional)

## 🚀 Cara Menggunakan

### 1. Upload ke Hosting
Upload semua file dan folder ke hosting Anda:

```bash
# Upload semua file ke root directory hosting
static-website/
├── css/
├── js/
├── images/
├── index.html
├── about.html
├── products.html
├── contact.html
├── robots.txt
└── sitemap.xml
```

### 2. Konfigurasi
Edit file-file berikut sesuai kebutuhan:

- **Informasi Perusahaan**: Edit di semua halaman HTML
- **Kontak**: Update di halaman contact.html
- **Produk**: Modifikasi data produk di `js/main.js`
- **Gambar**: Ganti placeholder images di folder `images/`

### 3. SEO Optimization
- **Meta Tags**: Sudah dioptimalkan untuk setiap halaman
- **robots.txt**: Mengizinkan search engine mengindex
- **sitemap.xml**: Peta situs untuk search engine
- **Structured Data**: Schema.org markup untuk perusahaan

## 📱 Browser Support

Website ini mendukung:
- ✅ Chrome (versi terbaru)
- ✅ Firefox (versi terbaru)
- ✅ Safari (versi terbaru)
- ✅ Edge (versi terbaru)
- ✅ Opera (versi terbaru)
- ✅ Mobile browsers

## 🎯 Fitur Unggulan

### Performance
- **Optimized Images**: Gambar dikompres dan dioptimalkan
- **Minimal CSS**: CSS yang efisien dan terorganisir
- **Lazy Loading**: Loading gambar hanya saat diperlukan
- **No Dependencies**: Tidak memerlukan library eksternal

### User Experience
- **Fast Loading**: Waktu loading yang cepat
- **Intuitive Navigation**: Navigasi yang mudah dipahami
- **Mobile Friendly**: Tampilan optimal di mobile
- **Accessibility**: Semantic HTML dan ARIA labels

### Business Features
- **Contact Form**: Form kontak yang fungsional
- **Product Catalog**: Katalog produk lengkap
- **Search & Filter**: Pencarian dan filter produk
- **Social Proof**: Testimoni dan partner logos

## 🔄 Customization

### Mengubah Warna
Edit file `css/style.css` dan ubah CSS variables:

```css
:root {
  --primary-color: #16a34a;
  --secondary-color: #6b7280;
  --accent-color: #eab308;
}
```

### Menambah Produk
Edit file `js/main.js` dan tambahkan data produk:

```javascript
const products = [
  {
    id: 13,
    name: "Nama Produk Baru",
    category: "kategori",
    description: "Deskripsi produk",
    image: "path/to/image.jpg",
    price: "Rp harga",
    rating: 4.5,
    specs: ["spec1", "spec2"]
  }
];
```

### Mengubah Informasi Perusahaan
Edit HTML di setiap halaman untuk mengubah:
- Nama perusahaan
- Alamat
- Telepon
- Email
- Deskripsi

## 📞 Dukungan

Untuk bantuan atau pertanyaan:
- 📧 Email: info@verdanusadaya.com
- 📞 Telepon: +62 812-3456-7890
- 🌐 Website: https://imammakbul166.github.io/VerdaNusadaya/

## 📄 Lisensi

Website ini dikembangkan untuk PT. Verda Nusadaya. Hak cipta © 2024.

---

**Verda Nusadaya - Solusi Agroindustri Terpercaya**