
AI Keuangan Chatbot — Final (Local, Client-side)
===============================================

Generated: 2025-11-05

Isi paket:
- index.html  -> Halaman chat UI (mirip ChatGPT)
- style.css   -> Styling tema AMOLED/Dark/Bright, chat bubbles
- script.js   -> Logika percakapan, parsing angka, perhitungan realistis, local learning
- ai_memory.json -> Contoh kamus awal (juga disimpan di localStorage saat jalan)
- README.md   -> Panduan singkat

Cara pakai lokal:
1. Ekstrak ZIP dan buka index.html di browser (Chrome/Firefox). Semua bekerja offline.
2. Ketik input di bagian bawah seperti: '5000' atau 'lima ribu' atau 'penghasilan 5 juta per bulan'.
3. Ikuti percakapan chat; AI akan menanyakan periode, tabungan, target, dan durasi.
4. Di Pengaturan (⚙️) kamu bisa ubah tema, gaya bahasa, atau aktifkan notifikasi.

Catatan teknis & privasi:
- Semua data disimpan di LocalStorage. Untuk penggunaan multi-user dan server, perlu backend.
- AI menyimpan kamus sederhana dan pengaturan di localStorage untuk memahami typo dan istilah lokal.
- Untuk export data: buka DevTools -> Application -> Local Storage -> copy JSON.
