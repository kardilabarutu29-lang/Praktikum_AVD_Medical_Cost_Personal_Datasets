## 📊 **Flowchart**
### 1. Halaman Utama
<img width="2408" height="3768" alt="image" src="https://github.com/user-attachments/assets/bcf2782a-4d9c-4413-996e-1e45419ef0d2" />

### 2. Login Sistem
<img width="6988" height="3888" alt="image" src="https://github.com/user-attachments/assets/a51fac13-e3f7-4599-ab5a-6b87c1f8cd7b" />


### 3. Dashboard Operator
<img width="14528" height="10088" alt="image" src="https://github.com/user-attachments/assets/e3cb3eeb-8c75-47ed-888c-9b2f9aa063b5" />


### 4. Menu 1 Pendaftaran Kapal Baru
<img width="11800" height="2128" alt="image" src="https://github.com/user-attachments/assets/7c5496df-23e6-47d8-80c1-1b71a994a727" />


### 5. Menu 2 Lihat Daftar Kapal
<img width="768" height="181" alt="image" src="https://github.com/user-attachments/assets/d5849749-13bf-4865-be40-22e83623db69" />


### 6. Menu 3 Penambatan Kapal (Docking)
<img width="13608" height="2184" alt="image" src="https://github.com/user-attachments/assets/9ff7f7b1-3805-40e2-b0eb-c66e4bfa5e5a" />


### 7. Menu 4 Bongkar Muat Kargo
<img width="11328" height="1568" alt="image" src="https://github.com/user-attachments/assets/ba7c58b4-1fad-42c0-851d-d0f7e9ed1f5e" />

### 8. Menu 5 Kelola Data Kargo
<img width="10488" height="2168" alt="image" src="https://github.com/user-attachments/assets/edf8be65-749d-4c97-8ae1-f174ed72fec3" />

### 9. Menu 6 Cek Profil Operator 
<img width="735" height="220" alt="image" src="https://github.com/user-attachments/assets/141b5e2d-f42b-46ba-9574-a4fed856ea01" />


### 10. Logout
<img width="765" height="192" alt="image" src="https://github.com/user-attachments/assets/7b42a8f3-de62-4610-82e8-08f634fc6ebe" />



### 11. Dashboard Admin
<img width="10488" height="2168" alt="image" src="https://github.com/user-attachments/assets/528aae2d-bd25-42ab-a9cf-dd2691e22518" />


### 12. Menu 1 Kelola Dermaga
<img width="13168" height="6176" alt="image" src="https://github.com/user-attachments/assets/d43c6a96-0299-4df5-8e3e-546d624b63ad" />



### 13. Menu 2 Kelola Slot Gudang
<img width="12368" height="6688" alt="image" src="https://github.com/user-attachments/assets/0b8d58d2-2dff-43b7-b128-fd108cf4749c" />



### 14. Menu 3 Kelola Tarif Retribusi
<img width="9128" height="2072" alt="image" src="https://github.com/user-attachments/assets/551db6e4-a304-4dc4-afac-9678b70d2595" />


### 15. Menu 4 Billing & Pembayaran 
<img width="10808" height="1768" alt="image" src="https://github.com/user-attachments/assets/d57a2709-9819-44df-a957-567e2ceafcfd" />


### 16. Menu 5 Kelola Akun Operator
<img width="16384" height="3057" alt="image" src="https://github.com/user-attachments/assets/1d206f7d-5884-46ba-80cc-7dae390525bc" />


### 17. Menu 6 Laporan
<img width="9608" height="1808" alt="image" src="https://github.com/user-attachments/assets/b0f2b63c-369b-4ed3-9f23-a1bbbe704d91" />


### 18. Menu 7 Cek Profil Admin 
<img width="768" height="220" alt="image" src="https://github.com/user-attachments/assets/b1fd12ef-23ef-4400-8427-659a47d10239" />


### 19. Logout
<img width="722" height="197" alt="image" src="https://github.com/user-attachments/assets/c4c78d8c-cab5-47e3-8da7-ba67357eb63f" />


📎 [Klik di sini untuk melihat Flowchart Lengkap](https://app.diagrams.net/?src=about#G1l_0vRv375RYu1bvGWVfsu-FzTx-2HyA5#%7B%22pageId%22%3A%22YSO67Ypj2ylAbOuhdHeY%22%7D)

---

## 🗂️ **ERD**
Entitas utama sistem:
- **Pengguna**
- **Admin**
- **Operator**
- **Kapal**
- **Dermaga**
- **Kargo**
- **Slot Gudang**
- **Retribusi**
- **Laporan**

Relasi utama:
- `Pengguna` ↔ `Admin` (1:1)
- `Pengguna` ↔ `Operator` (1:1)
- `Admin` ↔ `Laporan` (1:N)
- `Operator` ↔ `Slot_Gudang` (1:N)
- `Pengguna` ↔ `Retribusi` (1:N)
- `Slot_Gudang` ↔ `Kargo` (1:N)
- `Kargo` ↔ `Kapal` (N:M)
- `Kapal` ↔ `Jadwal_Sandar` (1:N)
- `Dermaga` ↔ `Jadwal_Sandar` (1:N)
- `Kapal` ↔ `Retribusi` (1:1)
  


---

## 🧩 **Use Case Diagram**
>"Berikut merupakan ilustrasi hubungan antara aktor (Admin dan Operator) dengan fungsionalitas utama dalam sistem informasi manajemen operasional pelabuhan ArgoPort."

<img width="5572" height="11004" alt="image" src="https://github.com/user-attachments/assets/5cf4f856-a355-47c8-a407-ded992668b39" />




## 📅 **Informasi Tambahan**
🧩 **Kebutuhan Sistem & Tech Stack**

Sebelum menjalankan program **Sistem Informasi Manajemen Operasional Pelabuhan ArgoPort**, kami menggunakan beberapa perangkat dan perangkat lunak pendukung berikut:

- **🧱 Java & Apache NetBeans**  
  Menggunakan bahasa pemrograman Java yang dikembangkan di lingkungan Apache NetBeans untuk membangun aplikasi berbasis desktop yang interaktif dan terstruktur.

- **💾 MySQL & Laragon / SQL**  
  Menggunakan database MySQL (yang dikelola melalui lingkungan lokal Laragon) sebagai Sistem Manajemen Basis Data Relasional (RDBMS) untuk menyimpan dan mengelola data operasional pelabuhan secara aman.

- **🔗 JDBC (Java Database Connectivity)**  
  Pustaka penghubung yang memungkinkan aplikasi berbasis Java dapat berkomunikasi dan melakukan pertukaran data secara langsung dengan database `argoport_db`.

- **📐 Data Modeler & Draw.io**  
  Digunakan untuk perancangan struktur basis data, pemodelan entitas (*ERD*), serta pembuatan diagram alur kerja sistem ArgoPort.

- **🐙 GitHub**  
  Digunakan sebagai layanan *version control* untuk mengelola kode program, kolaborasi tim, dan dokumentasi repositori proyek.

- **🎨 Canva**  
  Digunakan untuk perancangan desain antarmuka, presentasi, serta aset visual pendukung laporan proyek.








  


---

[⬆️ Kembali ke Awal](#-selamat-datang-di-panduan)
