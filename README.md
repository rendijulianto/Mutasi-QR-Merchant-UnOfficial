# 🚀 BCA QR Merchant Mutation Checker API

> Solusi otomatis untuk **mengambil data mutasi transaksi QR Merchant BCA** — cepat, stabil, dan siap diintegrasikan ke berbagai sistem seperti dashboard admin, monitoring transaksi, maupun aplikasi fintech.

---

## ✨ Features

| Fitur | Deskripsi |
|---|---|
| 🔐 **Secure Login** | Autentikasi aman untuk akses merchant |
| 📅 **Mutasi Harian** | Ambil data transaksi berdasarkan tanggal hari ini |
| 📆 **Mutasi Mingguan** | Monitoring transaksi dalam 7 hari terakhir |
| 🗓️ **Mutasi Bulanan** | Rekap transaksi selama 1 bulan penuh |
| 📊 **Structured Response** | Output JSON rapi dan mudah diolah |
| ⚡ **Fast & Lightweight** | Dioptimalkan untuk performa tinggi |
| 🔄 **Ready Integration** | Mudah diintegrasikan ke Laravel, Node.js, dan backend lainnya |

---

## 📦 Use Cases

Script ini cocok digunakan untuk:

- ✅ Sistem **monitoring pembayaran QRIS**
- ✅ Dashboard **laporan keuangan merchant**
- ✅ Integrasi ke **aplikasi top-up / payment gateway**
- ✅ Automasi **rekap transaksi harian**

---

## 📥 Installation

**PHP / Laravel:**

```bash
git clone https://your-repo-url.git
cd bca-qris-mutation
composer install
```

**Node.js:**

```bash
npm install
```

---

## ⚙️ Configuration

Sesuaikan credential pada file `.env`:

```env
BCA_USERNAME=your_username
BCA_PASSWORD=your_password
```

---

## 🚀 Usage

### 1. Login

```bash
php artisan bca:login
```

### 2. Cek Mutasi Harian

```bash
php artisan bca:mutation --type=daily
```

### 3. Cek Mutasi Mingguan

```bash
php artisan bca:mutation --type=weekly
```

### 4. Cek Mutasi Bulanan

```bash
php artisan bca:mutation --type=monthly
```

---

## 📄 Example Response

```json
{
  "status": true,
  "message": "Success",
  "data": [
    {
      "date": "2026-05-01",
      "amount": 150000,
      "type": "CR",
      "description": "QRIS PAYMENT",
      "reference": "ABC123XYZ"
    }
  ]
}
```

---

## 🔐 Security Notes

- Pastikan credential **tidak dibagikan secara publik**
- Gunakan `.env` untuk menyimpan data sensitif
- Disarankan menggunakan **proxy / IP whitelist** jika diperlukan

---

## ⚠️ Disclaimer

Script ini dibuat untuk kebutuhan automasi dan monitoring internal. Gunakan dengan bijak dan sesuai dengan kebijakan dari pihak bank terkait.

---

## 💼 Why Choose This Script?

- ✔ **Stabil & sudah teruji** di lingkungan produksi
- ✔ **Response cepat & akurat** tanpa overhead berlebih
- ✔ **Mudah digunakan** bahkan untuk non-expert sekalipun
- ✔ **Support pengembangan lanjutan** sesuai kebutuhan bisnis

---

## 📞 Support & Contact

Butuh bantuan integrasi atau custom feature? Hubungi kami:

- 📧 **Email:** rendijulianto37@gmail.com
- 💬 **WhatsApp / Telegram:** 082129632854

---

## ⭐ Closing

> *"Automate your transaction tracking. Save time. Scale faster."*

Solusi praktis untuk kamu yang butuh monitoring transaksi QR Merchant BCA secara otomatis — tanpa ribet, tanpa drama.
