# Latihan 2
NAMA : Uswatun Hasanah

NIM: 312210343

KELAS: TI.22.A3
1.Instal GIT for Windows
![Screenshot (43)](https://user-images.githubusercontent.com/115516474/196048215-92493a22-8ea6-44a2-8e08-3bb377a06607.png)


2.pilih direktori yang sudah aktif contohnya c:labs_pemograman1 lalu klik kanan dan pilih "git bash here"
![Screenshot (14)](https://user-images.githubusercontent.com/115516474/196048963-7154374b-649e-4b28-b56b-2d4860a68520.png)


3. Menambahkan Global Config 
-pada saat pertama kali menggunakan GIT, perlu dilakukan konfigurasi user.name dan user.email
-konfigurasi ini bisa di lakukan untuk global repostiry atau individual repository
-apabila belum dilakukian konfigurasi, akan mengakibatkan terjadinya kegagalan saat menjalankan perintah git commit
![Screenshot (44)](https://user-images.githubusercontent.com/115516474/196048820-d941206a-bf9b-45e1-be60-9dec6da56b7b.png)

4.Membuat Reposiory Local
Buat direktory projek pratikum pertama dengan nama latihan1
$ mkdir latihan1
$ cd latihan1


3.pilih direktori yang sudah aktif contohnya c:labs_pemograman1 lalu klik kanan dan pilih "git bash here"

![Screenshot (14)](https://user-images.githubusercontent.com/115516474/196048456-fd7a6106-5fa2-4cca-98da-ecf0c0242143.png)


3..Langkah pertama konfigurasi menggunakan nama dan email 

<img width="344" alt="tahap 1" src="https://user-images.githubusercontent.com/115516474/195516434-89b45d0d-1e56-4062-a4dc-6840c02901e8.png">>


4. Buat direktori dengan perintah mkdir lalu dimasukan ke direktorinya menggunakan cd gunakan perintah git init untuk membuat repository local.
     ![Screenshot (24)](https://user-images.githubusercontent.com/115516474/195974294-f31e4112-9269-48fa-a60a-563e5a6f1f2f.png)

4. Kemudia buat file README menggunakan perintah echo atau menggunakan git add (nama file)
![Screenshot (31)](https://user-images.githubusercontent.com/115516474/195977237-7503c19f-c9ef-42fa-864c-b7cbac08d169.png)
     
file README.md telah berhasil dibuat kemudian cek status jika ada file baru dengan perintah git status
 ![Screenshot (32)](https://user-images.githubusercontent.com/115516474/195977362-f2ece183-d7b0-4926-bf48-a75e8da8ec0c.png)
    
6. Kemudian lakukan perintah git commit -m (komentar commit) untuk menyimpan perubahan kedalam data base repostory local
  ![Screenshot (33)](https://user-images.githubusercontent.com/115516474/195977574-31b923d4-aa67-440d-832a-8a4f345ae4e6.png)
   
7. Buat repostory server menggunakan GITHUB sebelumnya harus membuat akun terlebih dahulu, kemudian klik ikon (+) New Story 
![Screenshot (35)](https://user-images.githubusercontent.com/115516474/195978006-0412f5e9-b7c4-4416-a58c-dfa890ceb2c3.png)

8. Kemudian kembali ke GITBASE, dengan menggunakan perintah git remote add origin (URL) untuk menambahkan remote ripostory
![Screenshot (36)](https://user-images.githubusercontent.com/115516474/195978201-ac6ced93-9e50-43d0-b18c-104f0da3e6e9.png)

9. Lalu cek ripository di GITHUB   

![Screenshot (37)](https://user-images.githubusercontent.com/115516474/195978338-93eb9fe8-302e-4529-9d10-b930b9f4cf2e.png)

Jika berhasil maka ada file yang di tambahkan di GITHUB nya

10. Dalam menyalin repository server gunakan perintah git cloone (URL)

