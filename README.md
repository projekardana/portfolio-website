# Muhammad Dendi Ardana | Personal Portfolio

Personal portfolio website untuk memperkenalkan latar belakang, area teknologi, proyek, dan cara menghubungi Muhammad Dendi Ardana. Situs ini dirancang sebagai profil profesional yang ringkas, responsif, dan mudah dikembangkan menggunakan teknologi web dasar.

## Gambaran Proyek

Website satu halaman ini menyajikan perjalanan dan fokus profesional di bidang software engineering, data engineering, AI, serta sistem dan infrastruktur. Konten disusun agar pengunjung dapat memahami profil, kompetensi, dan contoh pekerjaan melalui navigasi bagian yang jelas.

Proyek dibuat tanpa framework atau dependensi eksternal. Struktur ini menjaga situs tetap ringan dan membuat fondasi front-end-nya mudah dipelajari, ditinjau, dan disesuaikan.

## Fitur

- Layout responsif untuk desktop dan layar yang lebih kecil.
- Navigasi menuju bagian About, Background, Focus, Work, dan Contact.
- Menu navigasi yang dapat dibuka pada layar mobile.
- Animasi reveal saat konten masuk ke viewport menggunakan `IntersectionObserver`.
- Bagian profil, perjalanan profesional, fokus teknologi, proyek pilihan, kompetensi, filosofi kerja, dan kontak.
- Tautan kontak melalui email, LinkedIn, GitHub, serta tautan proyek yang tersedia.
- Metadata dasar untuk judul halaman, deskripsi, dan warna tema browser.

## Teknologi

- HTML5 untuk struktur dan konten halaman.
- CSS3 untuk layout, styling, animasi, dan breakpoint responsif.
- JavaScript tanpa framework untuk interaksi menu dan animasi saat scroll.

Tidak diperlukan package manager, proses build, atau instalasi dependensi.

## Menjalankan Secara Lokal

Cara paling sederhana adalah membuka `index.html` di browser. Untuk menguji melalui server lokal, jalankan perintah berikut dari direktori proyek:

```bash
python -m http.server 8000
```

Kemudian buka [http://localhost:8000](http://localhost:8000) di browser.

## Struktur Proyek

```text
.
├── index.html   # Konten dan struktur halaman
├── style.css    # Gaya visual dan aturan responsif
├── script.js    # Interaksi menu dan animasi reveal
├── profile.png  # Foto profil
└── README.md    # Dokumentasi proyek
```

## Kustomisasi

1. Ubah profil, riwayat, proyek, dan informasi kontak di `index.html`.
2. Ganti `profile.png` dengan foto yang sesuai. Pertahankan nama berkas tersebut, atau sesuaikan atribut `src` pada elemen gambar di `index.html`.
3. Sesuaikan warna, tipografi, layout, dan breakpoint responsif di `style.css`.
4. Perbarui interaksi halaman di `script.js` jika menambahkan komponen yang memerlukan perilaku JavaScript.
5. Periksa kembali tautan eksternal dan alamat email sebelum memublikasikan situs.

## Deployment

Karena proyek ini merupakan situs statis, berkas-berkasnya dapat dipublikasikan melalui layanan hosting statis seperti GitHub Pages, Netlify, atau Vercel. Pastikan `index.html`, `style.css`, `script.js`, dan aset gambar berada pada jalur yang dapat diakses oleh halaman.

## Lisensi

Repositori ini belum menyertakan berkas lisensi. Hak penggunaan, modifikasi, dan distribusi belum ditetapkan secara eksplisit. Sebelum menerima kontribusi publik atau mengizinkan penggunaan ulang, tambahkan berkas `LICENSE` dengan lisensi open source yang dipilih oleh pemilik proyek.
