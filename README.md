<div align="center">

# 🌸💕 **PastParadise** 💕🌸  
### *Handmade Craft Marketplace — Cute, Complete, Creative*  
Tempat belanja **kerajinan tangan lengkap**, aesthetic, dan berkualitas 💗

<img src="https://img.shields.io/badge/Craft%20Store-Complete%20Collections-ffb3d9" />
<img src="https://img.shields.io/badge/Built%20for-UKK%20RPL%202025-ff99c8" />
<img src="https://img.shields.io/badge/Theme-Pastel%20Pink-ffcce6" />

</div>

---

## 🌷 **✨ Overview**
<img width="1920" height="6185" alt="screencapture-localhost-UKK-WEBSITE-customer-2025-11-28-09_08_45" src="https://github.com/user-attachments/assets/50798b73-8b38-490a-a495-20a97022a872" />

<img width="1920" height="912" alt="Screenshot 2025-11-28 091045" src="https://github.com/user-attachments/assets/a7b7c5ad-9e1e-4eb3-9657-a9205d9b7fea" />
<img width="1920" height="912" alt="Screenshot 2025-11-28 091003" src="https://github.com/user-attachments/assets/0ef4083f-b71e-4298-bffb-21c1271d17ae" />
<img width="1920" height="911" alt="Screenshot 2025-11-28 091119" src="https://github.com/user-attachments/assets/ebb33e93-571e-4838-b09b-aee1632dde41" />


**PastParadise** adalah platform e-commerce bertema pink aesthetic yang berfokus pada **penjualan produk kerajinan tangan (handmade crafts)**.  
Website ini dirancang untuk menjadi **tempat belanja kerajinan paling lengkap**, mulai dari:

💗 Dekorasi rumah handmade  
💗 Aksesoris rajut  
💗 Souvenir  
💗 Kerajinan berbahan alami  
💗 Produk kreatif lokal lainnya  

Semua ditampilkan dengan tampilan yang lembut, bersih, dan modern ✨

---

## 💗 **✨ Why PastParadise is Special**

### 🌸 **Craft Marketplace yang Komplit**
PastParadise menyediakan berbagai kategori kerajinan, sehingga pengguna dapat menemukan semua kebutuhan handmade dalam satu tempat.

### 🌸 **Aesthetic & Friendly UI**
Tampilan pastel pink yang nyaman dan cocok untuk brand kerajinan yang lembut dan elegan.

### 🌸 **Dibuat untuk UMKM & Pengguna**
Pengunjung dapat melihat detail produk, menambah keranjang, checkout, hingga melakukan pembayaran via QR dengan sangat mudah.

---

## 💕 **✨ Features**

### 📦 **Product Showcase**
- Menampilkan berbagai produk kerajinan complete & variatif  
- Gambar produk tampil otomatis  
- Harga, nama, dan SKU rapi & jelas  

### 🛍️ **Craft Shopping Experience**
- Add to cart  
- Update jumlah barang  
- Sistem keranjang lengkap  
- Hitungan subtotal + total otomatis  

### 💸 **Payment with QR Code**
- Pembayaran mudah  
- QR Code ditampilkan di halaman payment (assets/qr.png)

### 🔐 **User System**
- Login dengan password **hashed**  
- Session aman  
- Validasi rapi  

---

## 🌸 **✨ Project Description**

PastParadise diciptakan untuk menjadi **solusi digital bagi penjualan produk kerajinan**, memudahkan customer menemukan barang handmade yang cantik dan unik.

Setiap fiturnya dirancang agar:
- Mudah digunakan  
- Responsif  
- Cepat  
- Soft aesthetic sesuai tema craft  

---

## 🎀 **✨ Tech Stack**

| Teknologi | Peran |
|----------|-------|
| 💗 PHP Native | Backend logic |
| 💗 MySQL | Database kerajinan |
| 💗 Laragon | Local dev environment |
| 💗 HTML/CSS/JS | UI pastel pink |
| 💗 Ionicons | Icon UI |

---


---

## 💗 **✨ Partial Database Overview**

### 🧚 customer
| Kolom | Tipe |
|-------|------|
| id_customer | varchar |
| id_role | int |
| nama_customer | varchar |
| email_customer | varchar |
| no_hp_customer | varchar |
| alamat_default_customer | text |
| password_customer | varchar (hash) |
| image_customer | varchar |
| status_akun | enum |

### 🧚 product
| Kolom | Tipe |
|--------|------|
| id_product_sku | varchar |
| nama_product | varchar |
| harga_product | int |
| image_product | varchar |

### 🧚 cart
| Kolom | Tipe |
|--------|------|
| id_cart | int |
| id_customer / guest_session | varchar |
| id_product_sku | varchar |
| quantity | int |

---

## 🎀 **✨ Installation**

### 1️⃣ Clone repository
git clone https://github.com/BirgitaPaskalina/Web_PASTPARADISE.git
### 2️⃣ Pindahkan ke folder Laragon
C:/laragon/www/PastParadise
### 3️⃣ Import database
Buka phpMyAdmin
Buat DB: pastparadise
Import file .sql
### 4️⃣ Atur database.php
$conn = new mysqli("localhost", "root", "", "pastparadise");
### 5️⃣ Jalankan di browser
http://localhost/PastParadise/login.php

---

## 💞 **✨ Future Expansion Ideas**
- Halaman kategori kerajinan (Rajut, Natural Textile, Recycled, Souvenir, dll)  
- Admin panel untuk upload produk baru  
- Sistem filter produk (warna, bahan, jenis kerajinan)  
- Wishlist  
- Loyalty point  

---

## 💗 **Made with love — PastParadise**  
*Where creativity meets elegance* ✨
