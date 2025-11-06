# Judul2-Jarkom

Percobaan 2 Build a Switch and Router Network bertujuan untuk membangun jaringan dasar yang terdiri dari router, switch, dan dua PC. Dalam kegiatan ini, setiap perangkat dikonfigurasi sesuai tabel alamat IP yang telah ditentukan. Setelah konfigurasi dilakukan, dilakukan pengujian konektivitas antarperangkat menggunakan perintah ping untuk memastikan komunikasi jaringan berjalan dengan benar, baik pada jaringan IPv4 maupun IPv6.

Sebelum router dikonfigurasi, ping antar-PC tidak berhasil karena router belum memiliki konfigurasi antarmuka (interface) yang menghubungkan dua jaringan berbeda. Akibatnya, tidak ada rute Layer 3 yang memungkinkan pengiriman paket data antar subnet.
Dengan kata lain, PC-A dan PC-B berada di dua jaringan yang berbeda, dan karena default gateway (router) belum aktif atau belum diberi alamat IP, maka paket tidak dapat diteruskan antarjaringan.

Sebelum di Konfigurasi
https://github.com/Llianzz/Judul2-Jarkom/blob/19358f12fbe9abdff984e918b868bd6fcd130764/Screenshot%202025-11-06%20233404.png

Setelah router dikonfigurasi dengan benar yaitu setiap antarmuka diberi alamat IP sesuai subnet dan diaktifkan dengan perintah no shutdown barulah router mampu melakukan routing antarjaringan. Saat perintah ping dijalankan kembali, ping berhasil karena router sudah berfungsi sebagai penghubung antar default gateway, setiap interface aktif dan memiliki alamat IP yang valid dan routing IPv4 dan IPv6 telah diaktifkan.

Setelah Konfigurasi
https://github.com/Llianzz/Judul2-Jarkom/blob/4d299c64bed7a5e33cc931ae916e7d42854f4d21/Screenshot%202025-11-06%20233516.png



Berikut Video Penjelasan
https://youtu.be/_zZ7Ba4Yt5I
