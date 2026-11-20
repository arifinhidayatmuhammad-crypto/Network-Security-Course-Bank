# 🛡️ UTS Network Security — Arifin Hidayat

**Repository Ujian Tengah Semester (UTS) Mata Kuliah Network Security**

Repository ini berisi dokumentasi, konfigurasi, implementasi, dan hasil praktikum Ujian Tengah Semester mata kuliah **Network Security**. Proyek ini dibuat sebagai bentuk penerapan materi keamanan jaringan menggunakan lingkungan Linux, Docker, dan berbagai tools keamanan jaringan.

---

## 👨‍🎓 Identitas Mahasiswa

| Keterangan | Informasi |
|---|---|
| Nama | Arifin Hidayat |
| NIM | 24552011362 |
| Mata Kuliah | Network Security |
| Program Studi | Teknik Informatika |
| Universitas | Universitas Teknologi Bandung |
| Jenis Tugas | Ujian Tengah Semester (UTS) |

---

## 🎯 Tujuan Praktikum

Praktikum ini bertujuan untuk memahami dan menerapkan konsep dasar keamanan jaringan melalui simulasi dan implementasi secara langsung.

Adapun tujuan pengerjaan:

1. Memahami konsep dasar Network Security.
2. Mengenal dan menggunakan tools keamanan jaringan.
3. Memahami konfigurasi jaringan menggunakan Docker.
4. Mempelajari konsep keamanan komunikasi dan enkripsi.
5. Melakukan simulasi serta pengujian keamanan jaringan.
6. Mendokumentasikan setiap tahapan praktikum secara sistematis.

---

## 🛠️ Teknologi dan Tools

| Tools | Kegunaan |
|---|---|
| Linux | Lingkungan praktikum |
| Docker | Virtualisasi lingkungan laboratorium |
| Docker Compose | Pengelolaan container |
| Kali Linux | Tools pengujian keamanan |
| OpenSSL | Enkripsi, dekripsi, dan hashing |
| dnsmasq | Konfigurasi DNS dan DHCP |
| Terminal | Eksekusi perintah Linux |
| Visual Studio Code | Pengelolaan file dan konfigurasi |

---

## 📂 Struktur Repository

```text
UTS-Network-Security/
│
├── README.md
│
├── 01-sumber-lab/
│   ├── README.md
│   │
│   ├── images/
│   │   ├── uts-openssl/
│   │   ├── uts-kali-tools/
│   │   └── uts-dnsmasq/
│   │
│   └── b/
│       ├── b1-compose/
│       ├── b2-...
│       └── ...
│
└── ...
```

---

## 🧪 Implementasi Praktikum

### 1. OpenSSL

Mempelajari penggunaan OpenSSL untuk kebutuhan keamanan informasi, termasuk:

- Enkripsi dan dekripsi data.
- Pembuatan hash.
- Penggunaan algoritma kriptografi.
- Pengujian integritas data.

**Dokumentasi:** `01-sumber-lab/images/uts-openssl/`

### 2. Kali Linux Tools

Mempelajari penggunaan tools pada Kali Linux untuk membantu proses analisis dan pengujian keamanan jaringan.

**Dokumentasi:** `01-sumber-lab/images/uts-kali-tools/`

### 3. DNS menggunakan dnsmasq

Mempelajari konfigurasi dan implementasi layanan DNS menggunakan dnsmasq dalam lingkungan laboratorium.

**Dokumentasi:** `01-sumber-lab/images/uts-dnsmasq/`

### 4. Docker Compose

Membangun dan mengelola lingkungan praktikum menggunakan Docker Compose agar setiap layanan dapat berjalan dalam container yang terpisah.

---

## 📸 Dokumentasi Praktikum

Dokumentasi screenshot hasil pengerjaan akan ditambahkan pada folder masing-masing praktikum.

Folder dokumentasi:

```text
01-sumber-lab/
└── images/
    ├── uts-openssl/
    ├── uts-kali-tools/
    └── uts-dnsmasq/
```

---

## ⚙️ Persyaratan Sistem

Sebelum menjalankan praktikum, pastikan perangkat sudah memiliki:

- Docker atau Docker Desktop.
- Docker Compose.
- Linux / Kali Linux / Ubuntu.
- Visual Studio Code (opsional).
- Koneksi internet untuk mengunduh image dan dependencies.

---

## 🚀 Cara Menjalankan Praktikum

1. Clone repository:

```bash
git clone https://github.com/USERNAME/UTS-Network-Security.git
```

2. Masuk ke direktori repository:

```bash
cd UTS-Network-Security
```

3. Masuk ke folder praktikum yang ingin dijalankan.

4. Jalankan konfigurasi Docker Compose sesuai petunjuk pada masing-masing folder:

```bash
docker compose up -d --build
```

5. Periksa status container:

```bash
docker compose ps
```

6. Setelah selesai, hentikan container:

```bash
docker compose down
```

---

## 📚 Referensi

- [Docker Documentation](https://docs.docker.com/)
- [Kali Linux Documentation](https://www.kali.org/docs/)
- [OpenSSL Documentation](https://docs.openssl.org/)
- [dnsmasq Documentation](https://thekelleys.org.uk/dnsmasq/doc.html)
- [Linux Documentation](https://www.kernel.org/doc/)

---

## ⚠️ Disclaimer

Seluruh praktikum dalam repository ini dibuat untuk tujuan pendidikan dan pembelajaran keamanan jaringan. Pengujian keamanan hanya dilakukan pada lingkungan laboratorium yang telah disiapkan dan sistem yang memiliki izin pengujian.

---

**© 2026 Aripin Hidayat — Network Security UTS**  
Universitas Teknologi Bandung
