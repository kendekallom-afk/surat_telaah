# 🗺️ Peta Hasil Telaahan - Aplikasi Web GIS

Aplikasi web untuk pembuatan peta hasil telaahan lahan, dirancang khusus untuk mendukung pembuatan lampiran surat keterangan status kawasan hutan. Aplikasi ini dapat berjalan di **desktop maupun HP** tanpa perlu instalasi.

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
| :--- | :--- |
| **📍 Plot Titik Koordinat** | Menampilkan titik koordinat dengan emoji 📍 dan label koordinat permanen |
| **🛰️ Basemap Online** | Pilihan Google Satellite, Google Maps, dan Google Hybrid |
| **🖼️ Basemap Lokal** | Upload citra/orthophoto sendiri sebagai basemap |
| **🌲 GeoJSON Kawasan Hutan** | Upload file GeoJSON untuk menampilkan batas kawasan hutan |
| **📐 Grid Metrik** | Grid koordinat dengan jarak bisa diatur (10m - 500m) di **luar box peta** |
| **📄 Layout Cetak PDF** | Layout siap cetak dengan kop surat, skala, kompas, dan legenda |
| **📱 Responsif** | Berjalan di desktop dan HP dengan tampilan yang menyesuaikan |
| **⚙️ Dinamis** | Data pemohon, nomor surat, desa, dan status lahan bisa diubah |

---

## 🖥️ Demo Langsung

Akses aplikasi melalui GitHub Pages:

[https://kendekallom-afk.github.io/surat_telaah/](https://kendekallom-afk.github.io/surat_telaah/)

---


---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Fungsi |
| :--- | :--- |
| **Leaflet.js** | Engine peta interaktif |
| **Turf.js** | Analisis spasial dan pembuatan grid metrik |
| **HTML5 + CSS3** | Struktur dan tampilan layout |
| **JavaScript** | Logika interaktif dan manajemen data |

---

## 📁 Struktur File


> **Catatan**: Aplikasi ini dibuat dalam **satu file HTML** untuk kemudahan deployment dan penggunaan offline.

---

## 🚀 Cara Menggunakan

### 1. Buka Aplikasi
- Online: [https://kendekallom-afk.github.io/surat_telaah/](https://kendekallom-afk.github.io/surat_telaah/)
- Offline: Buka file `index.html` di browser

### 2. Mengelola Data
Klik tombol **⚙ Data / Layer** di pojok kiri bawah untuk:
- Mengubah nama pemohon, nomor surat, desa, kecamatan, kabupaten
- Mengatur tanggal surat
- Memilih status lahan (APL/KH/Sebagian/Verifikasi)
- Mengupload basemap lokal atau GeoJSON kawasan hutan

### 3. Mengatur Basemap
- **Basemap Lokal**: Klik `+ Basemap Lokal` → pilih file gambar (citra/orthophoto)
- **Basemap Online**: Klik `🌐 Pilih Basemap Online` → pilih Google Satellite/Maps/Hybrid

### 4. Mengatur Kerapatan Grid
- Buka panel **⚙ Data / Layer**
- Geser slider **🌐 Kerapatan Grid (meter)** (10m - 500m)
- Grid akan otomatis berubah sesuai skala peta

### 5. Cetak / Simpan PDF
- Klik tombol **Cetak / Simpan PDF** di panel editor
- Atau gunakan fitur Print dari browser (Ctrl+P / Cmd+P)

---

## 📌 Contoh Data

### Titik Koordinat Contoh
| Titik | Bujur (BT) | Lintang (LS) |
| :--- | :--- | :--- |
| 1 | 119.16314 | -2.36012 |
| 2 | 119.16386 | -2.36013 |
| 3 | 119.16307 | -2.36060 |
| 4 | 119.16388 | -2.36054 |

### Status Lahan
- **APL** : Areal Penggunaan Lain
- **KH** : Kawasan Hutan
- **KH/APL** : Sebagian Kawasan Hutan
- **VER** : Perlu Verifikasi

---

## 🔧 Pengembangan Lebih Lanjut

Beberapa fitur yang bisa dikembangkan:

- [ ] Analisis spasial otomatis dengan Turf.js (cek titik di dalam poligon kawasan hutan)
- [ ] Plot titik baru langsung di peta (klik atau GPS)
- [ ] Ekspor KML / Shapefile untuk ArcGIS
- [ ] Penyimpanan data ke localStorage
- [ ] Peta indeks otomatis

---

## 📜 Lisensi

Hak Cipta © 2026. Dibuat untuk keperluan administrasi pertanahan dan kehutanan.

---

## 👤 Kontak

Untuk pertanyaan atau saran, silakan buka issue di repository ini atau hubungi pengembang.

---

**Dibuat dengan ❤️ untuk memudahkan tugas telaahan lahan di kantor.**

## 📸 Tampilan Aplikasi
