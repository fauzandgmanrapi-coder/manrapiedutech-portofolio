# Manrapi EduTech — Portofolio Online v2026-10-26-v1

Situs portofolio 1 halaman, statis (HTML + CSS). Tanpa database, tanpa env var, tanpa build rumit — jadi tidak ada risiko gagal build seperti aplikasi Next.js.

## Isi paket
- `index.html` — halaman utama (marker versi di baris ke-2)
- `style.css` — tampilan (gradasi navy–sky, aksen emas, responsif HP)
- `assets/logo.png` — logo final Manrapi EduTech (512×512)
- `VERSION.txt` — baris pertama = nama versi paket ini
- `README.md` — panduan ini

## SELF-CHECK SEBELUM UPLOAD (wajib, 30 detik)
1. Ekstrak ZIP ini ke folder BARU bernama `manrapiedutech-portofolio-v2026-10-26-v1` — jangan timpa folder lama.
2. Buka `VERSION.txt` → baris pertama harus: `MANRAPI EDUTECH PORTOFOLIO ONLINE v2026-10-26-v1`
3. Buka `index.html` → baris ke-2 harus berisi: `MANRAPI-EDUTECH-PORTOFOLIO-v2026-10-26-v1`
Kalau salah satu tidak cocok, berarti yang terbuka adalah paket lama — berhenti dan pakai folder ekstrak baru ini.

## LANGKAH DEPLOY

### 1. GitHub (akun fauzandgmanrapi-coder — akun yang sama dengan Smart Class)
1. github.com → tombol **+** → **New repository**
2. Repository name: `manrapiedutech-portofolio` → Public → **Create repository**
3. Klik **uploading an existing file**, lalu upload SEMUA isi folder ekstrak ini:
   `index.html`, `style.css`, `VERSION.txt`, `README.md`, dan folder `assets` (berisi logo.png)
4. **Commit changes**

### 2. Vercel
1. vercel.com → **Add New… → Project**
2. Import repo `manrapiedutech-portofolio` (pastikan sesi GitHub di browser yang sama login sebagai fauzandgmanrapi-coder)
3. Project Name: `manrapiedutech` ← nama ini yang menentukan domain `manrapiedutech.vercel.app`
4. Framework Preset: **Other** (jangan diubah, tidak ada Build Command / Output khusus)
5. TIDAK ADA Environment Variable yang perlu diisi.
6. **Deploy** → tunggu sampai selesai (biasanya < 1 menit)

### 3. Kabari Fauzan setelah deploy
Kirim link hasilnya — Fauzan akan verifikasi langsung di situs live:
halaman tampil + tulisan versi `v2026-10-26-v1` di footer paling bawah.

### Setelah live
Pasang link `https://manrapiedutech.vercel.app` sebagai link di bio Instagram @manrapiedutech.
