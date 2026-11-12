# Dota Type Test — Direbattle

Quiz MBTI versi Dota 2: 8 soal, 16 tipe, kartu hasil 1080×1920 siap share ke IG Story.

Satu file statis (`index.html`), tanpa build. Deploy di Vercel dengan framework preset "Other".

## Gambar hero

Portrait hero diambil lewat `/hero/<slug>.png`, yang di-proxy Vercel (lihat `vercel.json`) ke CDN resmi Dota 2, jadi gambarnya same-origin dan bisa digambar ke kartu PNG. Kalau gambar gagal dimuat (misalnya dibuka lokal tanpa Vercel), kartu otomatis pakai tile teks.
