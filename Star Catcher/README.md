# Star Catcher: Meteor Rush

Game arcade 2D berbasis HTML5 Canvas dan JavaScript. Pemain menggerakkan pesawat untuk menangkap bintang, menghindari meteor, dan memperoleh skor tertinggi dalam 60 detik.

## Cara menjalankan
1. Ekstrak ZIP.
2. Buka `index.html` di browser, atau jalankan server lokal dengan `python -m http.server 8000`.
3. Buka `http://localhost:8000`.

## Kontrol
- Keyboard: panah kiri/kanan atau A/D.
- Layar sentuh: tombol kiri dan kanan di bawah arena.
- Klik Mulai Permainan untuk memulai atau mengulang.

## Aturan
- Bintang biasa: +1 poin.
- Golden Star: +5 poin.
- Meteor: mengurangi 1 nyawa.
- Shield: perlindungan sementara selama 6 detik.
- Durasi 60 detik, tiga nyawa.

## Modifikasi dari konsep Star Catcher dasar
1. Golden Star ditambahkan sebagai objek bonus bernilai 5 poin.
2. Shield Power-up ditambahkan untuk memberi perlindungan sementara dari meteor.
3. Tampilan diperbarui dengan tema luar angkasa neon, HUD, panel instruksi, dan indikator best score.
4. Kontrol layar sentuh disediakan untuk perangkat mobile.

## Struktur proyek
- `index.html` — halaman utama.
- `style.css` — tampilan dan layout responsif.
- `game.js` — logika permainan, skor, timer, objek, dan kontrol.
- `assets/` — folder untuk aset tambahan.

## Teknologi
HTML5, CSS3, JavaScript, Canvas 2D API.

## Kredit
Dikembangkan sebagai modifikasi latihan publikasi web game dari materi Pertemuan 7. Lengkapi nama pengembang dan kredit aset sesuai kontribusi aktual sebelum publikasi.
