<h1 align="center">📦 HsTermx</h1>
<p align="center"><i>Script ringan untuk mengubah tampilan Termux secara otomatis dan stylish.</i></p>

---

## 📌 Description of HsTermx

**HsTermx** adalah script otomatis untuk mempercantik tampilan Termux secara ringan, cepat, dan profesional.  
Script ini mengatur shell Zsh, menambahkan tema, font, warna, serta fetch info terminal agar tampil menarik dan tetap ringan.

Ideal untuk pengguna yang ingin tampil beda tanpa membebani performa.

---

## ✨ Features of HsTermx

- Mengganti tampilan Termux secara otomatis
- Menampilkan info sistem dengan `rxfetch`
- Menggunakan font modern: **Fira Code Bold Nerd Font**
- Mengaktifkan tema warna custom: **nekonako-djancoeg**
- Konfigurasi ZSH dengan tema manual `osx2.zsh-theme`
- Ringan, tidak menggunakan plugin ZSH tambahan

---

## 📁 Directory Structure

```text
HsTermx/
├── install.sh                        # Script utama instalasi otomatis
├── theme/osx2.zsh-theme              # Tema untuk ZSH
├── colors/nekonako-djancoeg.colors   # Tema warna untuk Termux
├── fonts/firacode-bold-nerd-font.ttf # Font yang digunakan
└── rxfetch/rxfetch                   # Info sistem terminal (fetch tools)
```

---

## ⚙️ Installation Guide

  <details open>
  <summary><strong>Installation HsTermx</strong></summary>
    <br>
    <br>
- Update Repository & Upgrade Package
    
```bash
pkg update && pkg upgrade -y
```

- Instalation Git For Cloning Repository

```bash
pkg install git -y
```

- Clone Or Download Repository

```bash
git clone https://github.com/HamzSenpaii/HsTermx.git
```

- Move Folder

```bash
cd HsTermx
```

- Give Permission

```bash
chmod +x install.sh
```

- Execute Installer

```bash
./install.sh
```
  </details>

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
