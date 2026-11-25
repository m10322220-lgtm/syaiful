# Muhamad Syaiful Islam — Creative & Graphic Design Portfolio

Portofolio web pribadi **Muhamad Syaiful Islam**, seorang siswa **Desain Komunikasi Visual (DKV) SMKN 10 Surabaya**. Website ini menampilkan kurasi karya seni rupa dasar, nirmana, ilustrasi manual (zentangle, pointillism), 3D modeling, identitas merek (branding), serta desain publikasi organisasi.

---

## 🎨 Fitur Utama
- **Desain Editorial & Minimalis Modern**: Terinspirasi oleh gaya editorial kreatif dengan skema warna hangat (`cream`, `charcoal`, `terracotta`).
- **Kurasi 15+ Karya Lengkap**: Terbagi menjadi kategori *School Work* dan *Organizational Work*.
- **Modal Detail Interaktif**: Klik pada kartu karya apa pun untuk membuka popup detail lengkap, deskripsi mendalam, alat/software yang digunakan, serta tampilan visual karya beresolusi penuh.
- **Filter Kategori**: Tombol cepat untuk memfilter tampilan antara Semua Karya, Sekolah, dan Organisasi.
- **Kustomisasi Foto Profil**: Fitur interaktif di bagian hero untuk mengunggah atau mengganti foto profil langsung di browser.
- **Responsif Sepenuhnya**: Dioptimalkan untuk tampilan desktop, tablet, dan *mobile*.

---

## 🛠️ Tech Stack
- **HTML5 & Vanilla JavaScript** (Tanpa framework berat, performa super cepat).
- **Tailwind CSS (via CDN)** untuk utility-first styling.
- **Font Awesome 6** untuk ikon UI & media sosial.
- **Google Fonts** (*Anton*, *Oswald*, *Plus Jakarta Sans*, *Caveat*).

---

## 🚀 Cara Menjalankan Lokal (Local Preview)
Karena menggunakan aset gambar lokal, beberapa browser memerlukan server lokal (local server) agar fitur interaktif dan gambar termuat dengan sempurna (mencegah pembatasan CORS file://).

1. Clone atau unduh repository ini:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
   ```
2. Jalankan server lokal:
   - **Python 3:**
     ```bash
     python -m http.server 8000
     ```
   - **Node.js (npx):**
     ```bash
     npx serve
     ```
   - **VS Code:** Gunakan ekstensi **Live Server**, klik kanan pada `index.html`, lalu pilih *Open with Live Server*.
3. Buka browser di `http://localhost:8000` (atau port yang tertera).

---

## 🌐 Cara Publikasi di GitHub Pages (Siap Online!)
Repository ini sudah dikonfigurasi agar langsung siap di-deploy ke **GitHub Pages** (terdapat file `.nojekyll` dan `.gitignore` untuk membersihkan file mentah yang tidak perlu).

### Metode A: Melalui Website GitHub (Tanpa Git CLI)
1. Buat repository baru di [GitHub](https://github.com/new) (misal: `portofolio-syaiful`).
2. Masuk ke halaman repository tersebut, lalu klik tombol **Add file** -> **Upload files**.
3. Tarik dan lepas (*drag & drop*) seluruh file proyek (kecuali folder `Downloads` dan file PDF mentah) ke area upload.
4. Klik **Commit changes**.
5. Setelah terunggah:
   - Buka tab **Settings** di repository Anda.
   - Di menu sebelah kiri, klik **Pages**.
   - Pada bagian **Build and deployment** -> **Branch**, pilih `main` (atau `master`) dan folder `/ (root)`, lalu klik **Save**.
   - Tunggu 1–2 menit, URL publik situs Anda akan muncul di bagian atas halaman Pages!

### Metode B: Melalui Git CLI (Terminal)
Jika Anda memiliki Git terinstal di komputer:
```bash
git init
git add .
git commit -m "Initial commit: Portofolio Muhamad Syaiful Islam ready"
git branch -M main
git remote add origin https://github.com/username/repository-name.git
git push -u origin main
```
Lalu aktifkan GitHub Pages di tab *Settings* -> *Pages* seperti pada Langkah A5.

---

## 📬 Kontak & Sosial Media
- **Email:** sayaifulislam16@gmail.com
- **WhatsApp:** [0857-3211-7191](https://wa.me/6285732117191)
- **Instagram:** [@m.saaiffffff](https://instagram.com/m.saaiffffff)
- **Instansi:** SMKN 10 Surabaya (DKV)

---
© 2026 Muhamad Syaiful Islam. All rights reserved.
