# 🚨 Panic Button Dashboard

Dashboard Web & Mobile App untuk memantau tombol darurat secara real-time melalui **Firebase Realtime Database**. Dibangun dengan ❤️ untuk respons cepat terhadap kondisi kritis.

---

## 🖥️ Web Dashboard

> Tampilan responsif berbasis HTML, CSS, dan Firebase Realtime Database

### 🎯 Fitur Unggulan
- 💡 **Live Monitoring** status tombol darurat secara real-time
- 📊 **Rekap Data** laporan dengan visual yang rapi dan mudah dipahami
- 🔔 **Notifikasi Prioritas**: Darurat / Penting / Biasa
- 🌍 **Integrasi Google Maps** untuk menampilkan lokasi darurat
- ☁️ **Realtime Sync** dengan Firebase

### 🧩 Teknologi
| Teknologi              | Keterangan                   |
|-----------------------|------------------------------|
| HTML5 / CSS3          | Tampilan frontend            |
| Firebase Realtime DB  | Penyimpanan data realtime    |
| JavaScript (ES6+)     | Logika interaktif & fetch data|
| W3.CSS                | Layout responsif             |
| Google Maps           | Lokasi laporan darurat       |

---

## 📱 Mobile App (Android)

> Aplikasi Android dibuat dengan Kotlin untuk mengirim sinyal Panic Button ke Firebase.

### 📲 Fitur Mobile
- 🆘 Tombol "PANIC" yang mengirim prioritas dan lokasi
- 📡 Kirim data langsung ke Firebase Realtime Database
- 🛰️ Akses GPS untuk mendapatkan koordinat lokasi real-time
- 🔐 Permission handler otomatis (lokasi dan internet)

### 🛠 Teknologi Mobile
| Teknologi              | Keterangan                   |
|-----------------------|------------------------------|
| Kotlin                | Bahasa utama aplikasi Android|
| Firebase Realtime DB  | Backend realtime             |
| FusedLocationProvider | Lokasi akurat di Android     |
| Material Design 3     | Tampilan modern dan ringan   |

---

## 🧪 Cara Menjalankan

### Web
1. Buka file HTML di browser:
   - `index.html` (Dashboard utama)
   - `rekap.html` (Rekap laporan)
   - `user.html` (Data user terdaftar)
2. Lengkapi konfigurasi Firebase di `index.html`:
    const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    // isi dengan konfigurasi Firebase kamu
    };

### Android
1. Buka folder `android-app` di Android Studio.
2. Buat project Firebase dan hubungkan ke aplikasi.
3. Tambahkan file `google-services.json` ke folder `app/`.
4. Jalankan di emulator atau perangkat nyata.

---

## 📁 Struktur Proyek
panic-button-dashboard/
├── index.html # Dashboard utama
├── rekap.html # Rekap laporan
├── user.html # Data user terdaftar
├── house.png # Logo aplikasi
├── .gitignore
└── README.md # Dokumentasi ini

android-app/
└── app/ # Source code Kotlin
└── build.gradle

---

## 🛡️ Keamanan
- Jangan menyertakan kredensial Firebase asli di repositori publik.
- Tambahkan `.env`, `firebase-config.js`, dan `google-services.json` ke `.gitignore` agar tidak ter-commit.

---

## 🤝 Kontribusi
Pull request sangat diterima! Beberapa ide pengembangan:
- Menambahkan fitur geofence
- Integrasi notifikasi push
- Mode tampilan gelap (dark mode) 🌙

---

## 📬 Kontak
Author: [@yourusername](https://github.com/yourusername)  
Email: youremail@example.com  

<p align="center">Made with ❤️ by TIM WIKO LIFEMEDIA YOGYAKARTA</p>