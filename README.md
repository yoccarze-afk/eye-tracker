# 👁️ Eye Tracker - Termux Edition

Deteksi mata real-time lewat browser HP kamu!

## Fitur
- ✅ Deteksi kedip mata
- ✅ Arah pandangan (kiri/kanan/atas/bawah)
- ✅ Visualisasi posisi pupil
- ✅ Status mata buka/tutup

## Cara Install

### 1. Install di Termux
```bash
pkg update && pkg upgrade -y
pkg install nodejs git -y
git clone https://github.com/YOUR_USERNAME/eye-tracking.git
cd eye-tracking
npm install
node server.js
```

### 2. Buka di Browser
```
http://localhost:3000
```

### 3. Izinkan akses kamera → Klik MULAI KAMERA

## Catatan
- Butuh koneksi internet saat pertama buka (download model AI ~2MB)
- Gunakan pencahayaan yang cukup
- Pastikan wajah terlihat jelas di kamera
