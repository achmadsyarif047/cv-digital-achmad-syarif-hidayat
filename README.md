# CV Digital - Achmad Syarif Hidayat

Website Curriculum Vitae (CV) Digital interaktif dan responsif yang dikembangkan menggunakan HTML5, CSS3 (Flexbox & CSS Grid), dikelola via GitHub, dan dikemas menggunakan Docker Container.

## Struktur Proyek
- `index.html` : Struktur utama halaman CV berbasis HTML semantik.
- `style.css` : Tata letak responsif (Flexbox & Grid), styling visual, dan animasi hover.
- `assets/` : Menyimpan aset foto profil dan gambar pendukung.
- `Dockerfile` : Konfigurasi kontainerisasi web server Nginx.

## Langkah Menjalankan Aplikasi Secara Lokal (Docker)

1. **Build Docker Image**
   ```bash
   docker build -t cv-digital-app .