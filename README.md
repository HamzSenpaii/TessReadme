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

Script **HsTermx** dibuat oleh **HamzSenpaii**,
sebagai _rebuild ringan_ dari script original [MyTermux](https://github.com).  
Ini **bukan hasil fork langsung**, melainkan hasil **pembuatan ulang dan modifikasi** dengan fokus utama pada kesederhanaan, efisiensi, dan pengurangan beban sistem.

### 💡 Inspirasi
- script **HsTermx** alternatif dari **MyTermux** dengan fokus pada performa yang ringan.
- Dikembangkan ulang agar lebih minimal, ringan, dan mudah diinstal.

## 🙌 Thanks To

- **[HamzSenpaii](https://gitbuh.com/HamzSenpaii)** – Pembuat script **HsTermx**, yang merebuild Script MyTermux agar lebih ringan dan minimalis.
- **adi1090x** – Pembuat script [MyTermux](https://github.com/adi1090x/MyTermux) yang menjadi inspirasi utama.
- **rxfetch** – Minimalist system fetch script yang digunakan untuk menampilkan informasi sistem.
- Kontributor tema dan font:
  - `osx2.zsh-theme` – Tema ZSH bergaya macOS.
  - `FiraCode Nerd Font` – Font terminal dengan ikon lengkap.
  - `nekonako-djancoeg.colors` – Tema warna custom untuk kenyamanan visual.
- ❤️ Komunitas Termux & open-source – Untuk segala ilmu, alat, dan semangat kolaborasi.

> Terima kasih untuk semua pihak yang telah membantu, baik secara langsung maupun sebagai inspirasi.

---

<p align="center"><b>🖤 Terima kasih telah menggunakan HsTermx</b></p>
