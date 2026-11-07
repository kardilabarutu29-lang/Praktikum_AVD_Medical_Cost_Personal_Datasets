## 📊 **Flowchart**
### 1. Halaman Utama
<img width="2408" height="3768" alt="image" src="https://github.com/user-attachments/assets/bcf2782a-4d9c-4413-996e-1e45419ef0d2" />

### 2. Login Sistem
<img width="6988" height="3888" alt="image" src="https://github.com/user-attachments/assets/a51fac13-e3f7-4599-ab5a-6b87c1f8cd7b" />


### 3. Dashboard Operator
<img width="14528" height="10088" alt="image" src="https://github.com/user-attachments/assets/e3cb3eeb-8c75-47ed-888c-9b2f9aa063b5" />


#### 4. Menu 1 Pendaftaran Kapal Baru
<img width="11800" height="2128" alt="image" src="https://github.com/user-attachments/assets/7c5496df-23e6-47d8-80c1-1b71a994a727" />


#### 5. Menu 2 Lihat Daftar Kapal
<img width="768" height="181" alt="image" src="https://github.com/user-attachments/assets/d5849749-13bf-4865-be40-22e83623db69" />


#### 6. Menu 3 Penambatan Kapal (Docking)
<img width="13608" height="2184" alt="image" src="https://github.com/user-attachments/assets/9ff7f7b1-3805-40e2-b0eb-c66e4bfa5e5a" />


#### 7. Menu 4 Bongkar Muat Kargo
<img width="11328" height="1568" alt="image" src="https://github.com/user-attachments/assets/ba7c58b4-1fad-42c0-851d-d0f7e9ed1f5e" />

#### 8. Menu 5 Kelola Data Kargo
<img width="10488" height="2168" alt="image" src="https://github.com/user-attachments/assets/edf8be65-749d-4c97-8ae1-f174ed72fec3" />

#### 9. Menu 6 Cek Profil Operator 
<img width="735" height="220" alt="image" src="https://github.com/user-attachments/assets/141b5e2d-f42b-46ba-9574-a4fed856ea01" />


#### 10. Logout
<img width="765" height="192" alt="image" src="https://github.com/user-attachments/assets/7b42a8f3-de62-4610-82e8-08f634fc6ebe" />



### 11. Dashboard Admin
<img width="10488" height="2168" alt="image" src="https://github.com/user-attachments/assets/528aae2d-bd25-42ab-a9cf-dd2691e22518" />


#### 12. Menu 1 Kelola Dermaga
<img width="13168" height="6176" alt="image" src="https://github.com/user-attachments/assets/d43c6a96-0299-4df5-8e3e-546d624b63ad" />



#### 13. Menu 2 Kelola Slot Gudang
<img width="12368" height="6688" alt="image" src="https://github.com/user-attachments/assets/0b8d58d2-2dff-43b7-b128-fd108cf4749c" />



#### 14. Menu 3 Kelola Tarif Retribusi
<img width="9128" height="2072" alt="image" src="https://github.com/user-attachments/assets/551db6e4-a304-4dc4-afac-9678b70d2595" />


#### 15. Menu 4 Billing & Pembayaran 
<img width="10808" height="1768" alt="image" src="https://github.com/user-attachments/assets/d57a2709-9819-44df-a957-567e2ceafcfd" />


#### 16. Menu 5 Kelola Akun Operator
<img width="16384" height="3057" alt="image" src="https://github.com/user-attachments/assets/1d206f7d-5884-46ba-80cc-7dae390525bc" />


#### 17. Menu 6 Laporan
<img width="9608" height="1808" alt="image" src="https://github.com/user-attachments/assets/b0f2b63c-369b-4ed3-9f23-a1bbbe704d91" />


#### 18. Menu 7 Cek Profil Admin 
<img width="768" height="220" alt="image" src="https://github.com/user-attachments/assets/b1fd12ef-23ef-4400-8427-659a47d10239" />


#### 19. Logout
<img width="722" height="197" alt="image" src="https://github.com/user-attachments/assets/c4c78d8c-cab5-47e3-8da7-ba67357eb63f" />


📎 [Klik di sini untuk melihat Flowchart Lengkap](https://app.diagrams.net/?src=about#G1l_0vRv375RYu1bvGWVfsu-FzTx-2HyA5#%7B%22pageId%22%3A%22YSO67Ypj2ylAbOuhdHeY%22%7D)

---

## 🗂️ **ERD**
Entitas utama sistem:
- **Admin**
- **Ketua_RT**
- **Pengaduan_Faskes**
- **Pengaduan_Masyarakat**
- **Log_Status**
- **Tips_Otomatis**

Relasi utama:
- `Users` ↔ `Admin` (1:1)  
- `Users` ↔ `Ketua_RT` (1:1)  
- `Users` ↔ `Pengaduan` (1:N)  
- `Pengaduan` ↔ `Log_Status` (1:N)  
- `Pengaduan_Masyarakat` ↔ `Tips_Otomatis` (N:M)
  

📌 **ERD LOGICAL**

<img width="491" height="772" alt="image" src="https://github.com/user-attachments/assets/563eefd2-d33a-4f38-864b-2d4c26030152" />


📌 **ERD RELATIONAL**

<img width="569" height="785" alt="image" src="https://github.com/user-attachments/assets/07dae1e0-0166-4830-a278-d5d173b74e04" />

📎 [Klik di sini untuk melihat ERD Logical dan Relasional](https://app.diagrams.net/)

---

## 🧩 **Use Case Diagram**
> Berikut merupakan ilustrasi hubungan antara aktor (Admin, Ketua RT, dan Pengguna) dengan fungsionalitas utama dalam sistem pengaduan layanan kesehatan.

<img width="1002" height="636" alt="image" src="https://github.com/user-attachments/assets/e5f203c9-59b0-4439-a096-949e50e1d6f8" />

## 📁 **Struktur Project**

<img width="452" height="812" alt="image" src="https://github.com/user-attachments/assets/50310517-14de-4d33-85bd-47991befb19b" />

<img width="319" height="924" alt="image" src="https://github.com/user-attachments/assets/c4215c3d-5664-45c7-b8c7-2ace7e0e3449" />

<img width="321" height="914" alt="image" src="https://github.com/user-attachments/assets/2fb331d9-1e22-4464-bfda-2b4836114a09" />

<img width="315" height="952" alt="image" src="https://github.com/user-attachments/assets/f0afb42b-ec14-44ba-9544-6e7dceeb8fb3" />

<img width="316" height="166" alt="image" src="https://github.com/user-attachments/assets/31f7ad32-7007-491a-a8db-931af3162701" />






## 💻 **Cara Penggunaan Program**

---

### 👤 **USER (Pengguna Aplikasi)**

#### 🔐 Login  

<p align="center">
  <img width="798" height="565" alt="Login Page" src="https://github.com/user-attachments/assets/3f6383ba-36dd-4aa0-b8f2-f989676b41da" />
</p>

Langkah pertama sebelum mengakses sistem adalah **login ke aplikasi HELYA**.  
Pengguna wajib mengisi **Username** dan **Password** yang telah terdaftar, kemudian menekan tombol **Login**.

Setelah berhasil masuk, akan muncul notifikasi konfirmasi login seperti berikut:

<p align="center">
  <img width="802" height="559" alt="Screenshot 2025-11-04 221446 1" src="https://github.com/user-attachments/assets/b103e36f-1136-4941-9128-95db7b74ad79" />
</p>

Tampilan ini menunjukkan bahwa pengguna telah berhasil melakukan autentikasi dan siap menggunakan seluruh fitur di dalam sistem.

---

#### 🏠 **Beranda Pengguna**

<p align="center">
  <img width="799" height="667" alt="Screenshot 2025-11-04 231351 1" src="https://github.com/user-attachments/assets/ee69ca2e-41b5-454d-bf37-b780847ab991" />
</p>

Setelah login, pengguna akan diarahkan ke halaman utama aplikasi **HELYA**, di mana mereka dapat:
- Membuat **pengaduan kesehatan pribadi**.  
- Membuat **pengaduan fasilitas kesehatan (puskesmas, rumah sakit, klinik)**.  
- Melihat **riwayat laporan** serta status tindak lanjut pengaduan (*Menunggu, Diproses, Selesai*).  

Tampilan sederhana dan responsif memudahkan pengguna dalam mengakses fitur utama dengan cepat dan efisien.  

---

#### 🩺 **Membuat Pengaduan**  
Pengguna dapat memilih menu **“Pengaduan Kesehatan”** atau **“Pengaduan Fasilitas”**, lalu mengisi formulir berisi:  
- Nama dan alamat pelapor.  
- Jenis keluhan atau permasalahan.  
- Keterangan tambahan atau foto pendukung (opsional).  

Setelah dikirim, laporan otomatis tersimpan di basis data dan dapat dipantau statusnya oleh pengguna dan admin.

---

#### 📊 **Riwayat Laporan**  
Pada bagian bawah halaman utama, terdapat tabel **Riwayat Pengaduan** yang menampilkan:
- Nomor laporan  
- Nama pelapor  
- Jenis pengaduan  
- Status laporan  
- Tombol *Detail* untuk melihat informasi lebih lanjut  

Fitur ini membantu pengguna memantau sejauh mana pengaduannya telah ditindaklanjuti oleh pihak berwenang.  

---

### 👨🏻‍💻 **ADMIN (Pengelola Sistem)**

Pengguna **Admin HELYA** memiliki peran penting dalam memantau, mengelola, dan memperbarui data pengaduan masyarakat serta fasilitas kesehatan.  
Melalui akun admin, proses pengawasan dan tindak lanjut laporan dapat dilakukan secara cepat, terkoordinasi, dan transparan.

---

<details>
  <summary>📊 <b>1️⃣ Dashboard</b></summary>

  <p align="center">
    <img width="783" height="529" alt="Dashboard Admin" src="https://github.com/user-attachments/assets/8d532833-8e7b-4035-bab8-e66a51964ebc" />
  </p>

  Halaman **Dashboard Admin HELYA** berfungsi sebagai pusat pemantauan seluruh aktivitas pengaduan di wilayah kerja.  
  Tampilan ini menampilkan informasi statistik seperti jumlah pengaduan masyarakat, status penanganan laporan, serta grafik perbandingan jenis pengaduan.  

  Desain dashboard menggunakan warna kontras untuk membedakan kategori status:
  - 🟢 **Selesai**
  - 🟡 **Sedang Diproses**
  - 🔴 **Belum Diperiksa**

  Melalui tampilan ini, admin dapat dengan mudah memantau, menganalisis, dan mengevaluasi perkembangan laporan secara efisien.
</details>

---

<details>
  <summary>👥 <b>2️⃣ Manajemen Akun</b></summary>

  <p align="center">
    <img width="783" height="528" alt="Manage Account" src="https://github.com/user-attachments/assets/56d2e229-eb86-418c-bed7-6e65bbd1a5d9" />
  </p>

  Halaman **Manajemen Akun** berfungsi untuk mengelola data pengguna dalam sistem HELYA, khususnya akun **Ketua RT** yang memantau dan menindaklanjuti laporan kesehatan di wilayahnya.  
  Tampilan ini menyediakan fitur pencarian berdasarkan nama, serta tombol untuk menambah, memperbarui, dan menghapus akun pengguna.  

  Setiap data ditampilkan dalam tabel berisi:
  - Nomor akun  
  - Nama pengguna  
  - Nomor RT  
  - Opsi tindakan (Edit / Hapus)  

  ---
  <p align="center">
    <img width="986" height="701" alt="Search Account" src="https://github.com/user-attachments/assets/5ed07616-38a8-45e3-8ef9-1a72b09ba6ab" />
  </p>
  Admin dapat mencari akun dengan menginput nama akun.

  ---
  <p align="center">
    <img width="994" height="697" alt="Add Account" src="https://github.com/user-attachments/assets/1d92fc7a-7286-4830-b2d1-b1cc749c4d4b" />
  </p>
  Admin dapat menambahkan akun pengguna baru.

  ---
  <p align="center">
    <img width="988" height="703" alt="Edit Account" src="https://github.com/user-attachments/assets/25f9f1ff-779e-44c7-b374-512dea5b3ff9" />
  </p>
  Admin dapat mengubah data akun pengguna.

  ---
  <p align="center">
    <img width="989" height="700" alt="Delete Account" src="https://github.com/user-attachments/assets/5da54832-ef1e-4f73-881f-c54aeaf8c6dc" />
  </p>
  Admin dapat menghapus akun pengguna yang telah dibuat.
</details>

---

<details>
  <summary>🧾 <b>3️⃣ Manajemen Pengaduan</b></summary>

  <p align="center">
    <img width="999" height="750" alt="Manage Reports" src="https://github.com/user-attachments/assets/f2ca3667-eae0-4fdb-9b36-ada631b9dfef" />
  </p>

  Halaman **Manajemen Pengaduan** memungkinkan admin melihat seluruh laporan pengaduan dari masyarakat dan fasilitas kesehatan.  
  Data ditampilkan dalam bentuk tabel dengan informasi seperti:
  - Nama Pelapor  
  - Jenis Pengaduan  
  - Status Penanganan  
  - Tanggal Laporan  
  - Opsi Aksi (Lihat / Update / Hapus)

  Fitur pencarian dan filter memudahkan admin untuk mengelompokkan laporan berdasarkan status (*Menunggu, Diproses, Selesai*).  
  Desain halaman ini membantu admin memantau perkembangan setiap pengaduan dengan cepat dan akurat.
</details>

---

<details>
  <summary>🚪 <b>4️⃣ Keluar</b></summary>

  Fitur **Keluar (Logout)** berfungsi untuk mengakhiri sesi admin dan memastikan keamanan akun.  
  Setelah logout, sistem akan mengarahkan kembali ke halaman **Login**, menjaga agar akses aplikasi tetap aman dan terbatas hanya untuk pengguna yang berwenang.
</details>



## 📅 **Informasi Tambahan**
🧩 **Kebutuhan Sistem**

Sebelum menjalankan program **Sistem Informasi Pengaduan Layanan Kesehatan**, pastinya kami menggunakan beberapa perangkat yang sudah memenuhi beberapa kebutuhan sistem berikut:

- **🧱 JDK 23**  
  Java Development Kit (JDK) berisi kompiler *javac*, pustaka standar Java, serta alat bantu lain yang diperlukan untuk menulis, menjalankan, dan menguji program berbasis Java.

- **🖥️ NetBeans IDE 22**  
  NetBeans merupakan lingkungan pengembangan terintegrasi (IDE) yang mendukung berbagai bahasa pemrograman seperti Java, PHP, dan C++.  
  Versi terbaru memiliki fitur untuk *debugging*, integrasi Git, dan pengembangan aplikasi berbasis web maupun desktop.

- **⚙️ XAMPP**  
  Diperlukan untuk menjalankan aplikasi yang membutuhkan server web, basis data, serta bahasa pemrograman *server-side*.  
  XAMPP mempermudah proses konfigurasi dan pengelolaan lingkungan pengembangan.

- **💾 MySQL**  
  Merupakan sistem manajemen basis data relasional (RDBMS) yang menggunakan bahasa SQL.  
  MySQL berfungsi untuk menyimpan, mengatur, dan mengelola data agar tetap akurat, aman, serta mudah diakses kapan pun dibutuhkan.

- **🔗 MySQL Connector (JDBC)**  
  Pustaka tambahan yang digunakan untuk menghubungkan aplikasi Java dengan basis data MySQL.  
  Dengan konektor ini, aplikasi dapat melakukan proses komunikasi dan pertukaran data dengan database secara langsung.

---

[⬆️ Kembali ke Awal](#-selamat-datang-di-panduan)
