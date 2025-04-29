🧩 Prompt Lengkap Pembuatan Website Jigsaw Puzzle Anak-anak

Saya ingin kamu membuat sebuah proyek web game edukatif untuk anak-anak berupa jigsaw puzzle. Berikut adalah spesifikasinya:

🎯 Tujuan Utama:
Membuat game jigsaw puzzle interaktif berbasis web yang:

Cocok untuk anak-anak usia dini (usia 4–8 tahun)

Fun, colorful, dan mudah dimainkan

Tanpa perlu cropping gambar manual

Dapat diganti tingkat kesulitannya (2x2 dan 3x3 grid)

🌈 Desain dan UX:
Gunakan warna-warna cerah dan gaya visual ramah anak-anak.

Gunakan font besar dan ramah (contoh: Comic Sans, atau font serupa).

Berikan pesan kemenangan (“Yeay! Puzzle selesai 🎉”) jika berhasil menyusun gambar.

Gunakan drag-and-drop untuk menyusun potongan puzzle.

Tambahkan dropdown untuk memilih tingkat kesulitan (2x2 atau 3x3).

Tambahkan tombol “🔀 Acak Ulang”.

🔧 Fitur Utama:
Tampilkan satu gambar puzzle yang dipotong menjadi grid 2x2 atau 3x3 secara otomatis menggunakan CSS background-position, bukan cropping manual.

Puzzle diacak secara random saat dimulai atau tombol acak ditekan.

Validasi posisi puzzle secara otomatis setelah drop.

Jika semua potongan di posisi yang benar, tampilkan alert atau animasi berhasil.

Gambar puzzle hanya satu file (misalnya puzzle.jpg), disimpan di folder /public/images/.

🧱 Struktur Proyek:
java
Salin
Edit
/kids-jigsaw-puzzle-game/
│
├── index.html          → halaman utama
├── style.css           → styling menyenangkan untuk anak-anak
├── script.js           → logika game
└── public/
    └── images/
        └── puzzle.jpg  → gambar puzzle utuh (disarankan 300x300 px)
💡 Bonus (Opsional):
Jika ada waktu, tambahkan fitur berikut:

Animasi potongan saat drag/drop.

Sound effect sederhana saat potongan berhasil ditempatkan.

Responsif untuk tablet/HP.

Tombol untuk mengganti gambar puzzle.

🛠 Teknologi:
Gunakan HTML, CSS, dan JavaScript murni (tanpa framework).

Tidak perlu server-side code atau database.

Tidak perlu framework build seperti React/Vite, cukup proyek static sederhana.

Jika kamu memahami semuanya, buatkan struktur dan kode lengkap untuk proyek ini. Buat seprofesional mungkin, tetapi tetap ringan dan menyenangkan untuk dimainkan anak-anak.