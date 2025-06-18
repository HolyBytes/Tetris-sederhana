# 🎮 Tetris 2.0 Beta - Modern Tetris Experience

**Game Tetris modern dengan berbagai mode, efek visual keren, dan kontrol responsif**  
🔥 *Dikembangkan oleh Ade Pratama* 🔥

[![Play Now](https://img.shields.io/badge/PLAY-NOW-brightgreen?style=for-the-badge)](https://holybytes.github.io/Tetris-sederhana/)
![Version](https://img.shields.io/badge/Version-2.0_Beta-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-red?style=flat-square)

## 🌟 Fitur Utama

### 🎮 **6 Mode Game Berbeda**
- **Classic Mode**: Tetris standar dengan fitur hold & preview
- **Time Attack**: Kumpulkan poin maksimal dalam 2 menit!
- **Survival Mode**: Kecepatan tinggi tanpa ampun
- **Zen Mode**: Bermain santai tanpa game over
- **Puzzle Mode**: Teka-teki seru dengan langkah terbatas
- **Versus Mode**: Tantang AI dalam duel epik

### 💥 **Efek Visual Keren**
- Background particle system Three.js
- Animasi smooth untuk pergerakan block
- Efek partikel saat clear line
- Tema gradient ungu-biru futuristik

### 🎵 **Sound Effect Responsif**
- Setiap aksi punya sound effect unik
- Volume adjustable di settings
- Feedback audio yang memuaskan

### 📱 **Mobile Friendly**
- Kontrol touch khusus untuk mobile
- UI responsif semua ukuran layar
- Optimasi performa untuk perangkat rendah

## 🕹️ Cara Main

### Kontrol Dasar:
- **← →**: Gerak kiri/kanan
- **↓**: Turun cepat (+1 poin)
- **↑**: Putar block
- **Spasi**: Hard drop instan (+2 poin per baris)
- **C**: Hold piece (simpan block)
- **P**: Pause game

### Strategi Pro:
1. **Prioritaskan Tetris** (clear 4 baris sekaligus) untuk poin maksimal
2. **Manfaatkan fitur Hold** untuk block strategis
3. **Perhatikan Next Piece** untuk perencanaan
4. **Jangan over-stack** di satu sisi
5. **Fast drop** untuk poin bonus

## 🛠️ Teknologi

- **Frontend**: HTML5, CSS3, JavaScript ES6
- **Framework**: Bootstrap 5 + Tailwind CSS
- **3D Effect**: Three.js (r128)
- **Icons**: Font Awesome 6
- **Animation**: CSS3 + requestAnimationFrame

## 📊 Sistem Skoring

| Aksi                | Poin               | Multiplier Level |
|---------------------|--------------------|------------------|
| Single Line Clear   | 40 poin            | × (level + 1)    |
| Double Line Clear   | 100 poin           | × (level + 1)    |
| Triple Line Clear   | 300 poin           | × (level + 1)    |
| Tetris (4 lines)    | 1200 poin          | × (level + 1)    |
| Soft Drop (per baris)| 1 poin             | -                |
| Hard Drop (per baris)| 2 poin             | -                |

**Level up** setiap 10 baris yang di-clear!

## 🚀 Cara Mulai

1. **Main Online**:  
   Langsung buka [https://holybytes.github.io/Tetris-sederhana/](https://holybytes.github.io/Tetris-sederhana/)

2. **Local Development**:
   ```bash
   git clone https://github.com/HolyBytes/Tetris-sederhana.git
   cd Tetris-sederhana
   # Buka index.html di browser
   ```

## 📜 Changelog

### v2.0 Beta
- [x] Tambah 6 mode game berbeda
- [x] Sistem highscore lokal
- [x] Efek partikel Three.js
- [x] Kontrol mobile touch
- [x] Optimasi performa

## 🤝 Kontribusi

Laporkan bug atau request fitur via:
- [Issues GitHub](https://github.com/HolyBytes/Tetris-sederhana/issues)
- Email: sppquicksmk@gmail.com

## 📄 Lisensi

MIT License - Bebas dimodifikasi dan didistribusikan  
© 2024 Ade Pratama - [HolyBytes](https://github.com/HolyBytes)
