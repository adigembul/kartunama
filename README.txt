DIGITAL CARD — SETYOHADI WIRATMOKO | RUMAH EDUKASI DIGITAL

1. Upload seluruh file (index.html, config.json, icon.svg, manifest.webmanifest, sw.js) ke folder web HTTPS.
2. Buka web, klik tombol ⚙ lalu buat PIN 6–12 digit untuk pengaturan browser tersebut.
3. Ubah profil, unggah foto, atur tautan, portofolio, media sosial, fitur aktif/nonaktif, dan tema default.
4. Klik Simpan Semua Perubahan. Penyimpanan ini LOKAL di browser yang digunakan untuk mengedit.
5. Di tab Publikasi & NFC klik Unduh config.json, lalu TIMPA config.json di hosting agar pengunjung lain melihat perubahan. Proses ini tidak mengunggah PIN.
6. Untuk menulis NFC, isi URL HTTPS publik yang permanen, lalu tekan Tulis NFC melalui Chrome Android yang mendukung Web NFC dan tempelkan kartu/stiker NDEF pada HP. NFC device-ke-device tanpa tag tidak dapat menjamin website terbuka otomatis.
7. Konten default foto/proyek dapat disiapkan dengan data gambar terkompresi di config.json. Jika besar, upload bisa lebih lambat; untuk portofolio skala besar gunakan file gambar eksternal/CDN dan backend.
8. Jika editor sebelumnya pernah menyimpan pengaturan lokal, data lokal pada browser editor akan mengungguli config.json hosting. Pengunjung baru membaca config.json publik.

PERHATIAN KEAMANAN: PIN browser hanya mencegah pengaturan dibuka secara tidak sengaja pada browser yang sama. Ini bukan login server yang aman; website statis dapat disalin/diubah. Untuk admin privat, autentikasi multi-device, serta edit publik langsung, perlu backend dan database dengan kontrol akses. Jangan simpan rahasia/API key/PIN dalam config.json.

(c) Digital Card. Rumah Edukasi Digital
