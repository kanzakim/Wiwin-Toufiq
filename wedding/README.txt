THE WEDDING OF WIWIN & TOUFIQ
================================

ISI FOLDER
- index.html                  Halaman undangan (HTML, CSS, JavaScript)
- assets/foto-pasangan.jpg    Foto pasangan yang diberikan
- assets/musik-klasik.mp3    Musik instrumental orisinal yang dibuat untuk undangan
  (Jika perangkat Anda tidak mendukung MP3, lihat ekstensi file yang tersedia di folder assets.)

CARA MEMBUKA
1. Ekstrak file ZIP.
2. Buka folder hasil ekstrak.
3. Klik dua kali index.html untuk melihat website di browser.
4. Koneksi internet diperlukan untuk memuat font Google Fonts; konten utama tetap tampil jika offline.

CARA MENGGANTI FOTO
1. Siapkan foto pasangan baru.
2. Namai foto tersebut foto-pasangan.jpg.
3. Ganti file assets/foto-pasangan.jpg dengan foto baru (nama/path harus sama).

CARA MENGGANTI MUSIK
1. Siapkan file musik milik sendiri atau musik yang memiliki izin penggunaan.
2. Namai file tersebut musik-klasik.mp3.
3. Ganti assets/musik-klasik.mp3. Tombol ♫ di kanan bawah berfungsi untuk play/pause.
4. Browser biasanya mensyaratkan pengguna menekan tombol musik terlebih dahulu sebelum audio diputar.

CARA MENGGANTI NOMOR WHATSAPP
1. Buka index.html menggunakan VS Code atau editor teks.
2. Cari baris: const WHATSAPP_NUMBER = "6282194953329";
3. Ganti angka di dalam tanda kutip dengan nomor baru format internasional tanpa tanda +.
4. Simpan file. Tautan RSVP otomatis memakai nomor yang baru.

CARA MENGUBAH DATA
- Nama, tanggal, alamat, jam acara, dan teks undangan dapat diedit langsung di index.html.
- Tanggal countdown diatur pada const targetDate = new Date("2026-12-06T08:00:00+07:00").

PUBLIKASI KE GITHUB PAGES
1. Login ke GitHub dan buat repository baru (misalnya: undangan-wiwin-toufiq).
2. Upload index.html dan seluruh folder assets beserta isinya ke root repository.
3. Buka Settings > Pages.
4. Pada Build and deployment, pilih Deploy from a branch.
5. Pilih branch main dan folder /(root), lalu Save.
6. Tunggu proses publikasi selesai. Buka alamat GitHub Pages yang ditampilkan di halaman Settings > Pages.

CATATAN
- Foto yang sama digunakan pada cover dan profil, sesuai permintaan; tidak ada galeri atau foto tambahan.
- Musik yang disertakan adalah komposisi instrumental orisinal sederhana, bukan rekaman lagu komersial.
- Tombol Google Maps membuka tautan yang diberikan.
- Tombol RSVP membuka WhatsApp dengan pesan konfirmasi yang sudah diisi.
- Pastikan detail acara dan nomor WhatsApp diperiksa kembali sebelum tautan dibagikan.
