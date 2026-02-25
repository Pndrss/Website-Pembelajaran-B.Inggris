
# Elang - English Learning Platform

## 📚 Deskripsi Proyek

Elang adalah aplikasi pembelajaran bahasa Inggris interaktif yang dirancang untuk membantu pengguna menguasai materi pelajaran bahasa Inggris melalui sistem semester. Platform ini menyediakan materi pembelajaran, kuis, dan melacak kemajuan belajar pengguna.

### Fitur Utama
- 📖 Materi pembelajaran terbagi dalam 2 semester
- ❓ Sistem kuis untuk menguji pemahaman
- 📊 Dashboard dengan statistik pembelajaran
- 👤 Sistem autentikasi (login/register)
- 🎯 Tracking pencapaian dan statistik pengguna

---

## 🛠️ Instalasi

### Prasyarat
- Node.js (versi 14 atau lebih tinggi)
- npm atau yarn package manager

### Langkah-Langkah Instalasi

1. **Clone Repository**
    ```bash
    git clone <repository-url>
    cd PROJEK-PSW-1-Kelompok-6
    ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Jalankan Aplikasi**
    ```bash
    npm start
    ```

4. **Akses Aplikasi**
    - Buka browser dan kunjungi `http://localhost:3000`

---

## 📂 Struktur Proyek

```
src/
├── components/
│   ├── Dashboard.js          # Dashboard utama
│   ├── Dashboard.css         # Styling dashboard
│   ├── Login.js              # Halaman login
│   ├── Register.js           # Halaman registrasi
│   ├── semester1/            # Materi semester 1
│   │   ├── Greetings_And_Introduction.js
│   │   ├── Recount_Text.js
│   │   ├── Descriptive_Text.js
│   │   ├── Simple_Present_Tense.js
│   │   ├── Informal_Letters.js
│   │   └── Quiz1.js
│   └── semester2/            # Materi semester 2
│       ├── Narative_Text.js
│       ├── Procedural_Text.js
│       ├── Exposition_Text.js
│       ├── Present_Continuous_Tense.js
│       ├── Report_Text.js
│       └── Quiz2.js
├── App.js                    # Routing utama
└── App.css                   # Global styling
```

---

## 🔧 Teknologi yang Digunakan

- **React** - Frontend framework
- **React Router** - Navigasi halaman
- **CSS3** - Styling dan responsif design
- **JavaScript ES6+** - Bahasa pemrograman

---

## 📝 Materi Pembelajaran

### Semester 1
1. Greetings And Introduction
2. Recount Text
3. Descriptive Text
4. Simple Present Tense
5. Informal Letters

### Semester 2
1. Narative Text
2. Procedural Text
3. Exposition Text
4. Present Continuous Tense
5. Report Text

---

## 🎮 Cara Penggunaan

1. **Register** - Buat akun baru
2. **Login** - Masuk dengan akun Anda
3. **Pilih Materi** - Akses materi dari dashboard
4. **Belajar** - Pelajari konten yang disediakan
5. **Quiz** - Uji pemahaman Anda melalui kuis

---

## 📊 Fitur Dashboard

- Selamat datang yang personal
- Dropdown akses materi semester 1 & 2
- Statistik pembelajaran pengguna
- Daftar pencapaian
- Berita dan update terbaru
- Video pembelajaran YouTube
