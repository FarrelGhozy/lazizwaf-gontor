# 🏗️ RANCANGAN WEBSITE — LAZISWAF UNIDA Gontor (Astro v7)

> **Proyek:** Website Profil Lembaga Amil Zakat, Infak, Sedekah, dan Wakaf (LAZISWAF) Universitas Darussalam (UNIDA) Gontor
> **Stack:** 🚀 **Astro v7.1.1** — Static Site Generator
> **Lokasi:** `/home/master_core_ti/projects/lazizwaf-gontor/`

---

## 📋 Informasi Lembaga

| Item | Detail |
|------|--------|
| **Nama Resmi** | LAZISWAF Universitas Darussalam Gontor |
| **Didirikan** | 10 September 2010 | 
| **SK Rektor** | 8 April 2013 |
| **IG** | @laziswaf.unidagontor (1.225+ Followers, 279 Postingan) |
| **IG Putri** | @laziswaf.unidaputri (629 Followers, 181 Postingan) |
| **Lokasi** | Jl. Raya Siman, Demangan, Siman, Ponorogo, Jawa Timur 63471 |

### Program Unggulan
1. 🎓 **Beasiswa Minhati** — Beasiswa mahasiswa/i & santri kurang mampu
2. 📖 **Wakaf Al-Qur'an** — Penyaluran mushaf ke lembaga pendidikan
3. 🤝 **Bantuan Kemanusiaan** — Donasi korban bencana (Aceh, Sumatera)
4. 📢 **Sosialisasi ZISWAF** — Edukasi zakat, infak, sedekah, wakaf
5. 📦 **Bantuan Logistik** — Sembako & kebutuhan pokok

---

## 🚀 Astro v7 — Project Structure

```ascii
lazizwaf-gontor/
│
├── src/
│   ├── pages/              ← Halaman website (file .astro)
│   │   ├── index.astro     ← Beranda
│   │   ├── tentang.astro   ← Profil & Sejarah
│   │   ├── program.astro   ← Program Unggulan
│   │   ├── kegiatan.astro  ← Berita & Kegiatan
│   │   └── kontak.astro    ← Kontak & Maps
│   │
│   ├── layouts/            ← Layout template (navbar + footer)
│   │   └── BaseLayout.astro
│   │
│   ├── components/         ← Komponen reusable
│   │   ├── Navbar.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── CardProgram.astro
│   │   ├── CardKegiatan.astro
│   │   ├── Gallery.astro
│   │   ├── Stats.astro
│   │   └── CTASection.astro
│   │
│   └── styles/             ← CSS global
│       └── global.css
│
├── public/                 ← Static assets
│   └── favicon.svg
│
├── assets/                 ← Images & data
│   ├── images/             ← Foto dokumentasi (8 file)
│   │   ├── wakaf-quran-50-mushaf.jpg    (183KB)
│   │   ├── pelantikan-pengurus.jpg      (77KB)
│   │   ├── sosialisasi-ziswaf.jpg       (54KB)
│   │   ├── bantuan-aceh.jpg             (126KB)
│   │   ├── doortodoor-laziswaf.jpg      (35KB)
│   │   ├── donasi-sumatera.jpg          (152KB)
│   │   └── sedekah-shubuh.jpg           (171KB)
│   └── css/
│
├── package.json
├── astro.config.mjs
└── RANCANGAN.md            ← Kamu di sini
```

---

## 🎨 Desain & Tema

### Tema: 🌿 Islamic Green (Emerald Premium)

```css
:root {
  --green-50:  #f0fdf4;
  --green-100: #dcfce7;
  --green-200: #bbf7d0;
  --green-500: #10b981;   /* Emerald accent */
  --green-600: #059669;   /* Primary */
  --green-700: #047857;   /* Dark */
  --green-900: #064e3b;
  
  --emerald:   #059669;
  --gold:      #d4a843;
  
  --text-primary: #1b4332;
  --text-secondary: #2d6a4f;
  --text-muted: #6b8f7c;
  
  --bg-primary: #f0f7f4;
  --bg-card: #ffffff;
  --bg-dark: #0d2818;
}
```

### Font
- **Display:** `'Plus Jakarta Sans'` — modern, premium
- **Body:** `'Inter'` — readable, profesional
- **Arab:** `'Amiri'` — untuk kutipan

### Gaya
- Clean minimalis dengan white space longgar
- Emerald green accent + gold untuk premium touch
- Glassmorphism navbar
- Card shadow lembut dengan hover lift
- Animasi scroll reveal (fade-in up, stagger)
- Hero dengan gradient overlay

---

## 📸 Gambar Terkumpul (8 File)

| File | Deskripsi | Sumber | Ukuran |
|------|-----------|--------|--------|
| wakaf-quran-50-mushaf.jpg | Penyaluran 50 mushaf Al-Qur'an ke SMPN | IG LAZISWAF | 183KB |
| pelantikan-pengurus.jpg | Pelantikan Pengurus LAZISWAF 1447 H | IG LAZISWAF | 77KB |
| sosialisasi-ziswaf.jpg | Sosialisasi ZISWAF Kampus Putri | IG LAZISWAF | 54KB |
| bantuan-aceh.jpg | Bantuan kemanusiaan Aceh/Takengon | IG LAZISWAF | 126KB |
| donasi-sumatera.jpg | Donasi untuk korban bencana Sumatera | IG LAZISWAF | 152KB |
| doortodoor-laziswaf.jpg | Program Door-to-Door penghimpunan donasi | IG LAZISWAF | 35KB |
| sedekah-shubuh.jpg | Poster Sedekah Subuh | IG LAZISWAF | 171KB |

---

## ✅ Status Pengerjaan

- [x] **Step 1:** Rancangan MD dibuat ✅
- [x] **Step 2:** Gambar dokumentasi dari IG (7 foto) ✅
- [x] **Step 2:** Stack final: Astro v7.1.1 ✅
- [x] **Step 2:** Proyek Astro sudah di-setup ✅
- [ ] **Step 3:** Coding website (siap dimulai) ⬅️

## 🏁 Cara Jalankan

```bash
cd ~/projects/lazizwaf-gontor

# Development
npm run dev          # Buka di http://localhost:4321

# Build untuk production
npm run build        # Output di dist/

# Preview build
npm run preview
```
