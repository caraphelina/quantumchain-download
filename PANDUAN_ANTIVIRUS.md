# 🛡️ Kenapa Windows / Antivirus Menahan Quantum Chain? (Aman, kok)

Saat pertama membuka **`QuantumChain.exe`**, Windows mungkin menampilkan peringatan
biru **"Windows protected your PC"** (SmartScreen), atau antivirus menahannya
sebentar.

**Ini WAJAR dan BUKAN virus.** 🙂

### Kenapa muncul?
Aplikasi ini dibuat dengan Python (PyInstaller) dan **belum punya "tanda tangan
digital"** (sertifikat itu berbayar mahal/tahunan). Windows menahan **semua**
aplikasi baru yang belum dikenal — termasuk yang aman — sampai cukup banyak
orang mengunduhnya. Jadi peringatan ini soal *"belum dikenal"*, bukan *"berbahaya"*.

---

## ✅ Cara Menjalankan (Windows SmartScreen)

1. Klik dua kali **`QuantumChain.exe`**.
2. Kalau muncul layar biru **"Windows protected your PC"**:
   - Klik teks **"More info"** (Info selengkapnya).
   - Lalu klik tombol **"Run anyway"** (Jalankan saja).
3. Aplikasi terbuka. **Langkah ini biasanya hanya perlu sekali.**

---

## ✅ Kalau Antivirus (Defender/lainnya) Menahan

Bila file dikarantina atau dihapus otomatis, izinkan secara manual:

**Windows Security (Defender):**
1. Buka **Windows Security** → **Virus & threat protection**.
2. **Protection history** → cari **QuantumChain.exe** → **Actions** → **Allow** /
   **Restore**.
3. (Opsional) Tambahkan ke pengecualian: **Manage settings** →
   **Add or remove exclusions** → **Add an exclusion** → **Folder** → pilih
   folder Quantum Chain.

**Antivirus pihak ketiga (Avast, AVG, dll.):**
- Buka **Quarantine / Karantina** → pilih file → **Restore** + **Add to exclusions**.

---

## 💡 Tips Aman

- **Unduh HANYA dari halaman resmi** (link Releases yang dibagikan admin). Jangan
  dari sumber lain — itulah cara terbaik memastikan file asli.
- Kalau ragu, kamu boleh memindai file di **virustotal.com** (unggah `.exe`,
  cek hasilnya). Beberapa pemindai mungkin memberi "false positive" — itu hal
  umum untuk aplikasi PyInstaller.
- File ini **tidak butuh internet** kecuali saat **login** (verifikasi token).

---

*Quantum Chain — Kamus Sambung Kata. Token dari: Roblox `blondesigma666` ·
Discord `caraphelina666`.*
