# SIMaDA: Sistem Informasi Manajemen Data Akademik

Project ini dikembangkan oleh **Ronanda Saputra** sebagai bagian dari Tes Teknis untuk posisi **Programmer** di **Politeknik Caltex Riau**.

---

## 📝 Pembukaan
Terima kasih atas kesempatan mengikuti tes teknis posisi Programmer di Politeknik Caltex Riau. Dokumen ini merangkum project yang telah saya selesaikan.

---

## 🚀 Tech Stack
Sistem ini menggunakan arsitektur modern untuk performa optimal.

*   **Frontend:** Next.js 16 & Shadcn UI Components library
*   **Backend:** Laravel 12
*   **Database:** PostgreSQL
*   **Version Control:** GitHub
*   **Deployment:** Frontend (Vercel) & Backend (VPS)

---

## 🛠️ Panduan Penggunaan (Local)

### 1. Backend (Laravel)
1.  **Clone Repository**
    Silakan clone project Laravel pada [Link Repository Berikut ↗️](https://github.com/nan022/api-sistem-akademik).
2.  **Siapkan Environment**
    Pastikan Anda sudah mempunyai local server seperti Laragon atau Xampp.
3.  **Instalasi Dependensi**
    Jalankan perintah berikut di terminal:
    ```bash
    composer install
    ```
4.  **Setup Database**
    Jalankan perintah ini untuk migrasi dan mengisi data awal:
    ```bash
    php artisan migrate:fresh --seed
    ```
    <img width="753" height="623" alt="image" src="https://github.com/user-attachments/assets/629dae18-2d9c-4831-98c8-ac4dc3b134c5" />

5.  **Jalankan Server**
    Mulai server lokal dengan perintah:
    ```bash
    coomposer run dev
    ```

### 2. Frontend (Next.js)
1.  **Clone Repository**
    Silakan clone project Frontend pada [Link Repository Berikut ↗️](https://github.com/nan022/sistem-akademik).
2.  **Instalasi Dependensi**
    Jalankan perintah berikut di terminal:
    ```bash
    npm install
    ```
3.  **Konfigurasi Environment**
    Salin file `.env.example` menjadi `.env` dan sesuaikan URL API backend Anda.
4.  **Jalankan Development Server**
    Mulai aplikasi dengan perintah:
    ```bash
    npm run dev
    ```

---

## 💻 Testing
**API**
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/d16d4c9d-5606-4d86-a4b9-df7275559e14" />

1.  **Menamppilkan All Data**
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/27a0a0db-c7b8-4e44-94a2-39fc1ba04ca6" />

2.  **Quick Filter**
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/f75221b3-187f-4436-ae9e-cf7ea23fb86b" />

3.  **Advance Filter**
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/07edf83c-8f2f-4111-9908-274fc5b3c090" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/72c7a4d3-d08f-4251-95a4-6082baea5344" />

4. **Insert Data (New)**
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/c5ee60ff-b48a-4267-9292-8b7bedd83501" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/44eea5d3-ce6b-45ca-939c-d3d7c6bc4a1c" />

5. **And Another Features**




