# Praktikum
- Membuat Database
![a1](https://github.com/kannahs/Lab12web/blob/master/image/a1.PNG?raw=true)

- Lalu buat tabel
![a2](https://github.com/kannahs/Lab12web/blob/master/image/a2.PNG?raw=true)

- Selanjutnya membuat konfigurasi untuk menghubungkan dengan database server.
![a3](https://github.com/kannahs/Lab12web/blob/master/image/a3.PNG?raw=true)

- Selanjutnya adalah membuat Model untuk memproses data Artikel. Buat file baru pada direktori app/Models dengan nama ArtikelModel.php
![a4](https://github.com/kannahs/Lab12web/blob/master/image/a4.PNG?raw=true)

- Buat Controller baru dengan nama Artikel.php pada direktori app/Controllers.
![a5](https://github.com/kannahs/Lab12web/blob/master/image/a5.PNG?raw=true)

- Buat direktori baru dengan nama artikel pada direktori app/views, kemudian buat file baru dengan nama index.php.
![a6](https://github.com/kannahs/Lab12web/blob/master/image/a6.PNG?raw=true)

- Selanjutnya buka browser kembali, dengan mengakses url http://localhost:8080/artikel
![b6](https://github.com/kannahs/Lab12web/blob/master/image/b6.PNG?raw=true)

- Tambahkan data pada database
![a7](https://github.com/kannahs/Lab12web/blob/master/image/a7.PNG?raw=true)

- Hasilnya .
![b7](https://github.com/kannahs/Lab12web/blob/master/image/b7.PNG?raw=true)

- Tampilan pada saat judul berita di klik maka akan diarahkan ke halaman yang berbeda. Tambahkan fungsi baru pada Controller Artikel dengan nama view().
![a8](https://github.com/kannahs/Lab12web/blob/master/image/a8.PNG?raw=true)

- Buat view baru untuk halaman detail dengan nama app/views/artikel/detail.php.
![a9](https://github.com/kannahs/Lab12web/blob/master/image/a9.PNG?raw=true)

- Buka Kembali file app/config/Routes.php, kemudian tambahkan routing untuk artikel detail.
![a10](https://github.com/kannahs/Lab12web/blob/master/image/a10.PNG?raw=true)

- Artikel yang di tampilkan
![b9](https://github.com/kannahs/Lab12web/blob/master/image/b9.PNG?raw=true)

- Menu admin adalah untuk proses CRUD data artikel. Buat method baru pada Controller Artikel dengan nama admin_index().
![a11](https://github.com/kannahs/Lab12web/blob/master/image/a11.PNG?raw=true)

- Selanjutnya buat view untuk tampilan admin dengan nama admin_index.php
![a12](https://github.com/kannahs/Lab12web/blob/master/image/a12.PNG?raw=true)

- Tambahkan routing untuk menu admin seperti berikut:
![a13](https://github.com/kannahs/Lab12web/blob/master/image/a13.PNG?raw=true)

- Akses menu admin dengan url http://localhost:8080/admin/artikel
![b12](https://github.com/kannahs/Lab12web/blob/master/image/b12.PNG?raw=true)

- Tambahkan fungsi/method baru pada Controller Artikel dengan nama add().
![a14](https://github.com/kannahs/Lab12web/blob/master/image/a14.PNG?raw=true)

- Kemudian buat view untuk form tambah dengan nama form_add.php
![a15](https://github.com/kannahs/Lab12web/blob/master/image/a15.PNG?raw=true)

- Hasilnya . 
![b15](https://github.com/kannahs/Lab12web/blob/master/image/b15.PNG?raw=true)

- Tambahkan fungsi/method baru pada Controller Artikel dengan nama edit().
![a16](https://github.com/kannahs/Lab12web/blob/master/image/a16.PNG?raw=true)

- Kemudian buat view untuk form tambah dengan nama form_edit.php
![a17](https://github.com/kannahs/Lab12web/blob/master/image/a17.PNG?raw=true)

- Hasilnya
![b17](https://github.com/kannahs/Lab12web/blob/master/image/b17.PNG?raw=true)

- Tambahkan fungsi/method baru pada Controller Artikel dengan nama delete().
![a18](https://github.com/kannahs/Lab12web/blob/master/image/a18.PNG?raw=true)

