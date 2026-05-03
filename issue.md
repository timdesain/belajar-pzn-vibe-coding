# Project Setup: ElysiaJS + Drizzle + MySQL

## Goal
Inisialisasi project backend baru di dalam direktori ini menggunakan ekosistem Bun.

## Tech Stack
- **Runtime & Package Manager**: Bun
- **Framework**: ElysiaJS
- **ORM**: Drizzle ORM
- **Database**: MySQL

## High-Level Tasks

1. **Inisialisasi Project Bun**
   - Lakukan inisialisasi project Bun di direktori saat ini.
   - Pastikan konfigurasi dasar seperti `package.json` dan `tsconfig.json` sudah dibuat.

2. **Instalasi Dependencies**
   - Install framework ElysiaJS.
   - Install Drizzle ORM beserta Drizzle Kit untuk keperluan migrasi.
   - Install driver MySQL yang kompatibel (misalnya `mysql2`).

3. **Konfigurasi Dasar (Boilerplate)**
   - Buat file *entry point* (misalnya `src/index.ts`).
   - Setup server ElysiaJS dasar yang mengembalikan respons "Hello World" untuk memverifikasi bahwa server bisa berjalan.
   - Setup koneksi Drizzle ORM ke MySQL (pastikan menggunakan *environment variables* untuk kredensial database).
   - Definisikan satu skema database sederhana sebagai *proof of concept* (misal: skema tabel `users`).

4. **Konfigurasi Scripts**
   - Tambahkan *script* di `package.json` untuk kemudahan *development*, contohnya:
     - Script untuk menjalankan server mode *watch* (misal: `bun run dev`).
     - Script untuk men-generate/push migrasi database menggunakan Drizzle Kit.

## Notes
- Tulis kode dengan rapi dan gunakan standar TypeScript.
- Jangan terlalu fokus pada detail implementasi bisnis logik saat ini, cukup fokus menyambungkan semua teknologi di atas (Elysia, Drizzle, dan MySQL) agar berfungsi dengan baik.
