# **Praktikum 7**
  ---------------
|Nama			|Kelas		|NIM		|
|-----			|-----		|-----		|
|Syahru	Raga Ramdhani	|TI.20.A.2	|312010354	|

# Langkah Praktikum
## Install XAMPP
* Install XAMPP dari https://www.apachefriends.org/download.html dan pilih versi portable untuk memudahkan proses instalasi.<br>
## Konfigurasi Web Server
* **Konfigurasi Apache** <br>
Untuk konfigurasi HTTP server, seperti port yang digunakan akses HTTP, modul yang diaktifkan, lokasi document root, dll.<br>
Lokasi file: **\xampp\apache\conf\httpd.conf**
* **Konfigurasi PHP** <br>
Untuk konfigurasi perilaku engine PHP yang berefek pada keamanan dan performa.
Seperti batas maksimal waktu eksekusi script, batas file yang dapat diupload error reporting, dll.<br>
Lokasi file: **\xampp\php\php.ini**
* **Konfigurasi MySql** <br>
Konfigurasi server MySQL, seperti administrator user, port, timezone, dll.<br>
Lokasi file: **\xampp\mysql\bin\my.ini**<br>
## Menjalankan Web Server
Untuk menjalankan web server dari menu XAMPP Control.
![Gambar](/gambar/Capture.PNG)
* Uji coba apakah server sudah bekerja denga baik <br>
http://127.0.0.1 atau http://127.0.0.1 <br>
Jika muncul tampilan utama XAMPP maka serve sudah bekerja dengan baik. 
* Dokumen Website<br>
Semua file website tempatkan di direktori: \xampp\htdocs\
* Database MySQL<br>
Direktori: \xampp\mysql\ <br>
Manajemen database: http://localhost/phpmyadmin <br>
* **Memulai PHP**<br>
Buat folder pada root directoy web server **(c:\xampp\htdocs)**
![Gambar](/gambar/Capture1.PNG)<br>
Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: http://localhost/Praktikum7/<br>
maka akan muncul tampilan seperti ini.
![Gambar](/gambar/Capture2.PNG)<br>
* **PHP Dasar**<br>
Buat file baru pada directory tersebut. Kemudian buat kode seperti berikut
![Gambar](/gambar/Capture3.PNG)<br>
Kemudian untuk mengakses hasilnya melalui URL: http://localhost/Praktikum7/php_dasar.php <br>
Maka akan muncul tampilan seperti berikut>
![Gambar](/gambar/Capture4.PNG)<br>
* **Variable PHP**<br>
Menambahkan variable pada program
![Gambar](/gambar/Capture5.PNG)<br>
Maka hasilnya seperti berikut.
![Gambar](/gambar/Capture6.PNG)<br>
* **Predefine Variable $_GET**
![Gambar](/gambar/Capture7.PNG)<br>
Untuk mengaksesnya gunakan URL: http://localhost/Praktikum7/php_dasar.php?nama=Syahru<br>
Maka hasilnya seperti berikut.
![Gambar](/gambar/Capture8.PNG)<br>
* **Membuat Form Input**<br>
Masukan kode seperti berikut.
![Gambar](/gambar/Capture9.PNG)<br>
maka hasilnya seperti berikut.
![Gambar](/gambar/Capture10.PNG)<br>
* **Operator**
Masukan kode seperti berikut.
![Gambar](/gambar/Capture11.PNG)<br>
maka hasilnya seperti berikut
![Gambar](/gambar/Capture12.PNG)<br>
* **Kondisi IF**
Masukan kode seperti berikut.
![Gambar](/gambar/Capture13.PNG)<br>
maka hasilnya seperti berikut.
![Gambar](/gambar/Capture14.PNG)<br>
* **Kondisi Switch**
Masukan kode seperti berikut.
![Gambar](/gambar/Capture15.PNG)<br>
maka hasilnya seperti berikut.
![Gambar](/gambar/Capture16.PNG)<br>
* **Perulangan for**
Masukan kode seperti berikut.
![Gambar](/gambar/Capture17.PNG)<br>
maka hasilnya seperti berikut.
![Gambar](/gambar/Capture18.PNG)<br>
* **Perulangan while**
Masukan kode seperti berikut.
![Gambar](/gambar/Capture19.PNG)<br>
maka hasilnya seperti berikut.
![Gambar](/gambar/Capture20.PNG)<br>
* **Perulangan dowhile**
Masukan kode seperti berikut.
![Gambar](/gambar/Capture21.PNG)<br>
maka hasilnya seperti berikut.
![Gambar](/gambar/Capture22.PNG)<br>
# **Pertanyaan dan Tugas**
Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan
nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung
umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang berbeda-beda sesuai pilihan pekerjaan.<br>
# **Jawaban**
