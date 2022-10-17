**Hallo nama saya Cahyo Hidayatullah. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah**  *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan **GIT**.
## Cara penginstalan GIT

  - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .
  
  ![Screenshot (17)](https://user-images.githubusercontent.com/115677959/195978004-f83ef297-525c-4675-8d1e-61391bcb8a78.png) *Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal*
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah **git --version.**  Saya memakai versi 2.38.0.windows.1

  ![Screenshot (19)](https://user-images.githubusercontent.com/115677959/195978194-04778e47-f0cd-4d03-9ceb-23394a12b588.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### _Cara membuat akun git_
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut *http://github.com*

![Screenshot (16)](https://user-images.githubusercontent.com/115677959/195978233-065cd98e-8f18-4b11-ab55-3ebec7a60813.png)

- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### _Membuat repositori baru_

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![Screenshot (13)](https://user-images.githubusercontent.com/115677959/195978469-53789f6c-4d88-4b94-ac44-77d8c05be1f0.png)

- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

 ![Screenshot (14)](https://user-images.githubusercontent.com/115677959/195978342-860c1ebf-98a0-470c-8586-272e72bfc79d.png)

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

  ![Screenshot (18)](https://user-images.githubusercontent.com/115677959/195978391-435ade62-7139-47d7-b50b-073c6c000bdb.png)

### _Membuat Repository Local_

- Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih **Git Bash here** .
![Screenshot (20)](https://user-images.githubusercontent.com/115677959/195978607-35aa8e50-d7fd-4451-b5a6-754d887eb31f.png)


- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      **$ git config --global user.email “email_user”**
      **$ git config --global user.name “nama_user”**

  ![Screenshot (21)](https://user-images.githubusercontent.com/115677959/195978719-d22ef8c7-0654-47b5-bc06-0ef830e067d6.png)


- Buatlah direktori baru dengan menggunakan perintah *" mkdir lab_pemrograman1 "*  LALU *" cd lab_pemrograman1![Screenshot (22)](https://user-images.githubusercontent.com/115677959/195978992-de8cc7b2-e91a-45b7-9c71-d8c019d9b6c8.png)
 "*.

 ##### _Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local_ 

- Lalu jalankan perintah *git init* untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
   ![Screenshot (23)](https://user-images.githubusercontent.com/115677959/195979071-05dae59d-5418-4612-bf24-c4f39c767a11.png)


-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

    ![Screenshot (24)](https://user-images.githubusercontent.com/115677959/195979189-8f39f73d-dcea-4d35-982d-d84ddefad965.png)

 ##### _Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah *git add*. Dengan perintah _$ git add README.md_. Kalau ingin melihat infonya ketik perintah _git status_.
  ![Screenshot (26)](https://user-images.githubusercontent.com/115677959/195979269-80794fee-01bd-4fab-b200-a13256253af6.png)


- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah _git commit -m “komentar commit"_
  ![67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3](https://user-images.githubusercontent.com/115677959/195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75.png)

##### **File berhasil tersimpan**

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### _Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)_

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/Hazelnuts22/Latihan_1.git
   ![Screenshot (8-)](https://user-images.githubusercontent.com/115677959/195979558-eb6c7913-ade9-4381-8584-d3ad396d119f.png)


 ##### _Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository_

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
   ![git_push](https://user-images.githubusercontent.com/115677959/195979685-82932b67-cc7a-458a-beb6-4c6a4a12612a.png)

 ##### _Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever._

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/Hazelnuts22/Latihan_1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah _“ls -1"_
  ![git_push](https://user-images.githubusercontent.com/115677959/195979779-f936d543-9d8c-49e7-8e8c-dcedaa119557.png)


-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  
#### **FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas**.
### **Terimakasih**

 
