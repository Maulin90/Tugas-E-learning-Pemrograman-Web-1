# Cooking Master

Cooking Master adalah aplikasi belajar memasak yang memungkinkan pengguna untuk menemukan resep dan tutorial memasak.

## Instalasi
Unduh Bootstrap dari [sini](https://getbootstrap.com/docs/5.3/getting-started/download/).
Unduh Background yang telah disediakan.

### Menggunakan CDN
Proyek ini menggunakan Bootstrap melalui CDN. Pastikan Anda terhubung ke internet saat menjalankan aplikasi ini. Tidak perlu mengunduh file Bootstrap.

### Menggunakan File Lokal
Saya menggunakan Bootstrap secara lokal:
1. Pastikan Anda memiliki file Bootstrap yang diperlukan di dalam folder `bootstrap-5.3.3-dist`.
2. Tempatkan folder `css` dan `js` ke dalam folder proyek.
3. Ubah referensi di file HTML menjadi seperti berikut:
    ```html
    <link href="bootstrap/css/bootstrap.min.css" rel="stylesheet">
    <script src="bootstrap/js/bootstrap.bundle.min.js"></script>
    ```

## Cara Menjalankan

1. Clone repository ini ke lokal Anda.
2. Buka file `index.html` menggunakan browser Anda.

## Struktur Folder

- `index.html` - Halaman utama aplikasi.
- `login.html` - Halaman login pengguna.
- `register.html` - Halaman pendaftaran pengguna.
- `dashboard.html` - Halaman dashboard setelah login.
- `/bootstrap-5.3.3-dist` - Folder yang berisi file Bootstrap lokal.
- `/background` - Folder yang berisi gambar latar belakang.

