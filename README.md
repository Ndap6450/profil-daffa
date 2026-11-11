# Web Profil — Daffa Nafiis Musyaffa

Tugas membuat web profil menggunakan **HTML & CSS** dengan layout **Flexbox**, lalu dipublikasikan melalui **GitHub** dan **Netlify**.

## Struktur proyek

```
profil-web/
├── index.html
├── css/
│   └── style.css
├── assets/          (opsional, untuk logo asli)
├── favicon.svg
└── README.md
```

## Menjalankan secara lokal

Buka `index.html` langsung di browser, atau jalankan server lokal:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000` di browser.

## Upload ke GitHub

Buat repository baru bernama `profil-daffa` di GitHub (jangan centang "Add a README file"), lalu jalankan:

```bash
git init
git add .
git commit -m "Tambah web profil"
git branch -M main
git remote add origin https://github.com/USERNAME/profil-daffa.git
git push -u origin main
```

Ganti `USERNAME` dengan username GitHub kamu.

## Deploy ke Netlify

1. Login ke <https://app.netlify.com> menggunakan akun GitHub.
2. Klik **Add new site** → **Import an existing project**.
3. Pilih **GitHub**, lalu pilih repo `profil-daffa`.
4. Build command: kosongkan. Publish directory: `.`
5. Klik **Deploy site**.
6. Buka **Site configuration** → **Change site name** untuk mengganti alamat menjadi misalnya `daffa-profil.netlify.app`.

## Checklist tugas

- [x] HTML semantik
- [x] CSS eksternal
- [x] Flexbox pada navbar, hero, data diri, hobi, kontak, dan footer
- [x] Responsif (media query 820px dan 640px)
- [x] Data diri lengkap
- [ ] Upload ke GitHub
- [ ] Deploy ke Netlify
- [ ] Kirim link ke dosen

## Catatan

- Logo NDAP dibuat dengan HTML/CSS: teks miring di dalam bingkai hitam dengan bayangan abu-abu, menyerupai logo asli tanpa memakai file gambar.
- Folder `assets/` disiapkan kalau nanti ingin memakai file logo asli.
- Data yang bisa diubah ada di `index.html` (teks) dan `css/style.css` (warna di bagian `:root`).
- Web ini tidak memakai JavaScript atau framework, hanya HTML dan CSS.
