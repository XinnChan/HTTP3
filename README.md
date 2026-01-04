<div align="center">

# DDOS ATTACK HTTP/3 “MadeYouReset” – Force the target server to reset until it crashes and boom it explodes
### 🌊 RST STREAM HTTP3 CVE MADE YOU RESET 🌊

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/Platform-VPS%20|%20Termux-red?style=for-the-badge&logo=linux)
![Root](https://img.shields.io/badge/Root-Required-black?style=for-the-badge)

<p align="center">
  <strong>Advanced HTTP/3 Testing Tool</strong><br>
  Script ringan tanpa dependensi eksternal. Langsung jalan, tanpa ribet.
</p>

---
</div>

## ⚠️ Requirements & Compatibility

Script ini dirancang khusus untuk lingkungan berikut:
* **Environment:** VPS (Linux) & Termux (Android).
* **Access:** Wajib menggunakan access **Sudo** atau **Root**.
* **Dependencies:** Tidak ada instalasi modul selain (`pip install requests`) yang diperlukan.

## 🚀 Installation & Usage

Ikuti urutan langkah di bawah ini dengan tepat agar script berjalan dengan normal.

### 1. Jalankan Monitor (Wajib)
Script utama bergantung pada `monitor.py`. Jika monitor tidak berjalan, script utama tidak akan berfungsi.


`cd && cd HTTP3 && screen -dmS monitor python3 monitor.py`

Note: Pastikan screen session monitor sudah aktif sebelum lanjut ke langkah berikutnya.
### 2. Jalankan Script Utama
Setelah monitor aktif, jalankan script utama. Tidak perlu melakukan chmod (izin eksekusi), script dapat langsung dipanggil.

`./3`

Setelah perintah di atas diketik, menu opsi dan cara penggunaan detail akan muncul secara otomatis di layar Anda.
<div align="center">
🛡️ Disclaimer
Script ini dibuat untuk tujuan edukasi dan pengujian keamanan jaringan sendiri. Pengembang tidak bertanggung jawab atas penyalahgunaan alat ini.

### 3. Penjelasan script xu & us
Jangan hapus script xu dan us ini karena sebagai requirement module ./3
</div>
