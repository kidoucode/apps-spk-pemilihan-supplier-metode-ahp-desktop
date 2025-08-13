# Aplikasi Sistem Pendukung Keputusan Pemilihan Supplier Terbaik Menggunakan Metode AHP Berbasis Desktop (Java Netbeans dan MySQL)

Aplikasi ini adalah sistem pendukung keputusan pemilihan supplier terbaik menggunakan metode AHP yang dibangun menggunakan Java Swing untuk antarmuka pengguna dan MySQL sebagai database untuk penyimpanan data. Aplikasi ini cocok untuk tugas akhir, studi kasus bisnis, atau pengambilan keputusan berbasis kriteria. Namun file yang di share ini hanya dalam bentuk demo, jadi jika anda menginginkan file ini bisa beli di [LYNK.ID Kidou Code] (https://lynk.id/kidoucode)

#### Teknologi :
- [MySQL](https://downloads.mysql.com/archives/get/p/25/file/mysql-installer-community-8.0.40.0.msi) : 8.0.40
- [JDK](https://www.oracle.com/id/java/technologies/javase/jdk11-archive-downloads.html) : 11

Untuk menjalankan demo ini, Anda hanya memerlukan JDK 11, karena database diunggah secara online. Namun, harap diperhatikan bahwa koneksi database mungkin mengalami keterlambatan.

#### Library atau Dependensi :
-  **FlatLaf (Java Look and Feel)**
flatlaf-3.5.2.jar** → Library utama untuk tema modern Java Swing.
flatlaf-3.5.2-sources.jar → Source code untuk referensi/debug.
flatlaf-extras-3.5.2.jar → Fitur tambahan seperti custom accent color, font, dan icon.
flatlaf-fonts-roboto-2.137.jar → Font Roboto bawaan untuk digunakan di UI.
flatlaf-intellij-themes-3.2.5.jar → Tema UI mirip IntelliJ IDEA.
jsvg-1.4.0.jar → Rendering gambar SVG di UI, biasanya dipakai untuk icon.

- **MigLayout**
miglayout-core-5.3.jar → Inti layout manager untuk mengatur posisi komponen.
miglayout-swing-5.3.jar → Integrasi MigLayout dengan komponen Swing.

- **Modal Dialog** 
modal-dialog-2.1.0.jar → Library untuk membuat dialog kustom (popup) dengan animasi dan desain modern.
modal-dialog-demo-2.1.0.jar → Contoh/demo penggunaan modal dialog.
-  **MySQL Driver**
mysql-connector-j-8.0.31.jar → Driver JDBC untuk menghubungkan aplikasi Java dengan database MySQL/MariaDB.
-  **Hashing**
jbcrypt-0.4.jar → Library untuk hashing password menggunakan algoritma BCrypt. Fungsi umum: Mengamankan password sebelum disimpan di database.
-  **PDF**
itextpdf-5.5.13.jar → Library untuk membuat dan mengedit file PDF. Fungsi umum: Generate laporan PDF dari aplikasi (misal: invoice, laporan data).
-  **Excel (Apache POI)**
commons-collections4-4.4.jar → Kumpulan struktur data koleksi tambahan untuk Apache POI.
commons-compress-1.19.jar → Library untuk kompresi/dekompresi file (ZIP, GZIP, dll) yang digunakan POI.
poi-4.1.2.jar → Apache POI core untuk membaca/menulis Excel, Word, PowerPoint.
poi-ooxml-4.1.2.jar → Modul khusus format Office baru (XLSX, DOCX, PPTX).
poi-ooxml-schemas-4.1.2.jar → Skema XML untuk format OOXML.
stax-api-1.0.1.jar → API untuk parsing XML berbasis streaming (dibutuhkan POI).
xmlbeans-3.1.0.jar → Library untuk memproses XML yang digunakan oleh POI.

#### Fitur Utama :
- **Manajemen Buku:** Menambah, mengedit, dan menghapus informasi buku di perpustakaan.
- **Manajemen Anggota:** Menambah, mengedit, dan menghapus data anggota perpustakaan.
- **Peminjaman Buku:** Proses peminjaman buku oleh anggota dan pengembalian buku.
- **Laporan:** Melihat laporan peminjaman buku, laporan data anggota dan laporan data buku.

#### Arsitektur Proyek (Package) :
- **Config** : Menghubungkan aplikasi dengan database.
- **Service** : Mengandung logika bisnis untuk operasi CRUD.
- **DAO** : Implementasi logika bisnis yang spesifik untuk database, termasuk implementasi antarmuka service.
- **Icon** : Menyimpan ikon aplikasi.
- **JDialog** : Mengelola tampilan form input.
- **Form** : Mengelola tampilan data di tabel.
- **Main** : Mengelola tampilan menu utama.
- **Model** : Mewakili entitas tabel database.
- **Menu** : Mengelola daftar menu aplikasi.
- **Report** : Mengelola file laporan aplikasi.
- **Theme** : Mengelola design warna dan layout aplikasi.

#### Instalasi dan Konfigurasi

**1. Clone Repository** :
```sh
git clone git@github.com:idteguhjulianto/AppPerpus-Desktop.git
```

**2. Masuk ke Direktori Proyek** :

```sh
cd AppPerpus-Desktop
```

**3. Jalankan Aplikasi** :
```sh
java -jar AppPerpus.jar
```
Atau Anda bisa langsung mengklik file JAR untuk menjalankan demo aplikasi perpustakaan ini.

Terima kasih

