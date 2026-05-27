## CLASSIFIED INTELLIGENCE TERMINAL — Simulation

**Tagline:** *Tactical. Classified. Cinematic. Simulation Only.*

> **⚠ DISCLAIMER**  
> Proyek ini adalah **SIMULASI FIKTIF** untuk tujuan edukasi, visualisasi antarmuka, dan riset UI/UX.  
> **TIDAK** memiliki kemampuan intelijen nyata, alat ofensif, spyware, malware, atau sistem pemantauan ilegal.  
> Semua data bersifat **dummy**, log palsu, dan koneksi simulasi. Tidak ada operasi rahasia atau aktivitas intelijen sungguhan.  
> Hanya boleh digunakan sebagai demonstrasi desain terminal taktis bergaya pemerintahan.

---

## 📡 Platform Overview

**CNSD-TERMINAL** adalah simulasi *workstation* intelijen kelas atas yang terinspirasi oleh pusat operasi siber pemerintahan dan film-film thriller teknologi. Dibangun sepenuhnya dengan HTML, CSS, dan JavaScript vanilla, platform ini mereplikasi atmosfer terminal rahasia dengan:

- Antarmuka hitam matte bertema *deep intelligence blue*
- Animasi CRT dan efek pemindaian
- Multi-panel dashboard waktu nyata
- Terminal perintah dengan autentikasi dan log simulasi
- Peta global interaktif dan visualisasi topologi jaringan
- Matriks ancaman dan umpan sinyal intelijen

Semuanya berjalan di browser tanpa backend, cocok di-hosting di GitHub Pages.

---

## 🧠 Intelligence Modules (Simulated)

| Modul | Deskripsi |
|-------|------------|
| `Secure Authentication` | Layar login dengan kredensial terenkripsi (demo: `demo`/`demo`) |
| `Classified Terminal` | Shell perintah realistis dengan 15+ perintah simulasi (`inspect`, `trace`, dll) |
| `Telemetry Feed` | Log kejadian sistem langsung dengan timestamp dan tag |
| `Tactical World Map` | Peta dunia bergaya terminal dengan node berdenyut dan sapuan radar |
| `Network Topology` | Graf node yang bergerak sendiri mewakili infrastruktur jaringan |
| `Threat Severity Matrix` | Tabel tingkat ancaman (CRITICAL/HIGH/MEDIUM/LOW) yang diperbarui otomatis |
| `Signal Intelligence (SIGINT)` | Umpan sinyal fiktif dengan frekuensi, modulasi, dan dekripsi |
| `Mission Activity Tracker` | Pelacak misi taktis (tersedia melalui tab) |
| `System Integrity Board` | Indikator status sistem di bilah atas (SYNC, THREAT LVL, ALERT) |

---

## ✨ Key Features

- 🎥 **Cinematic boot sequence** dengan seni ASCII dan progres enkripsi
- 💻 **Terminal interaktif** dengan riwayat perintah, autocomplete, dan kursor berkedip
- 🌍 **Visualisasi global** dengan node dan koneksi terenkripsi animasi
- 🛡️ **Autentikasi bertingkat** sebelum masuk workspace
- 📊 **Dashboard modular** dengan grid yang responsif (desktop/tablet/mobile)
- 🔄 **Log simulasi waktu nyata** yang terus diperbarui
- 🖱️ **Navigasi berbasis keyboard** (Ctrl+K untuk bersihkan terminal, tombol panah)
- 🎛️ **Efek CRT scanline dan flicker** untuk nuansa monitor analog

---


Setiap perintah mengembalikan data dummy yang konsisten dengan tema intelijen. Implementasi menggunakan objek `commands` di JavaScript, sehingga mudah ditambahkan perintah baru.

### Autentikasi
Kredensial demo disimpan dalam array `validCreds`. Anda dapat mengubah atau menambahkan pengguna di bagian skrip.

### Visualisasi
- **World Map:** Dibangun dengan Canvas 2D, menggambar garis pantai sederhana dan node yang berdenyut. Garis koneksi menggunakan animasi *dash offset*.
- **Network Topology:** Node bergerak secara acak dalam kanvas, saling terhubung jika jarak cukup dekat. Efek *pulse* memberikan kesan lalu lintas data.

---

## 🔒 Security Disclaimer

**Proyek ini adalah SIMULASI dan tidak memiliki kemampuan nyata untuk:**

- Melakukan pengawasan atau intersepsi komunikasi
- Mengakses sistem atau jaringan sungguhan
- Mengeksploitasi kerentanan
- Mengumpulkan data pribadi
- Menjalankan alat ofensif siber apa pun

Semua perintah, log, dan data adalah **fiktif** dan dibuat secara acak di browser Anda. Tidak ada data yang dikirim ke server mana pun. Proyek ini murni untuk keperluan **edukasi, desain UI, portofolio, dan hiburan**.

Dengan menggunakan proyek ini, Anda setuju untuk tidak menyalahgunakannya untuk aktivitas ilegal atau tidak etis.

---

## 🛠️ Customization Guide

### Mengganti Kredensial Login
Buka bagian `validCreds` di dalam tag `<script>`:
```js
const validCreds = [
    { user: 'operator', pass: 'classified' },
    { user: 'admin', pass: 'secure123' },
    // tambahkan sendiri
];
