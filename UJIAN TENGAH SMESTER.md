**UJIAN TENGAH SMESTER**

Sistem Administrasi Smester

DAFA SEPTIANDRI (1202192033)

1. Download ISO installer windows server 2022

   - Link download berada di soal uts,jika kalian mengikuti perintah akan muncul tampilan seperti di bawah ini.

   ![1](https://user-images.githubusercontent.com/93079538/143207917-eef43535-1909-4fb7-98f8-1cf357752640.png)

   - Pilih download the ISO kemudian lakukan step by stepnya. Jangan lupa centang yes kemudian continue

     

   - Pilih bahasa yang kalian inginkan 

   ![2](https://user-images.githubusercontent.com/93079538/143207931-9ceaa177-4366-4a4b-8a35-4f9eec572213.png)
     
     

2. Langkah Langkah instalasi :

   - Instalasi Window Server 2022

     - open VirtualBox lalu anda klik mesin - new project

       ![3](https://user-images.githubusercontent.com/93079538/143207935-08eaf9e0-d452-493e-a58e-27a9e0ec71f6.png)
       

     - Masukan Nama Dari sistem yang ingin digunakan

       ![4](https://user-images.githubusercontent.com/93079538/143209021-03ab28c0-0922-4d31-892c-0b42cf349992.png)

     
     - Sesuaikan ukuran RAM dengan kondisi pc/laptop kalian

       ![5](https://user-images.githubusercontent.com/93079538/143209310-638094af-e016-49ac-8b1e-4a200b64353a.png)

       ![5 1](https://user-images.githubusercontent.com/93079538/143207939-b64414c0-ae39-4b17-b1d4-b91c0ced9f3e.png)

       

       ![5 2](https://user-images.githubusercontent.com/93079538/143207942-a33adb08-ae49-4c22-87fa-8aafbea57167.png)

       ![5 3](https://user-images.githubusercontent.com/93079538/143207944-a7727b0b-8246-4249-9de4-385b288981ce.png)

     
     - Sesuaikan size file Sesuia Rekomendasi dibawah

       ![6](https://user-images.githubusercontent.com/93079538/143207950-863208d2-298b-4202-b4b0-5a5e52c61853.png)
       

     - Setting konfigurasi "network" dan set "bridge adapter" pada VBox

       ![10](https://user-images.githubusercontent.com/93079538/143207953-41e3d0e0-2d72-4b5e-a5fe-6bd957d73a77.png)
       

     - Klik "start" Kemudian Pilih ISO yang sudah ter unduh

       ![11](https://user-images.githubusercontent.com/93079538/143207956-b3f270ec-0254-471e-ac13-f913bd47c917.png)
       

     - Klik Start dan instalasi windows server 2022 wizzard muncul

       ![12](https://user-images.githubusercontent.com/93079538/143210235-d39c8a70-6cb1-45c8-8ea6-fee53aba61fd.png)
       

     - Klik install Now

       ![13](https://user-images.githubusercontent.com/93079538/143207962-8772a6dd-e198-456d-bd08-d1cb1be52681.png)
       

     - Pilih LIsensi Windows Server Datacenter Evolution(Dekstop Experience) lalu "next"

       ![14](https://user-images.githubusercontent.com/93079538/143207964-8434650f-340f-4648-a757-8266a48af754.png)

       ![15](https://user-images.githubusercontent.com/93079538/143207968-37abc0e9-5870-4cc7-aa98-35c4156aa5c9.png)

       ![16](https://user-images.githubusercontent.com/93079538/143210813-1832bab4-9268-4f68-ab3b-83f4bca30896.png)


       ![17](https://user-images.githubusercontent.com/93079538/143207974-9a5c7958-4a89-411f-ac97-974d86f9bac6.png)

       ![18](https://user-images.githubusercontent.com/93079538/143207984-1ccc62f0-373a-42dd-b1af-2c56d4a85165.png)
       

     - Apabila Sudah Ter install sistem akan me reboot ulang otomatis

       ![19](https://user-images.githubusercontent.com/93079538/143207987-a2514682-a515-4f68-9149-30d51c0f0c38.png)
       

     - Klik menu "input keyboard - insert Ctrl-Alt-Del" lalu masukan password anda yang di buat

       ![20](https://user-images.githubusercontent.com/93079538/143211254-fe082298-7d66-4ff1-88ff-35472f5b799a.png)
       

     - Lalu klik menu "Devices-install guest additions CD image" pada VBox 

       ![21](https://user-images.githubusercontent.com/93079538/143207991-c69af355-9f14-4b50-8f09-e9f9524b89be.png)
       

     - Pada "file explorer", run berikut ininkemudian ikuti step nya

       ![22](https://user-images.githubusercontent.com/93079538/143207999-b28e3843-6cb2-43b8-9a5f-77688cd41390.png)

       ![23](https://user-images.githubusercontent.com/93079538/143208005-8592a215-8267-4f9f-9990-f0a059133609.png)

       ![24](https://user-images.githubusercontent.com/93079538/143212009-154161b1-ef99-48fa-a724-bb5a08b2ccf7.png)

       ![25](https://user-images.githubusercontent.com/93079538/143208015-fcd218ee-b55b-4dec-8a68-572651a022ec.png)

       ![26](https://user-images.githubusercontent.com/93079538/143208021-f1f13564-5f18-4f3b-8fe8-6e41c2ecb2b3.png)
       

     - Setelah itu sistem akan me reboot otomatis, lalu masukan lagi password  

       ![27](https://user-images.githubusercontent.com/93079538/143208025-b0ce00ec-a019-417b-898d-52f7e65e7420.png)
       

   - Instalasi Active Directory Domain Service

     - Sebelum Melakukan instalasi lakukan pergantian nama computer dengan masuk ke windows powershell, kemudian ketikan "rename-computer -Newname Server 2022"

       ![newname](https://user-images.githubusercontent.com/93079538/143212529-6f6f8f02-5e82-4c3d-b1e6-4d900d0a3387.png)
       

     - Masuk ke menu "server manager" lalu pilih opsi "manager" dilanjutkan dengan klik "add roles and features". kemudian klik "next"

       ![add roles](https://user-images.githubusercontent.com/93079538/143212823-9342aa06-024e-48ee-a79e-e1a80a81e0d2.png)
       

     - Pilih Opsi "role-based or feture-based instalation" lalu next

       ![add](https://user-images.githubusercontent.com/93079538/143213100-e9f8ed69-c797-4217-99cd-d237554e086a.png)
       

     - klik "Select a server from the server pool" untuk memilih direktori penyimpanan lokal.lalu next

       ![29](https://user-images.githubusercontent.com/93079538/143208045-abd3b5b3-c1ba-45e8-a6d6-989719b037d2.png)
       

     - Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”

       ![30](https://user-images.githubusercontent.com/93079538/143208047-723749ff-ba3d-475e-abb7-dba803b81681.png)
       

     - Kemudian centang kotak “Group Policy Management” dan tekan tombol Next

       ![ass](https://user-images.githubusercontent.com/93079538/143213480-1ed33b80-a423-4585-a79d-6a45b153cbaa.png)
       

     - Klik Next

       ![sas1](https://user-images.githubusercontent.com/93079538/143213956-65b511f4-888a-4896-8c56-06d086fcc213.png)
       

     - Klik "Install" dan tunggu hingga selesai

       ![sas2](https://user-images.githubusercontent.com/93079538/143214125-2fb64d5c-3e5a-4804-9a62-293dc45a814a.png)
       
       

   - Instalasi DNS Server

     - Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama

       ![sas3](https://user-images.githubusercontent.com/93079538/143214352-a35dc9f5-bc2a-40c4-883a-1ea1f5091f4f.png)
       
       

   - Instalasi NET Framework 3.5

     - Centang "NET Framework 3.5 Features"

       ![sas4](https://user-images.githubusercontent.com/93079538/143214734-859b8060-81f1-42eb-a5be-40732fd73478.png)
       

     - Klik Next

       ![sas5](https://user-images.githubusercontent.com/93079538/143215137-624b5185-ddbc-486a-8983-dbeafad116fe.png)
       

     - Lalu Klik Install

       ![sas6](https://user-images.githubusercontent.com/93079538/143216075-8ac50978-ea1b-44a8-9ad5-137ca2088f06.png)
       

     - Lalu Tunggu hingga selesai

       ![sas7](https://user-images.githubusercontent.com/93079538/143216309-74ed0b1d-aea8-49d2-9f06-4e4d5fcacc12.png)
       
       

   - Promote Server to a domain Controller

     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan

     - Seting ke ip static menggunakan cmd, ketik "sconfig" - ketik "1"

       ![31](https://user-images.githubusercontent.com/93079538/143208051-cff38c41-08a6-43d8-ae8a-a2ed4cd3b32d.png)
       

     - Kemudian setting network

       ![32](https://user-images.githubusercontent.com/93079538/143216585-b653dd11-2e5f-45bc-8f20-c6822286994b.png)
       

     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan

       ![40](https://user-images.githubusercontent.com/93079538/143216738-d405db6f-daa0-46d7-a94f-31b3b6f7957c.png)
       

     - Klik “Promote this server to a domain controller" untuk konfigurasi ADDS

       ![sas8](https://user-images.githubusercontent.com/93079538/143217088-00080409-5a1e-4c6c-b0f2-2277d727465c.png)
       

     - Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain "dafa.com"

       ![33](https://user-images.githubusercontent.com/93079538/143208054-dc0428f7-18e4-47d9-87f7-c437bb36ca3d.png)
       

     - Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password

       ![sas9](https://user-images.githubusercontent.com/93079538/143217291-e1bf40a7-8bd1-47c3-9aa3-e803be4862e5.png)
       

     - Lewati bagian DNS Options, lalu klik “Next”

       ![37](https://user-images.githubusercontent.com/93079538/143208062-1c959798-b673-45c6-8ac1-f9d04aa3e85a.png)
       

     - Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan

       ![34](https://user-images.githubusercontent.com/93079538/143208057-a3712ac6-0676-4133-9b03-8b16c210d6a0.png)
       

     - Lewati bagian Paths, klik “Next” 

       ![35](https://user-images.githubusercontent.com/93079538/143208060-e2d140bc-adb1-49d5-b52f-59778546b09c.png)

       

     - Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan

       ![36](https://user-images.githubusercontent.com/93079538/143217685-dd703579-ca9e-4ca7-9314-e9d033ba3947.png)
       

     - Tunggu Instalasi hingga selesai

       ![sas10](https://user-images.githubusercontent.com/93079538/143217937-4ac1cdad-6102-4cec-8493-219e591faf87.png)
       

     - Apabila sudah selesai sistem akan auto reboot, lalu cek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo”

       ![39](https://user-images.githubusercontent.com/93079538/143208065-fc492b3b-ea9f-4cea-9bd9-4697455116eb.png)
       

     - Setelah login dengan Active Directory Domain Controller Anda, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS

       ![40](https://user-images.githubusercontent.com/93079538/143216738-d405db6f-daa0-46d7-a94f-31b3b6f7957c.png)
       

     - Kemudian ubah IP Address sesuai dengan awal tadi

       ![41](https://user-images.githubusercontent.com/93079538/143208068-4d7b542e-dc3c-4994-87ea-3cc67e2a13b7.png)
