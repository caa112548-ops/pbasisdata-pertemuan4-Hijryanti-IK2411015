
- **Nama** : Hijryanti
-  
- **NIM**  : IK2411015  



## 📌 Ringkasan Tugas
Tugas ini bertujuan untuk membuat sistem **manajemen kegiatan dan booking ruangan laboratorium** berbasis web menggunakan **PHP dan MySQL**.  
Sistem ini dirancang agar pengguna dapat melakukan pemesanan ruangan secara online dengan proses yang terstruktur.

Fitur utama dari sistem ini adalah:
- 🔐 Login pengguna (admin/user)
- 🏫 Pemesanan ruangan (booking)
- ⚠️ Validasi agar tidak terjadi bentrok jadwal
- ✅ Persetujuan (approval) oleh admin
- 📊 Pengelolaan data kegiatan dan laporan

Dengan adanya sistem ini, proses peminjaman ruangan menjadi lebih **efisien, aman, dan terorganisir**.

## 🗄️ Cara Menjelaskan Script SQL
Dalam menjelaskan file database **program.3sql.sql**, dapat dilakukan secara bertahap agar mudah dipahami:

### 1. 🧱 Database
Menjelaskan pembuatan database sebagai tempat penyimpanan seluruh data sistem.

### 2. 📋 Tabel
Menjelaskan fungsi masing-masing tabel, seperti:
- **users** → menyimpan data pengguna  
- **roles** → menyimpan peran (admin/user)  
- **rooms** → menyimpan data ruangan  
- **bookings** → menyimpan data pemesanan  
- **timeslots** → menyimpan waktu penggunaan  
- **approvals** → menyimpan status persetujuan  

### 3. 🧾 Field (Kolom)
Menjelaskan isi dari setiap tabel, misalnya:
- id → identitas unik  
- nama → nama pengguna/ruangan  
- waktu → jadwal penggunaan  
- status → kondisi booking (pending/approved/rejected)  

### 4. 🔗 Relasi
Menjelaskan hubungan antar tabel, contohnya:
- bookings terhubung ke users (siapa yang memesan)  
- bookings terhubung ke rooms (ruangan yang dipakai)  

### 5. 🔐 Constraint
Menjelaskan aturan database:
- Primary Key → penanda unik data  
- Foreign Key → penghubung antar tabel  


## 📂 Daftar File Repository
Berikut file utama dalam sistem beserta fungsinya:

- 🏠 **index.php** → halaman utama aplikasi  
- 🔐 **login.php** → proses login pengguna  
- 🚪 **logout.php** → keluar dari sistem  
- 📊 **dashboard.php** → halaman utama setelah login  
- 🏫 **rooms.php** → mengelola data ruangan  
- 📅 **bookings.php** → mengelola pemesanan ruangan  
- 👥 **users.php** → mengelola data pengguna  
- 📈 **reports.php** → menampilkan laporan  
- ⚙️ **config.php** → konfigurasi koneksi database  
- 🗄️ **program.3sql.sql** → file struktur database  

## ✨ Kesimpulan
Sistem ini membantu proses booking ruangan menjadi lebih **teratur, transparan, dan mudah dikelola**, serta mengurangi kesalahan seperti bentrok jadwal melalui validasi otomatis dan persetujuan admin.
