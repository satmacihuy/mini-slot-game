<!-- ========================= -->
<!--        PROJECT LOGO       -->
<!-- ========================= -->

<p align="center">
  <img src="promo1.png" alt="Mini Slot Game Banner" width="400">
</p>

<h1 align="center">🎰 Mini Slot Game</h1>

<p align="center">
  Game slot sederhana berbasis web.  
  Tanpa backend. Tanpa database. Tanpa password.  
  Cukup browser dan sedikit keberuntungan.
</p>

<p align="center">
  <a href="https://github.com/satmacihuy/mini-slot-game/stargazers">
    <img src="https://img.shields.io/github/stars/satmacihuy/mini-slot-game?style=flat-square" />
  </a>
  <a href="https://github.com/satmacihuy/mini-slot-game/forks">
    <img src="https://img.shields.io/github/forks/satmacihuy/mini-slot-game?style=flat-square" />
  </a>
  <a href="https://github.com/satmacihuy/mini-slot-game/issues">
    <img src="https://img.shields.io/github/issues/satmacihuy/mini-slot-game?style=flat-square" />
  </a>
  <img src="https://img.shields.io/github/license/satmacihuy/mini-slot-game?style=flat-square" />
</p>

---

## 📌 Tentang Project

**Mini Slot Game** adalah game slot HTML + CSS + JavaScript yang berjalan **100% di sisi client**.

- Tidak pakai backend
- Tidak pakai database
- Tidak pakai password
- Semua data disimpan di **localStorage browser**

Setiap username punya saldo sendiri, dan semuanya tersimpan otomatis.

Project ini cocok buat:
- Latihan JavaScript
- Contoh multi-user tanpa backend
- Game iseng tapi rapi
- Base project sebelum naik ke backend beneran

---

## ✨ Fitur Utama

- 🧑‍💻 Login & Sign Up **hanya pakai username**
- 💾 Data user & saldo tersimpan di localStorage
- 💰 Sistem deposit
- 🎰 Slot machine 3 reel
- 📈 Perhitungan menang:
  - Pair → **1.5× deposit**
  - Jackpot (3 simbol sama) → **10× deposit**
  - Zonk → ya zonk
- 🎵 Sound effect (spin & jackpot)
- 🎶 Background music
- 🖼️ Promo banner (link ke GitHub)
- 📱 Responsive (aman dibuka di HP & desktop)

---

## 🧭 Alur Game

```text
Welcome Screen
      ↓
Login / Sign Up (username only)
      ↓
Loading Screen
      ↓
Game Screen
      ↓
Deposit → Spin → Result
