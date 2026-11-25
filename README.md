# NV Analytics

Platform digital untuk pencatatan dan analisis statistik pertandingan bola voli.

## Menjalankan secara lokal

1. Instal Node.js versi LTS.
2. Buka terminal pada folder proyek.
3. Jalankan `npm install`.
4. Jalankan `npm run dev`.

## Build untuk publikasi

Jalankan `npm run build`. Hasil build tersedia di folder `dist/`.

## Deploy melalui GitHub dan Netlify

- Push seluruh isi folder ini ke repository GitHub.
- Hubungkan repository tersebut ke Netlify.
- Build command: `npm run build`
- Publish directory: `dist`

Konfigurasi tersebut juga tersedia pada `netlify.toml`.

## Catatan penyimpanan data

Versi aplikasi saat ini menggunakan penyimpanan browser (`localStorage`/`sessionStorage`) untuk data lokal. Publikasi ke Netlify membuat website dapat dibuka melalui internet, tetapi tidak otomatis menyinkronkan data antarperangkat atau antar pengguna. Sinkronisasi bersama memerlukan backend/database online.
