# Enso Auto Bot - SOUIY

Bot otomatis untuk Enso yang membantu dalam melakukan berbagai tugas seperti chat, membuat DeFiDex, menyelesaikan campaign, dan menyelesaikan protocols.

## Fitur

- Otomatisasi interaksi dengan Enso
- Mendukung multi-akun
- Mendukung proxy
- Penjadwalan otomatis (setiap hari pukul 07:00 WIB)
- Statistik lengkap
- Dan banyak lagi!

## Persyaratan

- Node.js (versi 18 atau lebih baru)
- NPM atau Yarn
- Akun Enso dengan private key dan Zealy User ID

## Instalasi

1. Clone repository ini:

```bash
git clone https://github.com/Souiy/EnsoAutoBot-SOUIY.git
cd EnsoAutoBot-SOUIY
```

2. Install dependencies:

```bash
npm install
```

Atau jika menggunakan Yarn:

```bash
yarn install
```

3. Buat file konfigurasi:
   - Buat file `accounts.txt` yang berisi private key dan Zealy User ID (satu akun per baris, format: `<privateKey>,<zealyUserId>`)
   - Buat file `pesan.txt` yang berisi daftar pesan yang akan dikirim (satu pesan per baris)
   - (Opsional) Buat file `proxy.txt` yang berisi daftar proxy (satu proxy per baris, format: `http://user:pass@host:port`)

## Penggunaan

Jalankan bot dengan perintah:

```bash
node index.js
```

Opsi:
- `--no-type`: Menonaktifkan efek mengetik untuk output yang lebih cepat

## Struktur File

```
EnsoAutoBot-SOUIY/
├── index.js              # File utama bot
├── accounts.txt          # File berisi akun-akun (private key dan Zealy User ID)
├── pesan.txt             # File berisi daftar pesan
├── proxy.txt             # File berisi daftar proxy (opsional)
├── package.json          # File konfigurasi dependencies
└── README.md             # File dokumentasi ini
```

## Kontribusi

1. Fork repository
2. Buat branch fitur (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -am 'Menambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## Donasi

Satukan Solidaritas Bantu Palestina!:
- **Link Donasi**: [https://digital.dompetdhuafa.org/donasi/jagapalestina](https://digital.dompetdhuafa.org/donasi/jagapalestina)

## Kontak

- TikTok: [@Souiy1](https://www.tiktok.com/@Souiy1)
- GitHub: [Souiy](https://github.com/Souiy)

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
