# Creatify 💌

**Landing page untuk layanan undangan digital** — dibuat dengan HTML, CSS, dan JavaScript murni. Tidak ada dependency, tidak ada build tool, langsung bisa dibuka di browser.

![Preview](https://img.shields.io/badge/status-live-brightgreen?style=flat-square)
![HTML](https://img.shields.io/badge/HTML-single--file-blue?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)

---

## ✦ Fitur

- Desain elegan dengan palet biru lembut
- Animasi halus saat halaman dimuat
- Tab switching: **Undangan Digital** & **App**
- Responsive untuk mobile dan desktop
- Zero dependency — tidak perlu npm, webpack, dll

---

## 🚀 Cara Pakai

### Buka langsung di browser
```bash
# Clone repo
git clone https://github.com/USERNAME/creatify.git

# Buka file
open creatify-blue.html
```

### Deploy ke GitHub Pages
1. Push ke branch `main`
2. Masuk ke **Settings → Pages**
3. Source: `Deploy from a branch` → pilih `main` → folder `/ (root)`
4. Klik **Save** — situsmu akan live di `https://USERNAME.github.io/creatify/`

---

## 📁 Struktur File

```
creatify/
├── creatify-blue.html   # Halaman utama (single file)
├── README.md            # Dokumentasi ini
├── LICENSE              # MIT License
└── .gitignore           # File yang diabaikan Git
```

---

## 🛠 Kustomisasi

Edit langsung di `creatify-blue.html`:

| Bagian | Lokasi di file |
|--------|----------------|
| Nama & tagline | `<div class="top">` |
| Teks kartu Undangan | `<div class="hero-card">` |
| Teks kartu App | `<div class="app-card">` |
| Warna tema | `:root { --blue: ... }` |
| Font | `<link href="...googleapis...">` |

---

## 📄 Lisensi

Didistribusikan di bawah [MIT License](LICENSE).  
© 2025 Creatify
