# Aplikasi Task Management

---
## Fitur Utama
* **Login Pengguna**: Sistem login yang aman menggunakan JWT (JSON Web Token).
* **CRUD Tasks**: Pengguna bisa membuat, melihat, mengubah, dan menghapus (CRUD) daftar tugas mereka.
* **Halaman Terproteksi**: Halaman manajemen tugas hanya bisa diakses setelah berhasil login.
* **Update Instan**: Tampilan antarmuka (UI) akan langsung diperbarui setiap kali ada perubahan data, tanpa perlu *refresh* halaman.
* **[BONUS] Logout**: Tombol untuk keluar dari sesi dengan aman.
* **[BONUS] Search & Filter**: Fitur untuk mencari tugas berdasarkan judul dan memfilternya berdasarkan status.

---
## Teknologi yang Digunakan
* **Backend**: Node.js, Express.js, MongoDB (dengan Mongoose), JSON Web Token (JWT)
* **Frontend**: React (dibuat dengan Vite), React Router, TailwindCSS, Axios

---
## Cara Menjalankan Proyek
Berikut adalah langkah-langkah untuk menjalankan proyek ini di komputer Anda.

### Yang Dibutuhkan
* Node.js (versi 18 atau lebih baru)
* Koneksi ke database MongoDB (bisa menggunakan MongoDB Atlas gratis atau instalasi lokal)

### 1. Setup Backend
```bash
# Masuk ke folder backend
cd task-manager-backend

# Install semua package yang dibutuhkan
npm install

# PENTING: Buka file index.js dan ganti nilai MONGO_URI
# dengan connection string database MongoDB Anda.

# Jalankan server backend
npm start
```
Server akan berjalan di `http://localhost:3001`.

### 2. Setup Frontend
```bash
# Buka terminal baru, lalu masuk ke folder frontend
cd task-manager-frontend

# Install semua package yang dibutuhkan
npm install

# Jalankan aplikasi frontend
npm run dev
```
Aplikasi akan otomatis terbuka di browser, biasanya di `http://localhost:5173`.

---
## Kredensial Login
Gunakan akun di bawah ini untuk masuk ke aplikasi:

* **Username**: `admin`
* **Password**: `password123`