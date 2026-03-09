# Sky Watcher

Sky Watcher adalah Website cuaca yang memungkinkan pengguna melihat ramalan cuaca harian dan menyimpan kota favorit. Frontend dibangun dengan **React 18** + **Vite** + **Tailwind CSS**, sedangkan backend
menggunakan **Node.js** dengan **Express** dan menyimpan data favorit dalam file JSON.

Data cuaca diambil dari [Visual Crossing Weather API](https://rapidapi.com/visual-crossing-corporation-visual-crossing-corporation-default/api/visual-crossing-weather)
(dijalankan melalui RapidAPI) menggunakan **axios**.

---

## Fitur Utama

* Cari cuaca berdasarkan **nama kota**
* Lihat **suhu rata‑rata**, **maksimum**, dan **minimum** tiap hari
* Tampilkan **kondisi** (cerah, hujan, berawan, dll.) beserta ikon
* Ramalan cuaca mingguan
* Simpan & hapus **kota favorit** 
* UI responsif dan sederhana

## Teknologi & Dependensi

* Frontend: React 18, Vite, Tailwind CSS, axios
* Backend: Node.js 18+, Express, cors, fs (file system)
* Database ringan: file JSON 
* Build & tooling: npm, ESLint, PostCSS

## Struktur Project

```
/              ← root
├─ src/
│   ├─ backend/       ← backend Express
│   │   ├─ server.js
│   │   └─ db.json
│   ├─ Components/
│   ├─ Context/
│   ├─ Pages/
│   └─ assets/
├─ public/
├─ package.json
└─ vite.config.js
```

## Menjalankan Secara Lokal

1. Clone repositori:
   ```bash
   git clone <repo-url>
   cd Sky-Watcher-master
   ```
2. Install dependency:
   ```bash
   npm install
   ```
3. Jalankan backend:
   ```bash
   node src/backend/server.js
   ```
4. jalankan frontend:
   ```bash
   npm run dev
   ```
5. Buka http://localhost:5173 (Vite default) dan website sudah berhasil di jalankan.


