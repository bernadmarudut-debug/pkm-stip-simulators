# PKM STIP Jakarta 2026 — Simulator Pembelajaran Interaktif

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen)](https://USERNAME.github.io/pkm-stip-simulators/)

Aplikasi simulator pembelajaran interaktif berbasis web untuk kegiatan **Pengabdian kepada Masyarakat (PKM)** Sekolah Tinggi Ilmu Pelayaran (STIP) Jakarta di SMK Pelayaran.

## 🌊 Simulator 1: Green Shipping & Sustainable Energy

Pengenalan konsep pelayaran ramah lingkungan dan teknologi energi berkelanjutan bagi calon pelaut muda.

**Fitur:**
- 4 modul materi (Green Shipping, Sustainable Energy, Studi Kasus, Indonesia & Dekarbonisasi)
- Simulator kapal interaktif (pilih bahan bakar, atur kecepatan, pasang teknologi hijau, lihat CII rating)
- 30 soal kuis latihan dengan pembahasan
- 20 soal evaluasi akhir dengan penilaian (skor 0–100, grade A–E)

📂 File: `green-shipping.html`

## 📻 Simulator 2: Maritime English Communication

Komunikasi bahasa Inggris maritim sesuai standar IMO SMCP dan STCW.

**Fitur:**
- 4 modul materi (Introduction, VHF Communication, Distress & Safety, On-Board Comms)
- Simulator VHF interaktif dengan 5 skenario (VHF Calling, Report Position, MAYDAY, PAN PAN, Pilotage)
- 30 soal kuis latihan dengan pembahasan
- 20 soal evaluasi akhir dengan penilaian (skor 0–100, grade A–E)

📂 File: `maritime-english.html`

## 🚀 Cara Install & Deploy

### Opsi A: GitHub Pages (Recommended)

1. **Buat akun GitHub** di [github.com](https://github.com) jika belum punya
2. **Buat repository baru:**
   - Klik tombol **"+"** → **"New repository"**
   - Nama: `pkm-stip-simulators`
   - Pilih **Public**
   - Centang **"Add a README file"**
   - Klik **"Create repository"**
3. **Upload file:**
   - Di halaman repository, klik **"Add file"** → **"Upload files"**
   - Drag & drop semua file: `index.html`, `green-shipping.html`, `maritime-english.html`
   - Tulis commit message: "Upload simulator files"
   - Klik **"Commit changes"**
4. **Aktifkan GitHub Pages:**
   - Pergi ke **Settings** → **Pages** (di sidebar kiri)
   - Source: pilih **"Deploy from a branch"**
   - Branch: pilih **"main"** dan folder **"/ (root)"**
   - Klik **"Save"**
5. **Tunggu 1–2 menit**, lalu akses di:
   ```
   https://USERNAME.github.io/pkm-stip-simulators/
   ```

### Opsi B: Gunakan Langsung (Offline)

File HTML bersifat **self-contained** (tidak perlu server). Cukup:
1. Download/copy file `.html` ke komputer atau flashdisk
2. Buka langsung di browser (Chrome, Firefox, Edge)
3. Bisa digunakan offline tanpa internet

### Opsi C: Install di Server/Hosting

1. Upload ketiga file HTML ke folder publik hosting Anda
2. Akses melalui domain hosting

## 📁 Struktur File

```
pkm-stip-simulators/
├── index.html              ← Landing page (halaman utama)
├── green-shipping.html     ← Simulator Green Shipping
├── maritime-english.html   ← Simulator Maritime English
└── README.md               ← Dokumentasi ini
```

## 💻 Teknologi

- **HTML5 + CSS3 + JavaScript** — Single-file, no dependencies
- **Responsive Design** — Berfungsi di desktop, tablet, dan smartphone
- **Offline-capable** — Tidak perlu koneksi internet setelah download
- **No Backend Required** — Murni client-side, tidak perlu database atau server

## 📋 Spesifikasi Teknis

| Aspek | Detail |
|-------|--------|
| Browser | Chrome 80+, Firefox 75+, Edge 80+, Safari 13+ |
| Ukuran File | ~60KB per simulator |
| Koneksi | Hanya perlu internet untuk load Google Fonts (opsional) |
| Device | Desktop, tablet, smartphone |
| Instalasi | Tidak diperlukan |

## 👥 Tim PKM

**Sekolah Tinggi Ilmu Pelayaran (STIP) Jakarta**
Badan Pengembangan SDM Perhubungan
Kementerian Perhubungan Republik Indonesia

## 📄 Lisensi

Materi pembelajaran ini dikembangkan untuk kegiatan PKM STIP Jakarta 2026.
Dapat digunakan untuk keperluan pendidikan dan non-komersial.

---

> **Catatan:** Ganti `USERNAME` pada URL di atas dengan username GitHub Anda.
