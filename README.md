---

# 🎉 Panduan Penggunaan GitHub Organization! 🎉

## Daftar Isi

1. [Cara Membuat Repository di GitHub Organization](#cara-membuat-repository-di-github-organization)
2. [Cara Push Pekerjaan ke Repository](#cara-push-pekerjaan-ke-repository)
3. [⚠️ Peraturan Ketat Terkait Plagiarisme](#peraturan-ketat-terkait-plagiarisme)

---

### 💻 Cara Membuat Repository di GitHub Organization

Ikuti langkah-langkah berikut untuk membuat repository di dalam sebuah GitHub Organization:

1. **Login ke GitHub**: Masuk ke akun GitHub kamu.
2. **Navigasi ke Halaman Organization**:
   - Klik di menu profil kamu di kanan atas, lalu pilih nama organisasi yang ingin kamu buatkan repository.
3. **Membuat Repository**:
   - Di halaman organisasi, klik tab `Repositories`.
   - Klik tombol hijau `New` di sebelah kanan atas.
   - Isi detail repository seperti:
     - **Format Nama REPOSITORY**: STAMBUK_NAMA.
     - **Description** (opsional): Deskripsi singkat tentang repository.
     - **Public/Private**: **Pilih opsi ************`Private`************!** Repository **wajib** bersifat private agar tidak bisa diakses sembarang orang.
   - Klik `Create repository` setelah selesai mengisi detail.
   - ** ISI DALAM REPOSITORY AKAN DIPENUHI OLEH CODE LAPRAK 1 - SELESAI. USAHAKAN DALAM 1 REPOSITORY PISAHKAN PERFOLDER SETIAP LAPRAK. **
4. **Inisialisasi Repository**:
   - Kamu bisa memilih untuk menambahkan file README, `.gitignore`, atau lisensi saat membuat repository, atau bisa menambahkannya nanti.

⚠️ **Penting**: Jika repository dibuat **Public**, maka akan dianggap sebagai pelanggaran dan tugas kamu bisa dinyatakan **GAGAL**!

---

### 🚀 Cara Push Pekerjaan ke Repository

Setelah repository dibuat, kamu bisa mempush pekerjaan kamu dengan langkah-langkah berikut:

1. **Buka Terminal atau Command Prompt**, lalu pindah ke folder project kamu:
   ```sh
   cd /path/to/project
   ```

2. **Inisialisasi Git di dalam folder jika belum dilakukan**:
   ```sh
   git init
   ```

3. **Tambahkan repository remote dari GitHub**:
   ```sh
   git remote add origin https://github.com/organization_name/repository_name.git
   ```
   Gantilah `organization_name` dengan nama organisasi dan `repository_name` dengan nama repository kamu.

4. **Tambahkan file ke staging area**:
   ```sh
   git add .
   ```

5. **Buat commit dengan pesan yang jelas**:
   ```sh
   git commit -m "Menambahkan pekerjaan pertama"
   ```

6. **Push pekerjaan ke repository GitHub**:
   ```sh
   git push -u origin main
   ```
   Jika branch utama bukan `main`, ganti dengan nama branch yang digunakan.

---

### ⚠️ Peraturan Ketat Terkait Plagiarisme

Plagiarisme adalah pelanggaran serius yang tidak akan ditoleransi. Berikut aturan yang harus diperhatikan:

- **Dilarang keras menyalin kode dari repository lain tanpa izin dan referensi yang jelas!**
- **Dilarang menyalin tugas dari teman atau repository lain dalam satu organisasi!**
- **Jika ditemukan kode yang identik atau hampir sama, maka nilai akan otomatis menjadi ERROR dan ditolak!**
- **Semua repository akan diperiksa menggunakan alat pendeteksi plagiarisme otomatis!**
- **Jika ada repository public yang terbukti digunakan untuk berbagi kode secara ilegal, pemiliknya akan diberikan sanksi berat!**

🚨 **PERHATIAN!** Jika melanggar aturan ini, maka:

1. **Nilai tugas akan otomatis ERROR dan tidak bisa diperbaiki!**
2. **Repository akan diperiksa ulang oleh tim untuk investigasi lebih lanjut!**
3. **Pelanggaran berulang akan berakibat pada tindakan lebih lanjut sesuai kebijakan organisasi!**

---

