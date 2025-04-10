# Musisi Indonesia Beraksi

Platform untuk booking musisi, chat real-time, unggah audio/video, dan sistem penjadwalan berbasis Firebase.

## Cara Menjalankan

1. Salin `.env.example` ke `.env.local` dan isi kredensial Firebase & Midtrans
2. Jalankan: `npm install`
3. Jalankan: `npm run dev`

## Folder Struktur
- `components/` - Komponen UI seperti UploadForm, ChatBox
- `pages/` - Halaman utama (login, register, dashboard, dll)
- `utils/firebase.js` - Koneksi Firebase
- `firebase-functions/` - Fungsi notifikasi & reminder otomatis

## Deploy Firebase
```bash
firebase deploy --only hosting,functions
```

## CI/CD
- Bisa diintegrasikan dengan GitHub Actions / Vercel / Netlify

## Fitur
- Booking & penjadwalan
- Chat real-time
- Upload video/audio
- Halaman profil musisi
- Notifikasi & reminder otomatis
- Pembayaran Midtrans
