# **Kesehatan Mental – CI/CD Deployment with Docker & GitHub Actions**

Sebuah project landing page sederhana bertema **Kesehatan Mental**, yang di-deploy secara otomatis menggunakan **CI/CD**, **Docker**, dan **GitHub Actions** ke **VPS** dengan alamat:

🔗 **Live Website:** http://103.217.144.85:8080/

---

## 🧑‍🤝‍🧑 **Anggota Kelompok CS01 - B**

| No | Nama                           | NIM        |
|----|--------------------------------|------------|
| 1  | Anang Febryan Sutarja          | 0110222035 |
| 2  | Faiz Abdullah Hanif Firmansyah | 0110222281 |
| 3  | Ahmad Riza Muzakki             | 0110224101 |
| 4  | Muhammad Qohir Nur             | 0110224044 |
| 5  | Wahyu Rifda Muthia             | 0110222161 |
| 6  | Haura Tsabitah                 | 0110222242 |

---

# 📌 **Deskripsi Project**

Project ini merupakan landing page sederhana yang membahas tentang **kesadaran kesehatan mental**, dibuat menggunakan **HTML + CSS + JavaScript**, kemudian dikemas dalam **Docker container** dan dijalankan di server VPS.

Project ini juga menerapkan **Continuous Integration & Continuous Deployment (CI/CD)** sehingga setiap perubahan kode yang di-push ke GitHub akan otomatis di-deploy ke server VPS.

---

# 🚀 **Apa itu CI/CD?**

**CI/CD (Continuous Integration & Continuous Deployment)** adalah metode otomatisasi dalam pengembangan software.

## **CI — Continuous Integration**
Pada tahap CI:
- kode diperbarui secara berkala  
- GitHub Actions melakukan build otomatis  
- meminimalkan error karena integrasi dilakukan lebih sering  

## **CD — Continuous Deployment**
Setiap ada commit / push:
- server otomatis menarik versi terbaru  
- container Docker yang lama dihentikan dan diganti  
- aplikasi langsung diperbarui tanpa downtime  

Dengan CI/CD, deployment menjadi:
✔ otomatis  
✔ cepat  
✔ konsisten  
✔ minim error  

---

# 🧰 **Teknologi yang Digunakan**

| Teknologi | Fungsi |
|----------|--------|
| **Docker** | Mengemas aplikasi ke dalam container |
| **GitHub Actions** | Mengotomatisasi CI/CD pipeline |
| **VPS (Ubuntu)** | Server untuk menjalankan aplikasi |
| **Nginx (dalam container)** | Web server untuk landing page |
| **HTML, CSS, JS** | Pembuatan tampilan landing page |

---

# 📘 **Kesimpulan**

Project ini menunjukkan bagaimana cara:
- membuat landing page sederhana  
- mengemas aplikasi menggunakan Docker  
- menjalankan aplikasi di VPS  
- menerapkan CI/CD otomatis menggunakan GitHub Actions  

Dengan pipeline ini, setiap perubahan kode akan langsung muncul di web server tanpa perlu deploy manual.
