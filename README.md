# INA OMNIUM CALCULATOR — PWA

## Upload ke GitHub Pages
1. Buat repository GitHub baru, misalnya `ina-omnium-calculator`.
2. Upload seluruh isi folder ini ke root repository: `index.html`, `manifest.webmanifest`, `service-worker.js`, dan folder `icons`.
3. Di GitHub buka Settings → Pages.
4. Pada Build and deployment pilih Deploy from a branch.
5. Pilih branch `main` dan folder `/ (root)`, lalu Save.
6. Setelah deployment selesai, buka alamat GitHub Pages yang diberikan GitHub.

## iPhone / iPad
Buka alamat GitHub Pages di Safari → Share → Add to Home Screen → Add.
Sesudah pertama kali dibuka online, service worker menyimpan file aplikasi agar dapat digunakan offline.

## Android
Buka alamat di Chrome → menu → Add to Home screen / Install app.

Catatan: bila aplikasi diperbarui, ubah nama CACHE di `service-worker.js` (mis. v1 menjadi v2) agar perangkat mengambil versi terbaru.
