# Sistem Penghitungan Nilai Mahasiswa

![Sistem Penghitungan Nilai Mahasiswa](https://github.com/pangaribowo/MyNilai_22030022/img/blob/main/apk.png)

## Deskripsi:

Aplikasi Sistem Penghitungan Nilai Mahasiswa adalah sebuah aplikasi berbasis Java yang dirancang untuk membantu pengguna, khususnya dosen atau instruktur, dalam menghitung nilai akhir mahasiswa berdasarkan bobot dan nilai-nilai yang telah dimasukkan. Aplikasi ini dapat digunakan untuk mengelola nilai mahasiswa dengan efisien dan akurat.

## Fitur Utama

### 1. Input Nilai:

Pengguna dapat memasukkan nilai presensi, tugas, UTS, dan UAS mahasiswa.
Aplikasi memvalidasi input untuk memastikan bahwa hanya angka yang diterima.

### 2. Pengaturan Bobot:

Pengguna dapat mengatur bobot atau persentase nilai untuk setiap komponen penilaian (presensi, tugas, UTS, dan UAS).
Bobot UAS telah ditetapkan sebesar 30% dan tidak dapat diubah.

### 3. Perhitungan Otomatis:

Aplikasi secara otomatis menghitung nilai akhir mahasiswa berdasarkan bobot dan nilai yang dimasukkan.
Menampilkan hasil perhitungan nilai akhir pada layar.

### 4. Validasi Total Bobot:

Aplikasi memvalidasi total bobot agar tidak melebihi 100%.
Jika total bobot melebihi 100%, pengguna akan menerima peringatan.

### 5. Penentuan Grade:

Aplikasi menentukan grade berdasarkan nilai akhir yang dihasilkan.
Grade yang ditampilkan meliputi A, B, C, D, dan E.

### 6. Validasi Input:

Validasi khusus untuk memastikan bahwa input angka berada dalam rentang yang diizinkan.
Peringatan muncul jika nilai presensi, tugas, atau bobot berada di luar batas yang ditentukan.

## Cara Penggunaan:

1. Jalankan aplikasi menggunakan file JAR.
2. Pengguna memasukkan nilai presensi, tugas, UTS, dan UAS.
Menyesuaikan bobot untuk setiap komponen penilaian jika diperlukan.
3. Aplikasi secara otomatis menghitung nilai akhir dan menampilkan hasilnya.
Pengguna mendapatkan informasi grade berdasarkan nilai akhir.
4. Gunakan button "Reset" untuk menghapus inputan atau "Hitung" untuk mendapatkan nilai akhir.
5. Gunakan button "Tutup" untuk keluar dari aplikasi.

## Catatan:

Aplikasi ini dibangun menggunakan Java dan NetBeans sebagai lingkungan pengembangan. Pastikan untuk menjalankan aplikasi pada lingkungan yang mendukung Java.

Aplikasi ini diharapkan dapat membantu pengguna dalam mengelola dan menghitung nilai mahasiswa secara praktis. Jangan ragu untuk memberikan umpan balik atau melaporkan masalah melalui GitHub Issues.

Terima kasih telah menggunakan Aplikasi Sistem Penghitungan Nilai Mahasiswa!

### Use Case Model

![Use Case](https://github.com/pangaribowo/MyNilai_22030022/blob/main/uc.png)

### Tampilan Setelah Input
![Setelah Input](https://github.com/pangaribowo/MyNilai_22030022/blob/main/apk2.png)

...

## Pengembangan Selanjutnya

- Tambahkan fitur Panel Login untuk Admin.
- Percantik Tampilan.
- Pisahkan menjadi 3 Frame.
- Koneksikan dengan database.

## Kontribusi

Anda dapat berkontribusi dengan membuat _fork_ dan mengirimkan _pull request_.

======================== BUILD OUTPUT DESCRIPTION ======================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "MyNilai_22030022.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

## 📑 License
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

[MyNilai_22030022](https://github.com/pangaribowo/MyNilai_22030022/) is Free Java Archieve: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 