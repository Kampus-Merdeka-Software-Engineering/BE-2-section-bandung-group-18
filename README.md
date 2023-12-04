# simple app for my capstone project using Express.JS and prisma 

# Step by step 
1. Inisiasi project npm `npm init -y`
2. Update `package.json` dengan menambahkan scripts
3. Install package yang diperlukan `npm install express mysql2 dotenv cors`
4. Install decDependency `npm install -D nodemon`
5. `node_modules` dan `package-lock.json` akan terinstall oleh `npm`
6. Buat satu file `.gitignore` agar `node_modules` dan `.env` tidak ke upload ke git
7. Buat satu file entrypoint untuk inisiasi project `index.js` setelah itu  bisa update `package.json`
8. Import express, dotenv, dan package lain yang sudah di install tadi
9. Buatlah satu rute untuk mencoba apakah aplikasi bisa jalan atau tidak
10. Gunakan prisma agar kita bisa terhubung dengan database dan melakukan get/post data ke database dengan [prisma] (https://prisma.io)
11. Install prisma untuk inisiasi project npm yang ingin diintegrasikan `npm install -D prisma`
12. inisiasi prisma `npx prisma init --datasource-provider mysql`
13. Lalu akan ada kode tambahan pada file `.env` yaitu `DATABASE_URL` ini diisi sesuai `DATABASE_URL` kita, bisa juga `DATABASE_URL` diisi dari `railway` atau kalo jalanin dari local pakai yang localhost dulu aja `"mysql://johndoe:randompassword@localhost:3306/mydb"`
14. Definisikan model rencana kita di `schema.prisma`
