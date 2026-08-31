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
