#CLI Sederhana
Sebuah aplikasi command-line (CLI) sederhana untuk mengelola daftar tugas harian. Dibuat murni dengan modul bawaan Node.js, tanpa dependensi eksternal.
Data akan disimpan secara lokal dalam file tasks.json.

##Fitur
- Tambah Tugas: Menambahkan tugas baru ke daftar.
- Lihat Daftar Tugas: Menampilkan semua tugas dengan status (selesai/belum).
- Tandai Selesai: Mengubah status tugas menjadi selesai berdasarkan ID.
- Hapus Tugas: Menghapus tugas dari daftar berdasarkan ID.
- ID Berurutan: Menggunakan ID numerik sederhana yang berurutan (1, 2, 3, ...).

##Teknologi
Dibuat tanpa framework dan tanpa dependensi eksternal. 
- Node.js
- fs/promises: Untuk membaca/menulis file tasks.json secara asinkron.
- process.argv: Untuk mem-parsing perintah dan argumen langsung dari terminal.
