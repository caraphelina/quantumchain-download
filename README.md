# 🔗 Quantum Chain — Kamus Sambung Kata (Roblox)

Aplikasi desktop pendamping untuk game Roblox **[ARENA!] Sambung Kata**. Bantu
temukan kata berdasarkan **awalan / akhiran / keduanya** dan **suffix-spam
berlapis**, pasang **jebakan** agar lawan mentok, dan **analisis pola
pertandinganmu** — lengkap dengan asisten strategi, mode overlay, profil ganda,
kamus cadangan puluhan ribu kata, dan tema yang bisa diganti (gelap / terang /
sakura).

> Kamus ini **tidak diperjualbelikan**.

---

## ⬇️ Cara Pakai (untuk pemain)

1. Buka halaman **[Releases](../../releases)**.
2. Unduh file **`QuantumChain.exe`** dari rilis terbaru.
3. Taruh di satu folder khusus (mis. `Documents\QuantumChain\`), lalu **klik dua
   kali** untuk menjalankan — **tanpa install**.
4. Masukkan **token** yang kamu dapat (lihat kontak di atas) untuk login.

**Catatan:**
- Saat pertama dijalankan, folder `data/` & `backup/` dibuat otomatis di samping
  `.exe` — **di situlah progres kamu tersimpan.**
- Saat ada update, kamu bisa pakai **Update otomatis** di dalam aplikasi, atau
  **ganti `.exe` lama** dengan yang baru **di folder yang sama**. Jangan hapus
  folder `data/` — itu progres kamu.
- Launch pertama bisa agak lambat (wajar untuk file `.exe` mandiri). Bila
  antivirus menahan, izinkan saja — ini umum untuk aplikasi PyInstaller.

---

## ✨ Fitur

### 🔎 Pencarian Kata
- **Mode pencarian:** Awalan, Akhiran, Awalan + Akhiran, dan **Suffix Spam**
  (hasil berlapis: suffix → akhiran mematikan → kata nyambung prefix → cadangan).
- **Index Kata** — tandai kata yang sudah dipakai agar tidak terulang.
- **Kamus Cadangan diperluas** — puluhan ribu kata (KBBI gabungan, nama tempat,
  nama orang, bahasa gaul, bahasa Jawa, flora-fauna) dari **folder** maupun
  **sumber online** yang menyegarkan diri otomatis.
- Saat awalan sudah **terindeks penuh**, kata cadangan teratas muncul **di atas**.
- **Penanda DiCoba** (Shift + klik-kanan kata cadangan) & **pembersihan kamus
  otomatis** (kata 1–2 huruf / bersimbol dibuang).

### 🪤 Cari Jebakan — *disesuaikan dengan mode game*
Menemukan akhiran kata yang **paling sulit disambung lawan**, sesuai aturan tiap
mode: **Santai** (1 huruf, tanpa X/Q/F), **Normal** (1–3 huruf), **Brutal** (2–5
huruf). Tiap akhiran diberi indikator **"lawan mentok X/Y"** dan ada filter
**sembunyikan imbuhan umum** (-kan/-an/-nya/-i).

### 📈 Analisa Match
Rekam pertandingan (**Alt+A** mulai → **Alt+S** selesai) lalu lihat **panjang
sambungan rata-rata per menit**, **sebarannya**, dan kaitannya dengan **panjang
kata yang kamu ketik**.

### ⚔️ Strategi & Pertandingan
- 🧠 **Asisten Strategi Live** (Alt+W) — rekomendasi kata terbaik real-time.
- ⛓️ **Jebakan Berantai** — analisis 2 langkah (EMAS / KUAT / BERISIKO).
- 🎯 **Overlay Compact** (Alt+O) — panel ringkas mengambang di atas game.
- 🏆 **Match Timer**, **Riwayat**, **Replay**, **Dashboard**, **Album A–Z**,
  **Chain Map**, dan **REKOR HARIAN**.

### 👤 Profil, Tampilan & Lainnya
- 👥 **Profil ganda** — simpan beberapa progres terpisah & berpindah dari hub Profil.
- ℹ️ **Tentang Aplikasi** dengan tautan Discord, Roblox, GitHub + **tombol Ko-fi**.
- 🧭 **Sidebar** ditata ulang (hub Profil / Bantuan / Tentang / Informasi Update),
  bisa diciutkan, kategori membuka-menutup otomatis.
- 🎮 **Discord Rich Presence** — status "sedang main Quantum Chain" di Discord.
- ⚙️ **Mode Grafis (Lite / High)** di menu Kontrol — performa vs animasi penuh.
- 🔄 **Update otomatis** — unduh & pasang versi baru saat dijalankan ulang.
- ➕ **Tambah banyak kata sekaligus** (pisah koma/spasi, mis. `asi, asik, arta`).
- 🗑️ **Hapus kata** cepat (Shift + klik-kanan kartu utama).
- ⌨️ **Command Palette** (Ctrl+K) untuk semua aksi.
- 🎨 **Tema:** Gelap, Terang, dan **Sakura** (pink).
- 💾 Progres tersimpan otomatis & anti-korupsi, dengan **backup harian**.

---

## Quantum Chain 1.8

✨ **Baru**
- **Info bar baru** — progres pencarian kini menampilkan **persentase selesai**
  (donut) plus ikon **Terindex / Belum / Total**, dan terupdate **langsung**
  setiap kamu push index.
- **Keamanan data** — seluruh database kata (kamus utama, Kamus Cadangan, dan
  cache online) sekarang **terenkripsi**, jadi tidak bisa disalin langsung dari
  file.

🛠️ **Penyempurnaan**
- Pintasan **Shift+Home**: hapus kata utama paling atas.
- Penghapusan kata kini **instan** (tanpa jeda kedip).
- Perbaikan **OCR** untuk huruf berspasi lebar.
- Penyempurnaan penghitung mode **spam-akhiran**.
  
---
*Dibuat untuk komunitas Sambung Kata Roblox.*
---

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


*Dibuat untuk komunitas Sambung Kata Roblox.*
