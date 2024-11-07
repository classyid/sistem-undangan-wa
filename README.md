# 📨 Sistem Manajemen Undangan WhatsApp

Sistem manajemen pengiriman undangan melalui WhatsApp dengan interface yang modern dan fitur lengkap. Dibangun menggunakan PHP, MySQL, dan TailwindCSS.

## ✨ Fitur Utama

### 🔥 Manajemen Undangan
- Form pengiriman yang user-friendly
- Multiple penerima dalam satu kali kirim
- Preview pesan sebelum pengiriman
- Status tracking pengiriman
- Riwayat pengiriman lengkap

### 📝 Manajemen Template
- CRUD template pesan
- Variabel dinamis ({nama}, {tanggal}, etc.)
- Preview template
- Status aktif/nonaktif

### 👥 Manajemen Penerima
- Database penerima terintegrasi
- Import/export data penerima
- Grouping penerima
- Status aktif/nonaktif

### 📊 Dashboard Admin
- Interface modern dengan TailwindCSS
- Fully responsive design
- Dark/light mode
- Statistik pengiriman

### 🔒 Keamanan
- Sistem login multi-user
- Role-based access control
- Activity logging
- Error tracking

### ⚙️ Konfigurasi
- Konfigurasi WhatsApp API
- Pengaturan template default
- Manajemen user
- Kustomisasi tampilan

## 🛠️ Teknologi

- PHP 7.4+
- MySQL 5.7+
- TailwindCSS 2.0
- JavaScript/jQuery
- WhatsApp API

## 📦 Kebutuhan Server

- PHP >= 7.4
- MySQL >= 5.7
- mod_rewrite enabled
- cURL enabled
- WhatsApp API Key

## 🚀 Instalasi

1. Clone repository
```bash
git clone https://github.com/classyid/sistem-undangan-wa.git
```

2. Import database
```bash
mysql -u username -p database_name < database.sql
```

3. Konfigurasi
```bash
cp includes/config.example.php includes/config.php
# Edit config.php sesuai kebutuhan
```

4. Setup permission
```bash
chmod 755 assets/images
chmod 755 cache
chmod 644 includes/*.php
```

5. Setup WhatsApp API
- Dapatkan API Key dari provider
- Update konfigurasi di dashboard admin

## 🎯 Penggunaan

1. Login ke sistem
2. Setup konfigurasi dasar
3. Tambahkan template pesan
4. Import data penerima
5. Mulai kirim undangan

## 🔑 Environment Variables

```env
DB_HOST=localhost
DB_USER=root
DB_PASS=password
DB_NAME=wa_undangan

WA_API_KEY=your_api_key
WA_SENDER=628xxxxxxxxx
```

## 📝 Lisensi

MIT License - Silakan gunakan dan modifikasi sesuai kebutuhan.

## 👨‍💻 Kontributor

- [Andri Wiratmono](https://github.com/classyid)

## 🤝 Kontribusi

Kontribusi selalu welcome! Silakan buat Pull Request atau Issue.

## 📞 Support

- WhatsApp: [+6281241314446](https://wa.me/6281241314446)
- Email: [kontak@classy.id](mailto:kontak@classy.id)
