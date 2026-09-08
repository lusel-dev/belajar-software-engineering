# belajar-software-engineering
Catatan belajar, praktikum, dan proyek Software Engineering

#Learning Journey - Software Engineering

Hola! Repositori ini berisi catatan belajar, latihan praktikum, dan proyek yang saya kerjakan selama belajar untuk menjadi Software Engineering.

---

## 🌐 Modul 1: Internet Introduction & Networking Basics

Pengujian perintah dasar jaringan menggunakan Command Prompt / Terminal.

### 📌 1. Pengujian Konektivitas (`ping`)
Perintah `ping` digunakan untuk mengecek respons balik dan latensi koneksi ke server tujuan.

* **Google (`www.google.com`)**
  * **IP Address:** `216.239.38.120`
  * **Status:** Connected (0% Loss)
  * **Average Latency:** 50ms

* **Example (`example.com`)**
  * **IP Address:** `104.20.23.154`
  * **Status:** Connected (0% Loss)
  * **Average Latency:** 23ms

---

### 🔍 2. Pencarian Informasi DNS (`nslookup`)
Perintah `nslookup` digunakan untuk memetakan nama domain `www.example.com` ke IP Address aslinya.

* **DNS Server:** `rns-sht-01.hypernet.co.id` (`114.129.22.33`)
* **IPv4 Address:** `104.20.23.154`, `172.66.147.243`
* **IPv6 Address:** `2606:4700:10::ac42:93f3`, `2606:4700:10::6814:179a`

---

### 📝 Kesimpulan
Kedua domain memberikan respon sukses (*Reply*) tanpa kehilangan paket data. Perintah `nslookup` membuktikan bahwa sebuah nama domain dipetakan ke alamat IP publik di internet.

---

## ⚙️ The next Step : Backend Development & Laravel Basics

Catatan dan pemahaman konsep dasar pengembangan sisi server (*Backend*) dan pengenalan Framework Laravel.

### 📌 1. Konsep Dasar CRUD
CRUD adalah 4 operasi utama dalam pengelolaan data di basis data:
* **Create:** Menambahkan data baru (contoh: *tambah produk*).
* **Read:** Menampilkan data (contoh: *melihat daftar produk*).
* **Update:** Memperbarui/mengedit data yang ada.
* **Delete:** Menghapus data dari sistem.

### 🧩 2. Arsitektur MVC pada Laravel
Laravel menggunakan pola **MVC (Model-View-Controller)** untuk memisahkan tanggung jawab kode:
saya membayangkannya seperti di restoran kurang lebihnya

* **Model (`Product.php`):** Asisten Koki / Kasir (Tugasnya khusus berhubungan langsung dengan Gudang Bahan / Database)
* **View (`.blade.php`):** Buku Menu & Meja Makan (Ini adalah apa yang dilihat oleh pelanggan (user). Tempat user memesan makanan (isi form) atau melihat makanan yang dihidangkan (daftar produk))
* **Controller (`ProductController.php`):** Koki Dapur (Otak Utamanya) (Koki yang memproses pesanan. Koki mengecek: "Apakah pesanan nama dan detailnya sudah diisi lengkap?" (validasi). Kalau lengkap, koki menyuruh asistennya menyimpan bahan makanan)
* **Route (`web.php`):** Pelayan Restoran (Tugasnya hanya mengantar pesanan. Kalau user mengeklik tombol "Tambah Produk", pelayan (route) membawa pesanan itu ke dapur)
---
