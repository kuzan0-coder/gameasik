# Grand Casino Royale

Game kasino & arcade 3D yang dibuat dengan **Unity 6 (URP)** dan bisa langsung dimainkan di browser.

## ▶️ Main sekarang

**https://USERNAME.github.io/REPO/**

> Ganti `USERNAME` dan `REPO` sesuai akun & nama repository-mu setelah GitHub Pages aktif.

Tak perlu install apa pun — cukup buka link di browser. Bisa dimainkan di PC maupun HP.

## 🎮 Kontrol

### Komputer
| Tombol | Fungsi |
|---|---|
| `W A S D` / panah | Jalan |
| `Shift` (+ arah) | Lari |
| `Spasi` | Lompat — tekan 2× di udara untuk salto |
| Gerak mouse | Kamera |
| `E` | Berinteraksi (mesin arcade, kursi, pintu) |
| `M` | Peta mini |
| `Tab` | Menu pengaturan |

### HP / tablet
Kontrol sentuh muncul otomatis: joystick di kiri, geser layar kanan untuk kamera, plus tombol **AKSI**, **LOMPAT**, **PETA**, dan **MENU**.

## ✨ Isi game

- **Lobi 2 lantai** bergaya arcade dengan tangga dan mezzanine
- **Pilih karakter** — beberapa karakter dengan layar putar 3D
- **Ganti baju** — sistem wardrobe (atasan, celana, sepatu, rambut)
- **Mini-game**: slot bertema, video poker, pachinko, VLT, blackjack, roulette, bakarat, dadu, sic bo, pai gow, dan biliar
- **Kabinet arcade** yang bisa dimainkan langsung di dalam dunia game
- Musik latar dan efek suara yang dibangkitkan secara prosedural (tanpa file audio)

## 🛠️ Dibangun dengan

- Unity `6000.3.16f1` — Universal Render Pipeline
- Target: **WebGL** (browser) dan **Android**
- Kompresi Brotli, ukuran unduhan sekitar **52 MB**

## 📁 Tentang repository ini

Repository ini berisi **hasil build untuk browser saja**, bukan kode sumbernya.
Kode sumber project dikelola terpisah menggunakan Unity Version Control.

Berkas `.nojekyll` diperlukan agar GitHub Pages menyajikan seluruh berkas build apa adanya.

## ⚙️ Cara mengaktifkan GitHub Pages

1. Push seluruh isi folder ini ke repository (pastikan `index.html` berada di **akar** repo)
2. Buka **Settings → Pages**
3. **Source**: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)`
4. **Save**, lalu tunggu 1–3 menit

## 📝 Catatan

- Pemuatan pertama memerlukan beberapa detik karena berkas didekompresi di sisi browser (GitHub Pages tidak mengirim header Brotli). Kunjungan berikutnya lebih cepat berkat cache.
- Musik baru berbunyi setelah ada klik pertama — ini aturan browser, bukan kerusakan.
- Jika kursor terlepas saat bermain, klik layar untuk mengunci kembali.
