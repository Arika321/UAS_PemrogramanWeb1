
# 🧹 CleanTrash - Sistem Informasi Pengelolaan Sampah Berbasis Web

CleanTrash adalah aplikasi web yang dikembangkan sebagai project Ujian Akhir Semester mata kuliah **Pemrograman Web 1**.  
Aplikasi ini digunakan untuk membantu proses pengelolaan data sampah, pengguna, serta laporan secara terintegrasi antara backend dan frontend.

---

## 📚 Informasi Project

- Mata Kuliah : Pemrograman Web 1  
- Dosen Pengampu : Nova Agustina, S.T., M.Kom  
- Jenis Project : Ujian Akhir Semester  
- Metode Pengerjaan : Individu  
- Studi Kasus : Pengelolaan Sampah (CleanTrash)

---
## 👤 Identitas Mahasiswa

Nama          : Arika Azhar 
NPM           : 23552011408
Kelas         : TIF 23 RP CNS B 
Program Studi : Teknik Informatika

---
## 🎯 Tujuan Aplikasi

- Mengelola data sampah secara digital  
- Mempermudah admin dalam memantau data  
- Menyediakan laporan yang dapat diekspor  
- Menerapkan konsep CRUD, autentikasi, dan session  
- Mengintegrasikan frontend dan backend  

---

## 🚀 Fitur Utama

- Autentikasi Login & Register  
- Dashboard sebagai pusat informasi  
- Manajemen data (CRUD)  
- Manajemen pengguna  
- Menu Profil (edit data & foto profil)  
- Export laporan ke PDF  
- Export laporan ke Excel  
- Session & keamanan halaman  
- Footer otomatis pada seluruh halaman  
- Hosting online  

---

## 🧩 Teknologi yang Digunakan

| Komponen | Teknologi |
|--------|----------|
| Backend | PHP Native |
| Frontend | HTML, CSS, JavaScript |
| Framework CSS | Bootstrap |
| Database | MySQL |
| Server | Apache |
| Laporan | DomPDF & PhpSpreadsheet |

---

## 🗂 Struktur Folder Utama

```
UAS-PemrogramanWeb1-CleanTrash/
│
├── index.php
├── test.php
│
├── asset/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── script.js
│   │
│   └── img/
│
├── database/
│   ├── db_cleantrash.sql
│   └── db_cleantrans.sql
│
├── datatables/
│   ├── datatables.min.css
│   └── datatables.min.js
│
├── page/
│   ├── admin.php
│   ├── admin_data_sampah.php
│   ├── admin_data_setor.php
│   ├── admin_grafik.php
│   ├── cek_login.php
│   ├── config.php
│   ├── dashboard.php
│   ├── dashboard_nasabah.php
│   ├── data.php
│   ├── export_excel.php
│   ├── export_excel_transaksi.php
│   ├── export_pdf.php
│   ├── export_pdf_transaksi.php
│   ├── jenis_sampah.php
│   ├── jenis_tambah.php
│   ├── jenis_edit.php
│   ├── jenis_hapus.php
│   ├── laporan.php
│   ├── laporan_cetak.php
│   ├── login.php
│   ├── logout.php
│   ├── register.php
│   ├── nasabah.php
│   ├── nasabah_tambah.php
│   ├── nasabah_edit.php
│   ├── nasabah_hapus.php
│   ├── transaksi.php
│   ├── transaksi_tambah.php
│   ├── transaksi_edit.php
│   ├── transaksi_hapus.php
│   ├── profil.php
│   ├── profil_update.php
│   │
│   ├── components/
│   │   ├── header.php
│   │   ├── footer.php
│   │   ├── navbar.php
│   │   └── sidebar.php
│   │
│   └── js/
│       ├── jquery.min.js
│       ├── bootstrap.min.js
│       ├── custom.js
│       ├── scripts.js
│       ├── select2.min.js
│       └── select2.min.css
│
├── system/
│   ├── koneksi.php
│   ├── session.php
│   ├── functions.php
│   │
│   └── fpdf/
│       ├── fpdf.php
│       └── font/
│
├── uploads/
│   └── .htaccess
│
└── .git/

```

---

## ⚙️ Cara Instalasi

### 1. Clone Repository

```bash
https://github.com/Arika321/UAS_PemrogramanWeb1.git
```

### 2. Pindahkan ke Folder XAMPP

```
C:\xampp\htdocs\
```

### 3. Buat Database

Buka phpMyAdmin lalu jalankan:

```sql
CREATE DATABASE cleantrash;
```

Import file SQL yang tersedia di folder project (jika ada).

---

### 4. Konfigurasi Koneksi Database

Edit file:

```
config/koneksi.php
```

```php
$host = "localhost";
$user = "root";
$pass = "";
$db   = "cleantrash";
```

---

### 5. Jalankan Project

Buka browser:

```
http://localhost/UAS_Pemrograman-Web1
```

---

## 🔐 Akun Default (Jika Ada)

```
Email    : admin@gmail.com
Password : admin123
```

---

## 🧪 Cara Penggunaan

1. Register akun baru  
2. Login ke sistem  
3. Masuk ke Dashboard  
4. Kelola data menggunakan menu CRUD  
5. Lihat laporan  
6. Export PDF atau Excel  
7. Edit profil jika diperlukan  
8. Logout  

---

## 📤 Export Laporan

- PDF  
- Excel  

File laporan dapat langsung diunduh dari menu laporan.

---

### 📦 GitHub Repository
https://github.com/Arika321/UAS_PemrogramanWeb1.git

## 🖼 Screenshot Aplikasi

### Halaman Login
<img width="1360" height="650" alt="Image" src="https://github.com/user-attachments/assets/cffca53f-7661-473e-9491-c45fe6dd156b" />

### halaman Register
<img width="1366" height="648" alt="image" src="https://github.com/user-attachments/assets/35dc5291-aeec-43e5-88bf-e550cc8ab657" />


#### halaman dashboard Admin
<img width="1365" height="678" alt="Image" src="https://github.com/user-attachments/assets/af67d172-eec4-46ad-b125-aa5648dcde37" />

### halaman dashboard Nasabah
<img width="1366" height="681" alt="Image" src="https://github.com/user-attachments/assets/ae0eac13-29d3-4827-96d4-77d3de25e6d4" />


### halaman data Nasabah
<img width="1366" height="675" alt="Image" src="https://github.com/user-attachments/assets/cd3a9126-dd78-4bf4-967b-213992e7b607" />

### halaman Transaksi
<img width="1366" height="677" alt="Image" src="https://github.com/user-attachments/assets/55b56907-150e-459c-bc35-7871d24baf73" />

### halaman Laporan
<img width="1366" height="668" alt="Image" src="https://github.com/user-attachments/assets/6074605d-ee98-4f3b-a04c-6a71e211a7b3" />

#### halaman Laporan PDF
 <img width="548" height="617" alt="Image" src="https://github.com/user-attachments/assets/b7219f1a-8277-42a4-b5d0-d88ee161bd6f" />

### halaman Laporan Excel
<img width="674" height="299" alt="Image" src="https://github.com/user-attachments/assets/5a2e3475-7a7a-4e9b-9651-c89a8eb0dd69" />



## 🎥 Video Demo Project

(Upload ke Google Drive)

```
https://drive.google.com/file/d/1ENRLX54BAXJ7PVwWa84_Tn63Ry-vhL_5/view?usp=drive_link
```


---

## 📝 Catatan

Project ini dibuat untuk memenuhi tugas Ujian Akhir Semester mata kuliah Pemrograman Web 1.  
Segala bentuk pengembangan lanjutan dapat dilakukan sesuai kebutuhan.

---

## 📜 Lisensi

MIT License  
© 2026 CleanTrash

