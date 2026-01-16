[![React](https://img.shields.io/badge/React-19.2.3-61DAFB?logo=react&logoColor=black)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

## 🚀 Cara Instalasi (Local Development)

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek ini di komputer Anda:

### 1. Prasyarat
Pastikan Anda sudah menginstal:
- [Node.js](https://nodejs.org/) (Versi terbaru sangat direkomendasikan)
- [Git](https://git-scm.com/)

### 2. Clone Repositori
Buka terminal/command prompt dan jalankan perintah berikut:
```bash
git clone https://github.com/FataZikrillah/react-app.git
```
*(Ganti `USERNAME/REPO_NAME` dengan URL repositori Anda)*

### 3. Masuk ke Direktori Proyek
```bash
cd react-app
```

### 4. Instal Dependensi
```bash
npm install
```

### 5. Jalankan Aplikasi
```bash
npm start
```
Aplikasi akan berjalan di [http://localhost:3000](http://localhost:3000).

## 📦 Script yang Tersedia

Di dalam direktori proyek, Anda dapat menjalankan:

- `npm start`: Menjalankan aplikasi dalam mode pengembangan.
- `npm run build`: Membangun aplikasi untuk produksi ke folder `build`.
- `npm test`: Menjalankan test runner.
- `npm run eject`: **Peringatan!** Ini akan menghapus konfigurasi bawaan dan mengekspos file konfigurasi internal.

## 📂 Struktur Folder
```text
react-app/
├── public/          # File statis (index.html, favicon)
├── src/             # Kode sumber utama
│   ├── App.js       # Komponen utama
│   ├── index.js     # Entry point React
│   └── index.css    # Style global & Tailwind imports
├── tailwind.config.js # Konfigurasi Tailwind
└── package.json     # Daftar dependensi & script
```

