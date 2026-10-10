# How Well Do You Know Ata? 🎀

## File
- `index.html`: website kuis 20 soal.

## Penting tentang leaderboard
Supaya semua pemain melihat TOP 10 yang sama dari HP masing-masing, perlu backend online. HTML ini sudah disiapkan untuk Supabase, tetapi leaderboard global belum aktif sampai kamu mengisi `SUPABASE_URL` dan `SUPABASE_ANON_KEY` di dekat bagian atas JavaScript. Jangan pernah memasukkan service_role key ke HTML publik.

### Setup Supabase
1. Buat project di Supabase.
2. Buka SQL Editor, jalankan SQL pada `supabase_setup.sql`.
3. Di Project Settings → API, salin Project URL dan anon/public key.
4. Di `index.html`, isi `SUPABASE_URL` dan `SUPABASE_ANON_KEY`.
5. Upload `index.html` ke GitHub Pages. Semua orang yang membuka URL yang sama akan memakai leaderboard online yang sama.

Skor lokal lama tidak otomatis berpindah ke leaderboard online.
