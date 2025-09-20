<!-- README.md -->

<p align="center">
  <img
    src="https://images.unsplash.com/photo-1517180102446-f3ece451e9d8?auto=format&fit=crop&w=800&q=60"
    alt="Simple Web Illustration"
    width="600"
  />
</p>

<h1 align="center">Simpel Base Express js - fmds</h1>

<p align="center">
  <em>Project Base Express js website mudah di gunakan .</em>
</p>

---

## 🧭 Deskripsi
Repo ini berisi contoh dasar bagaimana melayani beberapa halaman HTML (`namafile1.html`, `namafile2.html`, `gaktaumls.html`) melalui **Express.js**.  
Tidak ada view engine (EJS/Pug) — semua file HTML diletakkan di folder `NamaFolderBebas` dan disajikan secara statis via `res.sendFile()`.  
UI-nya dibuat simpel agar fokus pada logika routing & struktur proyek.`
`Struktur sudah cukup simpel dan enak buat belajar dan juga sudah`
`support vercel dan localhost`

---

## 🧪 Teknologi & Bahasa Pemrograman
| Layer        |       Bahasa       |
|--------------|--------------------|
| Backend      | Node.js + Express.js |
| Frontend     | HTML5 + CSS3 + Vanilla JavaScript |
| Lain-lain    | dotenv (opsional), chalk (logger) |

---

## ⚙️ Instalasi & Menjalankan
1. Clone repo
   ```bash
   git clone https://github.com/username/simple-express-static-web.git
   cd simple-express-static-web
   ```

2. Install dependensi
   
```bash
   npm install
   ```

3. Jalankan server
   
```bash
   npm start
   # atau
   node index.js
   ```

4. Buka browser

   [http://localhost:4000](http://localhost:4000)

---

📁 Struktur Folder

```
simple-express-static-web/
├── index.js                 # Entry point Express
├── package.json
├── .env.             # contoh kalo mau make .env
├── README.md
└── NamaFolderBebas/
    ├── namafile1.html       # Halaman utama
    ├── namafile2.html       # Halaman dua
    └── gaktaumls.html       # Halaman feedback (link Telegram & WhatsApp)
    # ini semua nya bisa lu ubah sesuka lu dah
```

---

🔍 Endpoint yang Tersedia

Route	File HTML yang Disajikan	
`/`	`NamaFolderBebas/namafile1.html`	
`/homedua`	`NamaFolderBebas/namafile2.html`	
`/fedbck`	`NamaFolderBebas/gaktaumls.html`	

---

🎯 Feature
- Menggunakan Express js dan html css js 
- mudah di gunakan dan bisa di kembangkan
- ini hanya base untuk belajar dan lainya
- di setiap kode gw tambhin komentar biar ngga bingung

---

📄 Lisensi
MIT License — bebas dipakai & dikembangkan.

---

Happy coding! 🚀
