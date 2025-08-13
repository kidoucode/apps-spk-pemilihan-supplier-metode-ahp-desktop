# Aplikasi Sistem Pendukung Keputusan Pemilihan Supplier Terbaik Menggunakan Metode AHP (Java NetBeans & MySQL)

Aplikasi ini merupakan sistem pendukung keputusan untuk pemilihan supplier terbaik menggunakan metode AHP, dibangun dengan **Java Swing** untuk antarmuka pengguna dan **MySQL** sebagai database.  
Aplikasi ini cocok digunakan untuk tugas akhir, studi kasus bisnis, atau pengambilan keputusan berbasis kriteria.  

> **Catatan:** File yang dibagikan di sini adalah versi demo. Jika ingin mendapatkan versi lengkap, dapat dibeli di [LYNK.ID KidouCode](https://lynk.id/kidoucode).

---

#### **Teknologi**
- [MySQL 8.0.40](https://downloads.mysql.com/archives/get/p/25/file/mysql-installer-community-8.0.40.0.msi)  
- [JDK 11](https://www.oracle.com/id/java/technologies/javase/jdk11-archive-downloads.html)  

Untuk menjalankan versi demo, cukup menggunakan **JDK 11**, karena database sudah di-host secara online.  
Namun, koneksi ke database mungkin mengalami keterlambatan.

---

#### **Library / Dependensi**

- **FlatLaf (Java Look and Feel)**  
  - `flatlaf-3.5.2.jar` → Tema modern Java Swing  
  - `flatlaf-3.5.2-sources.jar` → Source code untuk referensi/debug  
  - `flatlaf-extras-3.5.2.jar` → Fitur tambahan seperti custom accent color, font, dan icon  
  - `flatlaf-fonts-roboto-2.137.jar` → Font Roboto bawaan  
  - `flatlaf-intellij-themes-3.2.5.jar` → Tema mirip IntelliJ IDEA  
  - `jsvg-1.4.0.jar` → Render gambar SVG untuk icon  

- **MigLayout**  
  - `miglayout-core-5.3.jar` → Layout manager inti  
  - `miglayout-swing-5.3.jar` → Integrasi untuk Swing  

- **Modal Dialog**  
  - `modal-dialog-2.1.0.jar` → Dialog kustom dengan animasi  
  - `modal-dialog-demo-2.1.0.jar` → Contoh penggunaan  

- **MySQL Driver**  
  - `mysql-connector-j-8.0.31.jar` → JDBC driver MySQL/MariaDB  

- **Hashing**  
  - `jbcrypt-0.4.jar` → Hash password dengan BCrypt  

- **PDF**  
  - `itextpdf-5.5.13.jar` → Generate dan edit PDF  

- **Excel (Apache POI)**  
  - `commons-collections4-4.4.jar` → Koleksi tambahan untuk POI  
  - `commons-compress-1.19.jar` → Kompresi/dekompresi file  
  - `poi-4.1.2.jar` → Apache POI core  
  - `poi-ooxml-4.1.2.jar` → Format Office baru (XLSX, DOCX, PPTX)  
  - `poi-ooxml-schemas-4.1.2.jar` → Skema OOXML  
  - `stax-api-1.0.1.jar` → Parsing XML streaming  
  - `xmlbeans-3.1.0.jar` → Pemrosesan XML untuk POI  

---

#### **Fitur Utama**
- Input supplier & kriteria  
- Perbandingan berpasangan (AHP)  
- Perhitungan bobot & konsistensi  
- Hasil ranking  

---

#### **Arsitektur Proyek (Package)**
- **Config** : Menangani konfigurasi koneksi aplikasi dengan database.  
- **DAO** : Implementasi logika akses data ke database, termasuk penerapan antarmuka service.  
- **Form** : Mengatur dan menampilkan data dalam bentuk tabel.  
- **Form Input** : Mengatur tampilan dan fungsi form untuk input data.  
- **Icon & Img** : Menyimpan ikon dan gambar yang digunakan aplikasi.  
- **Main** : Mengatur tampilan dan logika menu utama aplikasi.  
- **Model** : Mewakili struktur entitas sesuai tabel database.  
- **Service** : Menyimpan logika bisnis untuk operasi CRUD, menghubungkan DAO dan UI.  
- **TableModel** : Model tabel khusus untuk `JTable`.  
- **Theme** : Menangani tema warna, gaya, dan layout aplikasi.  
- **Util** : Berisi fungsi-fungsi utilitas umum.  

---

#### **Instalasi & Menjalankan Aplikasi**

**1. Clone Repository**
```sh
git clone https://github.com/kidoucode/apps-spk-pemilihan-supplier-metode-ahp-desktop.git
```

**2. Masuk ke Direktori Proyek** :

```sh
cd apps-spk-pemilihan-supplier-metode-ahp-desktop
```

**3. Jalankan Aplikasi** :
```sh
java -jar Apps_SPK_AHP_Supplier.jar
```
Atau Anda bisa langsung mengklik file JAR untuk menjalankan demo aplikasi perpustakaan ini.

Terima kasih

