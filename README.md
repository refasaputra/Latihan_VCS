# Latihan_VCS
Tutorial cara penggunaan git

Pertama kalian harus instal terlebih dahulu software Git Lalu kalian bisa buka software tersebut

1.Login Git
Langkah pertama kalian adalah memasukan username dengan menggunakan perintah

$ git config --global user.name "UsernameAnda"

lalu kalian tambahkan juga email dengan menggunakan perintah

$ git config --global user.email "email anda"

![Gambar 1](SS/1.png)
 
 2.Login Github
Langkah kedua kalian bisa login ke dalam website github, Setelah kalian login akan muncul tampilan dashboard dari github tersebut

![Gambar 2](SS/2.png)

3.Buat Repository
Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.

![Gambar 3](SS/3.png)

Kemudian kaliam akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.

![Gambar 4](SS/4.png)

4.Buat Folder
Lalu kalian buat folder di localdisk koomputer kalian

![Gambar 5](SS/5.png)

jika sudah kalian klik kanan pada folder tersebut lalu klik Git Bash

![Gambar 6](SS/6.png)

Buat folder dengan menggunakan perintah dan buka folder tersebut

$mkdir latihan1

$cd latihan1

![Gambar 7](SS/7.png)

![Gambar 8](SS/8.png)

dan tambahkan file README.md dengan menggunakan perintah

$echo "#LatihanVCS" >> README.md

![Gambar 9](SS/9.png)

kemudian buat repository lokal menggunakan perintah

$git init

![Gambar 10](SS/10.png)

Untuk menambahkan file yang baru saja dibuat tersebut menggunakan perintah

$git add README.md

![Gambar 11](SS/11.png)

Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah

$git commit -m "first commit"

![Gambar 12](SS/12.png)

kemudian gunakan perintah

$git branch -M main

![Gambar13 ](SS/13.png)

Setelah itu menambahkan remote repository. remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. dengan menggunakan perintah

$git remote add origin https://github.com/refasaputra/Latihan_VCS.git

![Gambar 14](SS/14.png)

Dan untuk mengirim perubahan pada local repository ke server gunakan perintah

$git push -u origin main

Dan kita bisa cek di repository langsung pada website github 

![Gambar 15](SS/15.png)

Sekian Dari Saya
Muhammad Refa Saputra

Mohon Maaf Bila Ada Kesalahan Namanya Manusia Tak Luput Dari Dosa dan Kesalahan
TERIMA KASIH

IG=Mohreffa_

FB=Muhammad Refa Saputra


