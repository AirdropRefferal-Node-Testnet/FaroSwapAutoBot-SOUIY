# FaroSwap Auto Bot - SOUIY

## 📌 Deskripsi
FaroSwap Auto Bot adalah script otomatisasi untuk melakukan berbagai aktivitas di jaringan testnet Pharos, termasuk:
- Klaim faucet PHRS dan USDT
- Swap token (PHRS ⇄ USDT)
- Menambahkan likuiditas
- Transfer PHRS antar wallet
- Check-in harian

## 🛠️ Prasyarat
- Node.js (versi 18 atau lebih baru)
- NPM/Yarn
- Git

## 📥 Instalasi
1. Clone repository ini:
```bash
git clone https://github.com/AirdropRefferal-Node-Testnet/FaroSwapAutoBot-SOUIY.git
```

2. Masuk ke direktori project:
```bash
cd FaroSwapAutoBot-SOUIY
```

3. Install dependencies:
```bash
npm install
```

## ⚙️ Konfigurasi
1. Buat file `pk.txt` yang berisi private key wallet Anda (satu key per baris)
```
nano pk.txt
```
3. (Opsional) Buat file `proxy.txt` untuk proxy (satu proxy per baris)
4. (Opsional) Buat file `wallet.txt` untuk daftar alamat tujuan transfer PHRS

## 🚀 Cara Menjalankan
```bash
node index.js
```

## 🎛️ Menu Utama
1. **Start Auto Daily Activity** - Menjalankan semua aktivitas harian secara otomatis
2. **Claim Faucet** - Menu klaim faucet (PHRS/USDT)
3. **Auto Swap PHRS & wPHRS** - Menu swap token
4. **Set Manual Config** - Mengatur konfigurasi aktivitas
5. **Clear Logs** - Membersihkan log transaksi
6. **Refresh** - Memperbarui data wallet
7. **Exit** - Keluar dari aplikasi

## ⚠️ Catatan Penting
- Script ini hanya untuk jaringan testnet
- Pastikan wallet memiliki cukup gas untuk transaksi
- Aktivitas harian akan berjalan setiap 24 jam sekali
- Ikuti perkembangan terbaru di TikTok: [AirdropRefferal (Souiy1)](https://www.tiktok.com/@airdroprefferal)

## 🤝 Donasi Palestina
- Satukan Solidaritas Bantu Palestina!
- [BANTU PALESTINA](https://digital.dompetdhuafa.org/donasi/jagapalestina)

---
