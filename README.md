# IP-LOC

**IP-LOC** adalah tools sederhana yang digunakan untuk melacak informasi lokasi berdasarkan alamat IP. Tools ini dibuat menggunakan Python dan hanya memerlukan dependensi minimal.

## Fitur

- Mendapatkan informasi lokasi berdasarkan IP, termasuk:
  - Negara, Provinsi, Kota/Kabupaten
  - Hostname, ISP
  - Zona Waktu, Lokasi Geografis (Latitude & Longitude)
- Tampilan terminal dengan warna yang menarik.
- Bersifat ringan dan mudah digunakan.

## Cara Install di Termux

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan **IP-LOC** di Termux:

### 1. Update dan Install Python

```bash
pkg update && pkg upgrade -y
pkg install python -y
```

### 2. Install Git

```bash
pkg install git -y
```

### 3. Clone Repositori

```bash
git clone https://github.com/wanzxploit/IP-LOC.git
cd IP-LOC
```

### 4. Install Dependensi

Tools ini membutuhkan library `requests`. Install dengan perintah:

```bash
pip install requests
```

### 5. Jalankan Tools

Setelah semua dependensi terinstal, jalankan tools dengan perintah berikut:

```bash
python main.py
```

## Contoh Output

```text
Masukkan IP yang ingin dilacak: 112.215.221.187

╔════════════════════════════════════════════╗
║            HASIL PELACAKAN IP              ║
╚════════════════════════════════════════════╝

KATEGORI      INFORMASI
-----------------------------------------------
 IP                  112.215.221.187
 Negara              ID
 Provinsi            Bali
 Kota/Kabupaten      Denpasar
 Hostname            N/A
 ISP                 AS24203 PT XL Axiata
 Timezone            Asia/Makassar
 Lokasi Geografis    -8.6500,115.2167
-----------------------------------------------

Tools IP-LOC By Wanz Xploit.
```

## Catatan
- Pastikan koneksi internet aktif saat menggunakan tools ini.
- Tools ini hanya untuk tujuan edukasi. Gunakan secara bertanggung jawab.

## Sosial Media
- **GitHub**: [https://github.com/wanzxploit](https://github.com/wanzxploit)
- **Instagram**: [https://instagram.com/wanz_xploit](https://instagram.com/wanz_xploit)
- **YouTube**: [https://youtube.com/wanzxploit](https://youtube.com/wanzxploit)

---
Dibuat dengan ❤️ oleh **Wanz Xploit**.
