<h1 align="center">📦 HsTermx</h1>
<p align="center"><i>Script ringan untuk mengubah tampilan Termux secara otomatis dan stylish.</i></p>

---

## 📌 Description of HsTermx

**HsTermx** adalah script otomatis untuk mempercantik tampilan Termux secara ringan, cepat, dan profesional.  
Script ini mengatur shell Zsh, menambahkan tema, font, warna, serta fetch info terminal agar tampil menarik dan tetap ringan.

Ideal untuk pengguna yang ingin tampil beda tanpa membebani performa.

---

## ✨ Features of HsTermx

- 🎨 Mengganti tampilan Termux secara otomatis
- 🖥️ Menampilkan info sistem dengan \`rxfetch\`
- 🔤 Menggunakan font modern: **Fira Code Bold Nerd Font**
- 🌈 Mengaktifkan tema warna custom: **nekonako-djancoeg.colors**
- 🧠 Konfigurasi ZSH dengan tema manual \`osx2.zsh-theme\`
- 🚀 Ringan, tidak menggunakan plugin ZSH tambahan

---

## 📁 Directory Structure

HsTermx/
├── install.sh     # Script utama instalasi otomatis
├── theme/osx2.zsh-theme     # Tema untuk ZSH
├── colors/nekonako-djancoeg.colors     # Tema warna untuk Termux
├── fonts/FiraCode-Bold-Nerd-Font.ttf # Font yang digunakan
└── rxfetch/rxfetch                   # Info sistem terminal (fetch tools)

---

## ⚙️ Installation Guide

pkg update && pkg upgrade
pkg install git -y
git clone https://github.com/username/HsTermx.git
cd HsTermx
bash install.sh

---

## 🧠 Credits & Notes

- Script ini dibuat oleh **HamzSenpaii** sebagai alternatif dari MyTermux dengan fokus pada performa ringan.
- Inspirasi tampilan berasal dari tema macOS dan setup fetch yang minimal.
- Tools & sumber yang digunakan:
  - [rxfetch](https://github.com/phosguy/rxfetch) – untuk menampilkan info sistem
  - [Nerd Fonts](https://www.nerdfonts.com/) – font terminal modern
  - Tema \`osx2.zsh-theme\` dan \`nekonako-djancoeg.colors\` dimodifikasi khusus untuk HsTermx

---

<p align="center"><b>🖤 Terima kasih telah menggunakan HsTermx</b></p>
