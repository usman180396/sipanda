# SIPANDA — Sistem Persuratan dan Arsip Digital

Versi GitHub Pages / Static Web App untuk MAN Kota Sorong.

## Fitur
- Dashboard
- Surat masuk
- Surat keluar
- Disposisi
- Arsip digital
- Pencarian
- Upload dokumen sampai 10 MB
- Backup dan restore JSON
- Responsive HP/desktop
- Tidak membutuhkan PHP, MySQL, atau hosting

## Cara upload ke GitHub
1. Buat repository baru, misalnya `sipanda-man-sorong`.
2. Upload `index.html`, `style.css`, dan `app.js`.
3. Buka **Settings → Pages**.
4. Pada Source pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/root`.
6. Simpan.
7. GitHub akan memberikan alamat `https://USERNAME.github.io/sipanda-man-sorong/`.

## Penting
Versi GitHub Pages ini menyimpan data di browser menggunakan localStorage. Jadi data tidak otomatis menjadi satu database bersama antar komputer. Gunakan menu Backup & Pemulihan untuk ekspor/impor data.

Untuk sistem yang digunakan bersama oleh seluruh TU/Kepala Madrasah dari banyak perangkat, diperlukan backend/database (misalnya Supabase/Firebase atau server PHP/MySQL).
