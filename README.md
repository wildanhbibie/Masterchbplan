# CHB Sales App 🟢

Aplikasi mobile PWA untuk Sales CHB — Daily Call Report & Outlet Management.

## Fitur
- 📊 Dashboard dengan statistik harian (visit rate, order rate)
- 📅 Call Plan Mingguan — atur jadwal kunjungan per hari
- 🏪 Manajemen Outlet — input order, tandai kunjungan, catatan order
- 📦 E-Katalog Produk — harga, PPN, per karton/box, diskon
- 🧾 Manajemen Faktur — upload foto faktur langsung dari HP
- 💾 Data tersimpan otomatis di HP (localStorage)
- 📱 Bisa diinstall di HP (PWA) — tampil seperti aplikasi native

---

## Deploy ke Vercel (GRATIS)

### Cara 1: Via GitHub (Paling Mudah)

1. **Upload ke GitHub:**
   - Buka [github.com](https://github.com) → buat repo baru (contoh: `chb-sales-app`)
   - Upload semua file di folder ini

2. **Deploy ke Vercel:**
   - Buka [vercel.com](https://vercel.com) → Sign up gratis (bisa pakai GitHub)
   - Klik **"New Project"** → Import repo `chb-sales-app`
   - Klik **Deploy** — selesai! Dapat URL seperti `chb-sales-app.vercel.app`

### Cara 2: Via Vercel CLI

```bash
npm install -g vercel
cd chb-sales-app
vercel --prod
```

---

## Install di HP Android

1. Buka URL app di **Chrome** di HP
2. Klik menu **⋮** (titik tiga) di sudut kanan atas
3. Pilih **"Add to Home screen"** atau **"Install app"**
4. Aplikasi akan muncul di layar utama HP seperti app biasa!

## Install di iPhone (iOS)

1. Buka URL app di **Safari**
2. Klik tombol **Share** (kotak dengan panah ke atas)
3. Pilih **"Add to Home Screen"**
4. Tap **Add** — selesai!

---

## Catatan Penting
- Data disimpan di **localStorage** HP — tidak hilang meskipun tutup browser
- Bekerja **offline** setelah pertama kali dibuka (Service Worker)
- Tidak perlu Play Store atau App Store
- Update otomatis saat ada perubahan di Vercel
