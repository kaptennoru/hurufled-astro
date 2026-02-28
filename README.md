# HurufLED - Website Astro

Website landing page untuk HurufLED, dibuat dengan Astro framework.

## 📁 Struktur Project

```
hurufled-astro/
├── src/
│   ├── components/
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── About.astro
│   │   ├── Portfolio.astro
│   │   ├── Testimonials.astro
│   │   ├── CTA.astro
│   │   ├── FAQ.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro
│   │   └── 404.astro
│   └── styles/
│       └── global.css
├── public/
├── astro.config.mjs
├── package.json
├── vercel.json
└── .gitignore
```

## 🚀 Cara Upload ke GitHub

### 1. Install Git (jika belum ada)
Download dari: https://git-scm.com/downloads

### 2. Buat Repository di GitHub
- Buka https://github.com
- Klik tombol **"New"** (hijau) di pojok kanan atas
- Isi nama repository: `hurufled-astro`
- Pilih **Public** atau **Private**
- Klik **"Create repository"**

### 3. Upload via Terminal/Command Prompt

Buka Terminal (Mac/Linux) atau Command Prompt/PowerShell (Windows):

```bash
# 1. Masuk ke folder project
cd hurufled-astro

# 2. Inisialisasi git
git init

# 3. Tambahkan semua file
git add .

# 4. Commit pertama
git commit -m "Initial commit - HurufLED website"

# 5. Hubungkan ke repository GitHub (ganti USERNAME dengan username GitHub Anda)
git remote add origin https://github.com/USERNAME/hurufled-astro.git

# 6. Push ke GitHub
git branch -M main
git push -u origin main
```

✅ File sudah terupload ke GitHub!

---

## 🌐 Cara Deploy ke Vercel

### Metode 1: Via Vercel Dashboard (Termudah)

1. Buka https://vercel.com
2. Klik **"Sign Up"** → pilih **"Continue with GitHub"**
3. Authorize Vercel untuk akses GitHub
4. Di dashboard Vercel, klik **"Add New... → Project"**
5. Cari dan pilih repository `hurufled-astro`
6. Klik **"Import"**
7. Vercel otomatis mendeteksi Astro framework
8. Klik **"Deploy"**
9. Tunggu ~1-2 menit → website sudah live! 🎉

### Metode 2: Via Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy (dari dalam folder project)
cd hurufled-astro
vercel

# Ikuti instruksi di terminal
# Pilih: "Link to existing project?" → No
# Set up project settings (enter semua default)
```

---

## 🔄 Update Website

Setiap kali Anda mengubah file dan push ke GitHub, Vercel otomatis mendeploy ulang:

```bash
# Edit file, lalu:
git add .
git commit -m "Update konten website"
git push
```

Vercel akan otomatis deploy dalam ~1-2 menit!

---

## 🖊️ Cara Edit Konten

### Ganti nomor WhatsApp:
Cari teks `bit.ly/cs-hurufled` di semua file `.astro` dan ganti dengan link WA Anda.

### Ganti nomor telepon:
Cari `081219136929` dan ganti dengan nomor Anda.

### Ganti email:
Cari `ledhuruf@gmail.com` dan ganti dengan email Anda.

### Ganti alamat:
Edit di `Contact.astro` dan `Footer.astro`.

### Tambah/hapus layanan:
Edit array `services` di `Services.astro`.

### Tambah foto portfolio:
Edit array `items` di `Portfolio.astro` - ganti URL gambar dengan foto produk Anda.

---

## 🛠️ Development Lokal

```bash
# Install dependencies
npm install

# Jalankan development server
npm run dev

# Buka browser: http://localhost:4321
```

---

## 📱 Domain Kustom di Vercel

1. Di Vercel Dashboard → pilih project Anda
2. Klik **"Settings"** → **"Domains"**
3. Ketik domain Anda (misal: `hurufled2.com`)
4. Klik **"Add"**
5. Ikuti instruksi untuk set DNS di registrar domain Anda
