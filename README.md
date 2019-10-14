#latihan_git

#CARA MENGGUNAKAN GIT

1.Doawnload git di website resminya git (git-scm.com).
2.Menambahkan global config
 -Pada saat pertama kali menggunakan git kita perlu melakukan konfigurasi user.name dan user.email
 
 -Apabila belim dilakukan dapat mengakibatkan terjadinya kegagalan saat menjalankan perintah git commit.
 
 $ git config --global user.name "miftahuljannah"
 
 $ git config --global user.email "miftahuljannah2646@gmail.com"

![gambar config](https://github.com/miftahuljannah1202/vanilla/blob/master/gambar/ss%20git%20config.png?raw=true)
3.Membuat repository difolder baru 
 
 -Buat file baru pada repository anda dengan perintah git init
  ($ git init)

![gambar git init](https://github.com/miftahuljannah1202/vanilla/blob/master/gambar/ss%203%20git%20init.PNG)
 -lalu membuat file bernama README.md
  ($ echo "#latihan_git" >>README.md)

 -File README.md berhasil dibuat

4.Commit (menyimpan perubahan ke database)

 -Untuk menyimpan perubahan yang ada kedalam database repository local,gunakan perintah git commit -m "komentar commit"
 
 -File berhasil disimpan
  ($ git commit -m "file pertama saya"

5.Membuat repository server
 -Server repository yang akan kita gunakan adalah htttp://github.com
 
 -Anda harus membuat akun terlebih dahulu
 -Pada laman github,klik tombol strat project,atau
 
 -Dari menu (icon +) klik new repository
 
 -Isi nama repositorynya
 
 -Lalu klik tombol create repository

6.Menambahkan remote repository

 -Remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository,sehingga dapat diakses banyak user.
 
 -Untuk menambahkan remote  repository server,gunakan perintah ($ git remote add origin [url])

7.Push (mengirim perubahan ke server)
 
 -Untuk mengirim perubahan pada local repository keserver gunakan perintah git push.
  
 ($ git  push -u origin master)

 -Perintah ini akan meminta memasukan username dan password pada akun github.com
