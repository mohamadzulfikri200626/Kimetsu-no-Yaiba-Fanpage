# Kimetsu no Yaiba Fan Page

Mini Project Front End Basic
Mohamad Zul Fikri, D3 Sistem Informasi, UPN Veteran Jakarta

## Tentang project ini

Jadi ini tuh website fan page tentang anime Kimetsu no Yaiba (Demon Slayer) yang dibuat pakai HTML dan CSS aja, tanpa JavaScript dan tanpa framework. Isinya cerita singkat, fakta, karakter, galeri, rekomendasi, dan lagu soundtrack. Nah, ada juga halaman profil buat memperkenalkan pembuatnya.

Teks di halaman utama pakai bahasa Inggris karena ceritanya diambil dari Wikipedia versi Inggris. Kalau halaman profil, pakai bahasa Indonesia.

## Halaman

- `index.html` adalah halaman utama yang isinya informasi tentang anime.
- `profile.html` adalah halaman profil pembuat: foto, nama dan program studi, deskripsi singkat, skill, kontak, dan tombol kembali ke halaman utama.
- `login.html` adalah halaman login bertema Demon Slayer Corps. Ini cuma tampilan, jadi username dan password nggak dicek dan nggak disimpan.

## Isi halaman utama

Kalau dibuka dari atas, urutannya begini. Pertama ada header dengan menu navigasi, lalu hero yang pakai video sebagai background. Setelah itu ada About (cerita singkat), Anime Facts (daftar fakta dan tabel informasi), dan Characters yang isinya 8 card karakter. Berikutnya ada Gallery, tiga card Recommendations, dan Music yang punya pemutar audio untuk 1 lagu saja yang dapat dimainkan, dikarenakan github hanya bisa mengupload maksimal 20mb saja. Barulah di bagian bawah ada form ulasan (cuma tampilan, nggak ngirim data) dan footer.

## Struktur folder

```
MP_MohamadZulfikri/
├── index.html
├── profile.html
├── login.html
├── README.md
├── css/
│   └── style.css
└── assets/
    ├── images/   gambar karakter, galeri (gallery-1 sampai 4), rekomendasi (rec-1 sampai 3)
    ├── video/    infinity-castle.mp4 (background hero)
    └── audio/    1 lagu untuk bagian Music yang berfungsi
```

File halaman ditaruh di luar, CSS di folder `css`, dan semua media di folder `assets`. Jadi kalau mau cari file, tinggal lihat folder sesuai jenisnya.


## Sumber dan hak cipta

- Cerita dan deskripsi karakter diparafrasekan dari Wikipedia (lisensi CC BY-SA).
- Ini fan project nonresmi dan nggak berafiliasi dengan Koyoharu Gotouge, SHUEISHA, Aniplex, maupun Ufotable.
- Gambar, video, dan lagu milik pemegang hak ciptanya masing-masing.

## Pembuat

Mohamad Zul Fikri
