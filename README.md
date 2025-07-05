# Landing-Page-MBC
Fungsi dari landing page ini adalah untuk memperkuat citra profesional MBC Lab di ranah digital dan juga untuk menghadirkan media komunikasi yang efektif antara MBC Lab dan klien, serta sebagai etalase digital untuk memamerkan kapabilitas teknologi dan sumber daya manusia di dalamnya.
 Dibangun menggunakan HTML/CSS/JavaScript di frontend, dan PHP di backend dengan layanan InfinityFree.

 ## Struktur Proyek
 Berikut ini adalah struktur direktori dari proyek website :
 
MBC-Lab-Website/

├── index.html  # Halaman utama website

├── style.css                # File styling utama

├── script.js                # Interaksi JavaScript

├── /images/                 # Folder aset gambar

│   ├── logo-mbc.jpeg

│   ├── cybersecurity.png

│   ├── bigdata.png

│   ├── gis.png

│   └── gametech.png

├── /screenshots/            # Screenshot halaman (untuk dokumentasi)

│   ├── homepage.jpg

│   ├── divisi.jpg

│   └── kontak-form.jpg

├── README.md                # Dokumentasi utama proyek


## Instalasi Lokal
1. Clone repositori: git clone https://github.com/Mr-Sakhi/Landing-Page-MBC.git
2. Buka file index.html di browser.
3. Pastikan koneksi internet aktif (untuk load font & CDN).

## Instruksi Deployment
Website di-deploy ke subdomain gratis InfinityFree:

URL: https://mbclab.kesug.com/?i=1
Langkah:
1. Upload semua file via File Manager / FTP.
2. Pastikan index.html berada di root.
3. Pastikan gambar & CSS terhubung dengan path relatif.
   
## Konfigurasi SSL
Website sudah menggunakan SSL aktif melalui layanan ZeroSSL.

Detail Sertifikat:
- Issuer: ZeroSSL ECC Domain Secure Site CA
- Valid Until: 29 Januari 2030
- Algoritma: SHA384withECDSA
- Tool Validasi: SSL Labs

## Backend & Form Kontak
- Website tidak memiliki backend (tidak ada PHP, database, dsb).
- Form kontak dikirim menggunakan FormSubmit (layanan pihak ketiga).
- Data form akan dikirim langsung ke email tujuan.

## Alur Kerja Form:
1. User isi nama, email, dan pesan
2. Saat klik tombol Kirim, data dikirim via POST ke endpoint FormSubmit
3. User bisa diarahkan ke halaman terima kasih (thanks.html – opsional)

## Screenshot Tampilan Halaman

### Halaman Beranda/HomePage
![homepage](https://github.com/user-attachments/assets/e6d9756d-4e13-4c65-a420-821a2cc854c9)

### Halaman Divisi
![divisi](https://github.com/user-attachments/assets/45235a5e-b0a8-4b21-832f-b3a3587d8803)

### Halaman Kontak
![kontak-form](https://github.com/user-attachments/assets/0f75aba3-2e2f-42fc-b0a0-48587953e2ed)

## IDS (Intrusion Detection System)
Saat ini tidak ada sistem IDS aktif karena website tidak menggunakan server backend dikarenakan susah untuk mendapatkan host yang free backend seperti php.

## Developer
Nama: Muhammad Sakhi Daffarian
NIM: 101012400382
📧 Email: dafaryan9@gmail.com
🔗 Instagram: @sakhiii._
🔗 LinkedIn: muhammad-sakhi-daffarian

