# 🌐 Club Gratis - Web Panel

Proyek ini adalah antarmuka web dari layanan **Club Gratis** untuk membuat akun VMess, VLESS, Trojan, Shadowsocks, serta melakukan pengecekan status proxy. Web ini dibuat menggunakan **HTML statis**, **Bootstrap** (untuk `index.html`), dan **Tailwind CSS** untuk halaman-halaman pembuatan akun.

---

## 📁 Struktur Direktori


---

## 🔧 Fitur

- ✅ Cek proxy (status, negara, ISP, latensi, flag)
- ✅ Buat akun:
  - VMess
  - VLESS
  - Trojan
  - Shadowsocks
- ✅ Salin konfigurasi & tampilkan QR Code
- ✅ Responsif dan ringan

---

## 🌍 URL Akses (Contoh)

| Halaman        | URL                                     |
|----------------|------------------------------------------|
| Halaman Utama  | `https://<your.domainname.com>/`         |
| Cek Proxy      | `https://<your.domainname.com>/cekproxy` |
| VMess          | `https://<your.domainname.com>/vmess`    |
| VLESS          | `https://<your.domainname.com>/vless`    |
| Trojan         | `https://<your.domainname.com>/trojan`   |
| Shadowsocks    | `https://<your.domainname.com>/shadowsock` |

---

## ⚙️ API yang Digunakan

- 🔍 Cek Proxy: [`https://<api.yourname.com>/check?ip=IP:PORT`](https://<api.yourname.com>/check?ip=1.1.1.1:443)
- 🌐 Pembuatan Akun: via endpoint `/Club-Gratis/{ip}-{port}` dari backend Cloudflare Workers (privat)

---

## 📦 Deployment

Web ini dapat dihosting secara gratis di:

- GitHub Pages
- Cloudflare Pages
- Netlify
- Vercel

> Untuk deployment ke GitHub Pages:
1. Push semua file ke GitHub.
2. Masuk ke **Settings > Pages**.
3. Pilih branch `main` dan folder `/root` (atau `/docs` jika disimpan di sana).
4. Simpan, dan akses link publiknya.

---

## 🙌 Kontribusi

Proyek ini dikelola oleh komunitas Club Gratis. Jika kamu ingin menambahkan fitur atau perbaikan, silakan lakukan pull request.

---

## 📣 Kontak

- Telegram Channel: [Mr.king's Official](https://t.me/club_gratis1)
- Group Telegram: [Join Group](https://t.me/club_gratis)

---

## 🧡 Donasi

Dukung kami agar layanan tetap gratis untuk semua. Info donasi ada di halaman **qr-donate.jpg** di menu sidebar.

