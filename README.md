# Latihan 2
NAMA : Uswatun Hasanah

NIM: 312210343

KELAS: TI.22.A3

1.Instal GIT for Windows

![Screenshot (43)](https://user-images.githubusercontent.com/115516474/196048215-92493a22-8ea6-44a2-8e08-3bb377a06607.png)


2.pilih direktori yang sudah aktif contohnya c:labs_pemograman1 lalu klik kanan dan pilih "git bash here"

![Screenshot (14)](https://user-images.githubusercontent.com/115516474/196048963-7154374b-649e-4b28-b56b-2d4860a68520.png)


3. Menambahkan Global Config 
pada saat pertama kali menggunakan GIT, perlu dilakukan konfigurasi user.name dan user.email
konfigurasi ini bisa di lakukan untuk global repostiry atau individual repository 
apabila belum dilakukian konfigurasi, akan mengakibatkan terjadinya kegagalan saat menjalankan perintah git commit

![Screenshot (44)](https://user-images.githubusercontent.com/115516474/196048820-d941206a-bf9b-45e1-be60-9dec6da56b7b.png)


4.Membuat Reposiory Local
Buat direktory projek pratikum pertama dengan nama latihan1

![Screenshot (47)](https://user-images.githubusercontent.com/115516474/196049957-008dfee1-302a-48fe-89d6-57c7f1bfe418.png)

-sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directpry)


5.Membuat Repository Local
-Jalankan perintah GIT INIT, untuk membuat repository lokal

![Screenshot (49)](https://user-images.githubusercontent.com/115516474/196050423-d77c6ade-54a5-4fe2-b4a7-2fa6b2373442.png)

-Repository baru berhasil di inisialsasi, dengan terbentuknya satu direktori hidden nama .git


6.Menambhakan File baru pada repository
-Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
-disini saya akan coba buat satu file bernama README.md

![Screenshot_20221017-005706_Chrome](https://user-images.githubusercontent.com/115516474/196050885-53c78d3d-a1be-4d00-b868-067a54ba7a98.jpg)

-File README.md berhasil dibuat

![Screenshot (50)](https://user-images.githubusercontent.com/115516474/196051163-4897c32d-3ab8-4714-a95e-399b9e852d30.png)

-Untuk menambah file yang baru saja dibuat tersebut gunakan perintah git add

![Screenshot_20221017-011545_Drive](https://user-images.githubusercontent.com/115516474/196051439-845a351d-b8b7-4d24-9671-abf8ea25b1a8.jpg)

-File README.md berhasil ditambahkan

![Screenshot (51)](https://user-images.githubusercontent.com/115516474/196051531-58e547f9-7ebe-4c91-bc21-2fef31902ab1.png)


7. Menyimpan perubahan ke database (commit)
-Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah "git commit -m "file pertama saya"

![Screenshot (52)](https://user-images.githubusercontent.com/115516474/196051938-2ab2a12d-d69a-4a28-ad30-966d91005864.png)


8.Membuat repository server
-Server repository yang akan digunakan adalah http://github.com
-pada laman github, klik tombol star a projeck, atau dari menu icon + klik New Repository

![Screenshot (53)](https://user-images.githubusercontent.com/115516474/196052189-7679a6a7-9a9d-4897-87f0-c943a8b9e888.png)


9.Membuat repository server
-isi nama repository latihan 1
-lalu klik tombol Create repository

![Screenshot (56)](https://user-images.githubusercontent.com/115516474/196052405-59e6e0ff-0eb2-478c-8aa3-c44601887de8.png)


10.Menambahkan Remote Repository 
-Repository merupakan server yang digunakan untuk menyimpan perubahan pada local repositori sehingga dapat diakses oleh banyak user. 
-Untuk menambahkan remote repository server, gunakan perintah git remote add origin (URL)
-$git remote add origin


11. Push (mengirim perubahan ke server)
-Untuk mengirim perubahan pada local repository ke server gunakan perintah git push

![Screenshot_20221017-014518_Chrome](https://user-images.githubusercontent.com/115516474/196053107-48d20ace-5fba-407d-bfc6-8b25e9525d68.jpg)

-perintah ini akan meminta memasukan username dan password pada akun github.com

![Screenshot (57)](https://user-images.githubusercontent.com/115516474/196053285-b4872689-6d0d-442c-ad39-72a63ba002de.png)


12. Melihat hasilnya pada server repository
-Buka laman github.com arahkan pada repositorynya
-Maka perubahan akan terlihat pada laman tersebut

![Screenshot (60)](https://user-images.githubusercontent.com/115516474/196053489-1a6f5461-4376-42f8-b021-0035b5de6faf.png)


13.Clone Repository
-Clon repository adalah meng-copy repositori server dan secara otomatis membuat suatu directori sesuai dengan nama repositorynya 
(working direktory). Untuk melakukan clone menggunakan perintah git clone (URL)

![Screenshot (57)](https://user-images.githubusercontent.com/115516474/196053689-7111490c-a4d7-4b1b-95e4-e5c503bb8155.png)



