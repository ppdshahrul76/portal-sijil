# 🎓 Portal Sijil Digital PPDHS

Sistem Pendaftaran Kehadiran dan Penjanaan Sijil Digital Automatik untuk **Pejabat Pendidikan Daerah Hulu Selangor (PPDHS)** menggunakan Google Apps Script, Google Sheets, dan Google Slides.

## 🚀 Ciri-Ciri Utama
- **Pendaftaran Kehadiran Dalam Talian**: Antaramuka moden berfokuskan pengalaman pengguna (UI Tema Gelap / Futuristic).
- **Pelbagai Peranan**: Sokongan untuk Peserta, Penceramah, dan Fasilitator.
- **Dashboard Analitik**: Graf visual dinamik bagi jumlah sijil mengikut tahun dan sektor anjuran (menggunakan Chart.js).
- **Kelulusan Admin & Penjanaan Pukal**: Fungsi semakan dan penghantaran sijil automatik berbentuk PDF terus ke e-mel penerima.
- **Paparan Logo Dinamik**: Mengendalikan paparan logo secara *server-side* bagi melepasi sekatan firewall domain/rangkaian.

## 📁 Struktur Projek
- `Code.gs` - Logik pelayan (Server-side Apps Script: DriveApp, SlidesApp, MailApp, SpreadsheetApp).
- `Index.html` - Antaramuka Utama (Client-side HTML, CSS, JavaScript, Chart.js).
- `Logo.html` - Komponen header khas untuk paparan logo PPDHS / KPM.

## 🛠️ Cara Penggunaan
1. Buka [Google Apps Script](https://script.google.com/).
2. Salin kod daripada `Code.gs`, `Index.html`, dan `Logo.html`.
3. Pastikan `SPREADSHEET_ID` di dalam `Code.gs` dihalakan ke Google Sheet yang betul.
4. Lakukan *Deploy > New deployment > Web app*.