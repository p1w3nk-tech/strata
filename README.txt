README - Panduan Login Aplikasi Data Produk (Firebase)

==========================================
🔹 Cara Login
==========================================
1. Aplikasi ini menggunakan Firebase Authentication dengan metode Email/Password.
2. Untuk login, buka file index.html di browser.
3. Masukkan email dan password sesuai yang sudah dibuat di Firebase Console.

==========================================
🔹 Akun Admin (akses penuh)
==========================================
- Email: mnu@smg.com
- Password: (dibuat di Firebase Console, contoh: Semarang123)
- Role: admin
- Hak akses: Tambah, Edit, Hapus data, Export, Import, Print

==========================================
🔹 Akun User (hanya baca)
==========================================
- Email: (tambahkan akun baru di Firebase Console, misalnya viewer@smg.com)
- Password: (ditentukan saat buat akun)
- Role: user
- Hak akses: hanya bisa melihat data (tidak bisa tambah/edit/hapus)

==========================================
🔹 Cara Menambah/Mengelola User di Firebase
==========================================
1. Masuk ke Firebase Console: https://console.firebase.google.com/
2. Pilih project: strata-dc0dc
3. Buka menu Authentication → Users → Add user
4. Masukkan email & password untuk akun baru
5. Klik Add user

Catatan:
- Akun dengan email mnu@smg.com otomatis menjadi admin.
- Semua akun lain dianggap user biasa.
