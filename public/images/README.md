# 📁 Panduan Folder Gambar - HurufLED

Letakkan gambar Anda di folder yang sesuai di bawah ini:

---

## 📂 Struktur Folder

```
public/images/
├── hero/           → Gambar utama di bagian atas halaman (hero section)
├── services/       → Foto produk per layanan (neon box, videotron, dll)
├── portfolio/      → Foto hasil pekerjaan / proyek yang sudah selesai
├── about/          → Foto tim, workshop, atau kantor
├── team/           → Foto anggota tim / karyawan
├── testimonials/   → Foto profil pelanggan (opsional)
└── logo/           → Logo perusahaan dalam berbagai format
```

---

## 📸 Panduan Per Folder

### `/hero/`
- **hero-main.jpg** — Foto produk terbaik untuk tampilan utama
- **hero-bg.jpg** — Opsional: foto background hero section
- Ukuran ideal: **1920 x 1080px** atau lebih
- Format: `.jpg` atau `.webp`

### `/services/`
Satu gambar per layanan:
- `neon-box.jpg`
- `videotron.jpg`
- `acrylic-led.jpg`
- `galvanill.jpg`
- `stainless.jpg`
- `billboard.jpg`
- `neonflex.jpg`
- `pylon-sign.jpg`
- Ukuran ideal: **800 x 600px**
- Format: `.jpg` atau `.webp`

### `/portfolio/`
Foto hasil pekerjaan (bebas banyak):
- `portfolio-1.jpg`, `portfolio-2.jpg`, dst.
- Atau beri nama deskriptif: `neonbox-restoran-bintaro.jpg`
- Ukuran ideal: **800 x 600px** (landscape)
- Format: `.jpg` atau `.webp`

### `/about/`
- `workshop.jpg` — Foto workshop/pabrik
- `team-photo.jpg` — Foto tim bersama
- `proses-produksi.jpg` — Foto proses pembuatan
- Ukuran ideal: **1200 x 800px**

### `/team/`
Foto per anggota tim:
- `owner.jpg`
- `tim-desain.jpg`
- `tim-produksi.jpg`
- Ukuran ideal: **400 x 400px** (square)

### `/testimonials/`
- Foto wajah pelanggan (opsional, bisa pakai avatar)
- Ukuran ideal: **150 x 150px** (square)

### `/logo/`
- `logo.png` — Logo utama dengan background transparan
- `logo-white.png` — Logo putih untuk background gelap
- `logo-dark.png` — Logo gelap untuk background terang
- `favicon.ico` atau `favicon.png` — Icon tab browser (32x32px)
- Format: `.png` dengan background transparan

---

## 💡 Tips Optimasi Gambar

1. **Kompres gambar** sebelum upload menggunakan:
   - https://squoosh.app (gratis, online)
   - https://tinypng.com (gratis, online)
   
2. **Gunakan format WebP** jika memungkinkan — lebih kecil, lebih cepat

3. **Ukuran file ideal**: di bawah 200KB per gambar untuk performa web yang baik

4. **Nama file**: gunakan huruf kecil, pisahkan dengan tanda `-` (contoh: `neon-box-resto.jpg`)
   - ✅ `neon-box-bintaro.jpg`
   - ❌ `Neon Box Bintaro.jpg`

---

## 🔧 Cara Ganti Gambar di Kode

Setelah meletakkan gambar di folder yang sesuai, buka file komponen dan ubah path gambar:

```astro
<!-- Contoh di Hero.astro -->
<img src="/images/hero/hero-main.jpg" alt="HurufLED Signage" />

<!-- Contoh di Services.astro -->
<img src="/images/services/neon-box.jpg" alt="Neon Box" />

<!-- Contoh di Portfolio.astro -->
<img src="/images/portfolio/portfolio-1.jpg" alt="Portfolio HurufLED" />
```

---

Jika ada pertanyaan, hubungi: ledhuruf@gmail.com
