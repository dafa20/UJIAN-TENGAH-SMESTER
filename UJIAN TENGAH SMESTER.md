**UJIAN TENGAH SMESTER**

Sistem Administrasi Smester

DAFA SEPTIANDRI (1202192033)

1. Download ISO installer windows server 2022

   - Link download berada di soal uts,jika kalian mengikuti perintah akan muncul tampilan seperti di bawah ini.

     <img src="C:\Users\owner\Downloads\UTS SAS\1.png" alt="1" style="zoom: 33%;" />

   - Pilih download the ISO kemudian lakukan step by stepnya. Jangan lupa centang yes kemudian continue

     

   - Pilih bahasa yang kalian inginkan 

     <img src="C:\Users\owner\Downloads\UTS SAS\2.png" alt="2" style="zoom:33%;" />
     
     

2. Langkah Langkah instalasi :

   - Instalasi Window Server 2022

     - open VirtualBox lalu anda klik mesin - new project

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124132505122.png" alt="image-20211124132505122" style="zoom: 50%;" />

     - Masukan Nama Dari sistem yang ingin digunakan

       <img src="C:\Users\owner\Downloads\UTS SAS\4.png" alt="4" style="zoom:50%;" />

     - Sesuaikan ukuran RAM dengan kondisi pc/laptop kalian

       <img src="C:\Users\owner\Downloads\UTS SAS\5.png" alt="5" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\6.png" alt="6" style="zoom:50%;" />

       

       <img src="C:\Users\owner\Downloads\UTS SAS\7.png" alt="7" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\8.png" alt="8" style="zoom:50%;" />

     - Sesuaikan size file Sesuia Rekomendasi dibawah

       <img src="C:\Users\owner\Downloads\UTS SAS\9.png" alt="9" style="zoom:50%;" />

     - Setting konfigurasi "network" dan set "bridge adapter" pada VBox

       <img src="C:\Users\owner\Downloads\UTS SAS\10.png" alt="10" style="zoom:50%;" />

     - Klik "start" Kemudian Pilih ISO yang sudah ter unduh

       <img src="C:\Users\owner\Downloads\UTS SAS\11.png" alt="11" style="zoom:50%;" />

     - Klik Start dan instalasi windows server 2022 wizzard muncul

       <img src="C:\Users\owner\Downloads\UTS SAS\12.png" alt="12" style="zoom:50%;" />

     - Klik install Now

       <img src="C:\Users\owner\Downloads\UTS SAS\13.png" alt="13" style="zoom:50%;" />

     - Pilih LIsensi Windows Server Datacenter Evolution(Dekstop Experience) lalu "next"

       <img src="C:\Users\owner\Downloads\UTS SAS\14.png" alt="14" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\15.png" alt="15" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\16.png" alt="16" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\17.png" alt="17" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\18.png" alt="18" style="zoom:50%;" />

     - Apabila Sudah Ter install sistem akan me reboot ulang otomatis

       <img src="C:\Users\owner\Downloads\UTS SAS\19.png" alt="19" style="zoom:50%;" />

     - Klik menu "input keyboard - insert Ctrl-Alt-Del" lalu masukan password anda yang di buat

       <img src="C:\Users\owner\Downloads\UTS SAS\20.png" alt="20" style="zoom:50%;" />

     - Lalu klik menu "Devices-install guest additions CD image" pada VBox 

       ![21](C:\Users\owner\Downloads\UTS SAS\21.png)

     - Pada "file explorer", run berikut ininkemudian ikuti step nya

       <img src="C:\Users\owner\Downloads\UTS SAS\22.png" alt="22" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\23.png" alt="23" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\24.png" alt="24" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\25.png" alt="25" style="zoom:50%;" />

       <img src="C:\Users\owner\Downloads\UTS SAS\26.png" alt="26" style="zoom:50%;" />

     - Setelah itu sistem akan me reboot otomatis, lalu masukan lagi password  

       ![27](C:\Users\owner\Downloads\UTS SAS\27.png)

   - Instalasi Active Directory Domain Service

     - Sebelum Melakukan instalasi lakukan pergantian nama computer dengan masuk ke windows powershell, kemudian ketikan "rename-computer -Newname Server 2022"

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124142845715.png" alt="image-20211124142845715" style="zoom: 67%;" />

     - Masuk ke menu "server manager" lalu pilih opsi "manager" dilanjutkan dengan klik "add roles and features". kemudian klik "next"

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124142902254.png" alt="image-20211124142902254" style="zoom: 67%;" />

     - Pilih Opsi "role-based or feture-based instalation" lalu next

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124142959907.png" alt="image-20211124142959907" style="zoom:67%;" />

     - klik "Select a server from the server pool" untuk memilih direktori penyimpanan lokal.lalu next

       <img src="C:\Users\owner\Downloads\UTS SAS\29.png" alt="29" style="zoom:67%;" />

     - Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”

       <img src="C:\Users\owner\Downloads\UTS SAS\30.png" alt="30" style="zoom: 67%;" />

     - Kemudian centang kotak “Group Policy Management” dan tekan tombol Next

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143216319.png" alt="image-20211124143216319" style="zoom: 67%;" />

     - Klik Next

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143236118.png" alt="image-20211124143236118" style="zoom:67%;" />

     - Klik "Install" dan tunggu hingga selesai

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143249021.png" alt="image-20211124143249021" style="zoom:67%;" />

   - Instalasi DNS Server

     - Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143500439.png" alt="image-20211124143500439" style="zoom:67%;" />

   - Instalasi NET Framework 3.5

     - Centang "NET Framework 3.5 Features"

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143548021.png" alt="image-20211124143548021" style="zoom:67%;" />

     - Klik Next

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143659498.png" alt="image-20211124143659498" style="zoom:67%;" />

     - Lalu Klik Install

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143752056.png" alt="image-20211124143752056" style="zoom:67%;" />

     - Lalu Tunggu hingga selesai

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124143804583.png" alt="image-20211124143804583" style="zoom:67%;" />

   - Promote Server to a domain Controller

     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan

     - Seting ke ip static menggunakan cmd, ketik "sconfig" - ketik "1"

       <img src="C:\Users\owner\Downloads\UTS SAS\31.png" alt="31" style="zoom:67%;" />

     - Kemudian setting network

       <img src="C:\Users\owner\Downloads\UTS SAS\32.png" alt="32" style="zoom:67%;" />

     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan

       <img src="C:\Users\owner\Downloads\UTS SAS\40.png" alt="40" style="zoom:67%;" />

     - Klik “Promote this server to a domain controller" untuk konfigurasi ADDS

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124145109391.png" alt="image-20211124145109391" style="zoom:67%;" />

     - Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain "dafa.com"

       <img src="C:\Users\owner\Downloads\UTS SAS\33.png" alt="33" style="zoom:67%;" />

     - Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124145201092.png" alt="image-20211124145201092" style="zoom:67%;" />

     - Lewati bagian DNS Options, lalu klik “Next”

       <img src="C:\Users\owner\Downloads\UTS SAS\37.png" alt="37" style="zoom:67%;" />

     - Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan

       <img src="C:\Users\owner\Downloads\UTS SAS\34.png" alt="34" style="zoom:67%;" />

     - Lewati bagian Paths, klik “Next” 

       <img src="C:\Users\owner\Downloads\UTS SAS\35.png" alt="35" style="zoom:67%;" />

       

     - Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan

       <img src="C:\Users\owner\Downloads\UTS SAS\36.png" alt="36" style="zoom:67%;" />

     - Tunggu Instalasi hingga selesai

       <img src="C:\Users\owner\AppData\Roaming\Typora\typora-user-images\image-20211124145603350.png" alt="image-20211124145603350" style="zoom:67%;" />

     - Apabila sudah selesai sistem akan auto reboot, lalu cek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo”

       <img src="C:\Users\owner\Downloads\UTS SAS\39.png" alt="39" style="zoom:67%;" />

     - Setelah login dengan Active Directory Domain Controller Anda, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS

       <img src="C:\Users\owner\Downloads\UTS SAS\40.png" alt="40" style="zoom:67%;" />

     - Kemudian ubah IP Address sesuai dengan awal tadi

<img src="C:\Users\owner\Downloads\UTS SAS\41.png" alt="41" style="zoom:67%;" />
