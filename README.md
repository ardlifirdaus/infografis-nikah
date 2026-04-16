# 💍 Pesta Satu Hari, Beban Bertahun-Tahun

> Infografis interaktif edukasi keuangan pernikahan untuk pemuda Indonesia.

---

## 🎯 Tentang Proyek Ini

Banyak pemuda Indonesia rela menghabiskan **lebih dari satu tahun tabungan** — bahkan berutang — hanya untuk sebuah pesta pernikahan. Padahal setelah menikah, kebutuhan finansial justru semakin bertambah.

Proyek ini hadir sebagai **edukasi keuangan berbasis data**, bukan untuk melarang menikah atau merayakannya — tapi untuk memastikan satu hari pesta tidak menghancurkan bertahun-tahun kerja keras.

---

## ✨ Fitur

| Fitur | Keterangan |
|---|---|
| 📊 Data riil | Bersumber dari Ditjen Badilag, BPS, OJK, Bank Indonesia |
| 🧮 Kalkulator interaktif | Hitung dampak finansial sesuai gaji & biaya pesta |
| 🏔️ Visualisasi cicilan | Lihat gunung utang pasca nikah secara real-time |
| 📈 Simulasi investasi | Proyeksi 5, 10, 20 tahun jika uang pesta diinvestasikan |
| 💡 Solusi alternatif | 4 pilihan bijak yang konkret dan actionable |
| 🌗 Dark mode | Otomatis mengikuti preferensi sistem |
| 📱 Responsive | Tampil rapi di mobile & desktop |
| ⚡ Zero dependency | Tidak butuh framework, library, atau koneksi internet |

---

## 📸 Preview

```
┌─────────────────────────────────────┐
│  💍  Pesta satu hari,               │
│      beban bertahun-tahun           │
│                                     │
│  📊 Data riil  🧮 Kalkulator  💡 Solusi │
├─────────────────────────────────────┤
│  01  Angka yang harus kamu ketahui  │
│  02  Kalkulator dampak pestamu      │
│  03  Gunung cicilan pasca nikah     │
│  04  Realita pernikahan Indonesia   │
│  05  Jika uang pesta diinvestasikan │
│  06  Pilihan yang lebih bijak       │
└─────────────────────────────────────┘
```

---

## 🚀 Deploy

### Netlify Drop — *paling cepat (30 detik)*
1. Rename file menjadi `index.html`
2. Buka [app.netlify.com/drop](https://app.netlify.com/drop)
3. Drag & drop file → langsung dapat URL publik

### GitHub Pages — *paling rapi*
```bash
# 1. Buat repository baru di GitHub
# 2. Upload index.html
# 3. Settings → Pages → branch main → Save
# Live di: https://username.github.io/nama-repo
```

### Embed ke Google Sites
```html
<!-- Setelah deploy ke Netlify/GitHub Pages -->
Insert → Embed → masukkan URL
```

---

## 📦 Struktur File

```
📁 proyek/
├── 📄 index.html          # Infografis utama (all-in-one)
└── 📄 README.md           # Dokumentasi ini
```

> Seluruh kode HTML, CSS, dan JavaScript ada dalam **satu file** — tidak ada dependency eksternal.

---

## 📊 Sumber Data

| Data | Sumber |
|---|---|
| Angka perceraian 2019–2022 | Direktorat Jenderal Badan Peradilan Agama, Mahkamah Agung RI |
| UMP rata-rata 2024 | Badan Pusat Statistik (BPS) |
| Bunga KTA | Referensi produk KTA bank umum (rata-rata 18%/tahun) |
| Return investasi | OJK · rata-rata reksa dana saham Indonesia jangka panjang (11%/tahun) |
| Estimasi biaya pesta | Survei & laporan konsultan wedding Indonesia |

---

## 🧮 Asumsi Kalkulator

```
Tabungan bulanan     : 20% dari gaji bersih
KTA pesta            : bunga 18%/tahun, tenor 36 bulan
KPR (estimasi)       : Rp 3.500.000/bulan
Cicilan kendaraan    : Rp 1.500.000/bulan
Return investasi     : 11%/tahun (compounding)
Aturan cicilan sehat : ≤ 30% dari gaji bersih
```

---

## 💻 Cara Pakai Lokal

Tidak perlu server. Cukup buka file di browser:

```bash
# Klik dua kali file index.html
# atau via terminal:
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 🎨 Animasi & UI

- **Floating icon** — hero icon melayang naik-turun
- **Heartbeat** — ikon perceraian berdetak
- **Pop-in** — kartu statistik muncul berurutan
- **Scroll reveal** — setiap section muncul saat di-scroll
- **Bar grow** — progress bar tumbuh dari nol dengan easing smooth
- **Shimmer** — strip warna bergerak di atas & bawah halaman
- **Pulse** — live alert berkedip merah
- **Hover lift** — kartu terangkat saat di-hover

---

## 🤝 Kontribusi

Proyek ini open untuk:
- 🐛 **Bug fix** — temukan & laporkan masalah
- 📊 **Update data** — data perceraian atau UMP terbaru
- 🌐 **Terjemahan** — versi Bahasa Inggris atau bahasa daerah
- 📱 **Peningkatan UI** — ide tampilan yang lebih baik

---

## 📄 Lisensi

Bebas digunakan, dimodifikasi, dan disebarluaskan untuk keperluan **edukasi non-komersial**.

Jika membagikan ulang, sertakan kredit dan tautan ke proyek ini.

---

## 🙏 Pesan dari Pembuat

> *"Pernikahan adalah awal — bukan puncak. Rumah tangga yang kuat dibangun di atas fondasi finansial yang sehat, bukan di atas sisa utang pesta. Yang paling dikenang bukan seberapa megah pestanya — tapi seberapa kuat kalian menghadapi hidup bersama."*

---

<div align="center">

Dibuat dengan ❤️ untuk edukasi keuangan pemuda Indonesia

**Bukan untuk menghakimi — tapi untuk melindungi masa depanmu.**

</div>
