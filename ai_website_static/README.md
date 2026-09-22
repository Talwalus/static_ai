# AI Learning Assistant (Static Version)

Versi **statis** (HTML + CSS + JS) yang bisa langsung di-upload ke:

- **GitHub Pages**
- **Vercel**
- **Netlify**
- Atau dibuka langsung di browser (double-click `index.html`)

Tidak perlu Python / Flask / server backend.

## Fitur
1. Tanya AI  
2. Jelaskan Materi  
3. Buat Ringkasan  
4. Buat Soal  
5. Keluar / Reset  

API Key dimasukkan oleh user saat membuka website (disimpan di sessionStorage).

## Cara pakai di GitHub Pages

1. Buat repository baru di GitHub
2. Upload file `index.html` (bisa taruh di root atau folder `docs`)
3. Settings → Pages → Source: Deploy from branch `main` (root)
4. Buka URL yang diberikan GitHub Pages

## Cara pakai di Vercel

1. Import repository GitHub
2. Framework Preset: **Other**
3. Build Command: kosongkan
4. Output Directory: `.` (titik) atau kosong
5. Deploy

## Catatan
- User memasukkan API Key sendiri di website
- Pilih model yang stabil (default: `gemini-2.5-flash`)
- Jika muncul 503, ganti model lewat tombol "Ganti API Key / Model"
