# Ekstraksi dan Transformasi data (CSV, JSON, dan database MySQL) untuk saling dihubungkan antar Sintaks Kode (SQL dan Python)
Pada kali ini, dilakukan proses mengkoneksi database di MySQL dengan Google Collab yang menggunakan sintaks Python. Selain itu, kami melakukan transformasi dan proses aggregate data produk terkait pemesanan, pelanggan, dan pemesanan setiap pelanggan menggunakan phpMyAdmin

Tahap awal dari menjalankan semua syntax ini adalah mengimport library, pada kali ini ditambahhkan syntax baru pada baris pertama dan terakhir yang mana syntax pada baris pertama berfungsi agar sql terkoneksi dengan syntax python yang telah dibuat dan syntax pada baris terakhir berfungsi agar data termuat pada syntax.

Lalu, akan di extract data yang akan digunakan. Ada tiga data yang digunakan yaitu, data CSV, JSON, dan database MySQL.

Untuk mengextract database dari MySQL, kali ini digunakan “Clever Cloud” untuk mengkoneksi database sql customer karena pada saat mencoba menggunakan “MySQL Workbench” data tidak terkoneksi.

Untuk mengkoneksi data melalui “Clever Cloud”, tahap pertama dilakukan pembuatan akun “Clever Cloud” itu sendiri, langkahnya yakni pilih create “Database Credentials” yang mana database ini gratis dan dapat dilakukan secara online. Setelah create database baru kita akan memperoleh host name, user name, beserta password dari database.

Masukkan host name, user name, dan password ke dalam perintah yang ada pada google collab

Untuk memasukkan code syntax sql kita bisa lakukan di PHPMyAdmin. Hal ini sama seperti memasukkan code syntax di sql workbench hanya saja ini dapat dilakukan dengan online di cloud.

Masukan code syntax untuk membuat tabel customers yang sudah diberikan sebelumnya ke PHPMyAdmin lalu kita jalankan. Jika sudah menghasilkan output tabel yang sesuai, maka database sudah dapat digunakan. Untuk melihat output tabel sudah sesuai atau belum, dapat digunakan syntax “SELECT*FROM(nama server)customers”.

Lalu, setelah database sudah terkoneksi dengan data customers, kita dapat menjalankan syntax extract data from MySQL database pada google collab. Sehingga apabila perintah tersebut berhasil dijalankan akan menghasilkan output yang dapat dilihat pada “Clever Cloud”

## Melakukan Tranform The Product Data
