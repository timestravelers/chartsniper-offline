# ChartSniper Pro v3 – Offline AI Edition

📈 Aplikasi deteksi pola chart otomatis menggunakan kamera HP tanpa internet.  
Dibangun dengan teknologi AI nyata: TensorFlow.js + OpenCV.js + JavaScript murni.

---

## 🔍 Fitur Utama

- **📷 Deteksi Pola Chart via Kamera**
  - Head and Shoulders, Double Top, Triangle, dll.
- **🧠 AI Nyata**
  - Model CNN berbasis TensorFlow.js
- **🖼️ Computer Vision**
  - Preprocessing gambar dengan OpenCV.js
- **📱 Mobile-Friendly UI**
  - Desain responsif untuk ponsel
- **💾 Offline First**
  - Tidak perlu internet

---

## 🧩 Teknologi

| Tech | Fungsi |
|------|--------|
| **TensorFlow.js** | Model AI untuk deteksi pola |
| **OpenCV.js**     | Preprocessing gambar |
| **JavaScript**    | Logika analisis |
| **HTML/CSS**     | UI mobile-friendly |

---

## 🚀 Cara Pakai

1. Buka `index.html` di browser
2. Izinkan akses kamera
3. Arahkan ke chart
4. Klik tombol “Ambil Gambar” → analisis otomatis

---

## 📁 Struktur File
ChartSniper_Pro_Offline/
├── index.html              ← Aplikasi utama
├── model/
│   ├── pattern-model.json  ← Arsitektur model AI
│   └── weights.bin         ← Bobot model AI (dummy untuk testing)
├── js/
│   └── ai-model.js         ← Logika AI & deteksi pola
├── assets/
│   └── ding.mp3            ← Notifikasi suara
└── README.md               ← Deskripsi aplikasi
