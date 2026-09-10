# Identitas

Nama: I Gusti Agung Bagaskara
NIM: 260530911041
Kategori CTF: Web

# Tools Yang Berhasil Di instalasi:
WSL:
  Ubuntu
Git
GitHub
Python

# Proses Instalasi WSL:

1. Jalankan Powershell Sebagai Administrasi Dan Jalankan command

      ``wsl --install``

   Ini Bakal Menginstall Distro Ubuntu Linux.
   


Proses Instalasi Git
1. Install Git pada Website
   https://git-scm.com/install/
   Berdasarkan Sistem Yang Dimiliki
   <img width="1920" height="1080" alt="Website Instalasi Git(1)" src="https://github.com/user-attachments/assets/e31f13be-e7cb-4680-94aa-023efcf06cd6" />

3. Tekan "Install"
4. Selesai



Proses Instalasi GitHub:
1. Install Github pada Website
   https://desktop.github.com/download/
   <img width="1920" height="1080" alt="Screenshot 2026-09-10 225003" src="https://github.com/user-attachments/assets/48c93224-16e9-42cc-b93f-6f756e875ebd" />

3. Login Pada Aplikasi GitHub <img width="1197" height="827" alt="GitHub Start(1)" src="https://github.com/user-attachments/assets/0276bc26-0208-4a52-af63-2e152f781bf5" />

4. Selesai
   <img width="1196" height="818" alt="GitHub Done(2)" src="https://github.com/user-attachments/assets/d16a4fe9-a996-4aad-bdef-e294d4ff8d45" />

# Pengujian

1. Pengujian WSL
   <img width="1920" height="1080" alt="Ubuntu CLI Folder   File Creation" src="https://github.com/user-attachments/assets/8ebc593a-1722-45dd-b1a8-e175aa14dc3d" />

2. Pengujian Python
   2.1 Melalui File Yang Sudah Dibuat
   <img width="1920" height="1080" alt="PY Testing With Pre Existing File" src="https://github.com/user-attachments/assets/ec11818f-005e-46cd-ab19-37e92955eb4b" />

   2.2 Melalui CLI Saja
   <img width="1920" height="1080" alt="PY Test With 1 Line" src="https://github.com/user-attachments/assets/62e20b37-4634-4b00-b42f-3a7d97675030" />
   
# Challenge
1. Undo

step 1:
saya memulai challange nya dan melihat hint yang berada di CLI saya kemudian mencari di google cara men *decode* base64 pada linux CLI dan menemukan bahwa bisa menggunakan command "base64 -d"
<img width="1472" height="753" alt="Undo(1)" src="https://github.com/user-attachments/assets/e7a232b7-8b7b-4dc1-9160-2b0ee89e74aa" />
<img width="1920" height="1080" alt="Mencari Cara(2)" src="https://github.com/user-attachments/assets/9adb7f01-b627-4498-8bc0-d7ca99123140" />

step 2:
sama seperti sebelumya saya melihat hint yang berada pada CLI saya dan kemudian mencari di google untuk cara *reverse* sebuah text pada linux CLI dan ternyata dapat dilakukan dengan command "rev"
<img width="1468" height="748" alt="Part2(3)" src="https://github.com/user-attachments/assets/eb7c97e0-991f-4c4d-a90a-21d6d333f297" />
<img width="1920" height="1080" alt="Mencari Reverse (4)" src="https://github.com/user-attachments/assets/c5775b26-bc55-4fc9-aaf3-70e54f4e5bbd" />



step 3:
Saya pun melihat clue nya lagi dan seperti biasa, mencari cari bagaimana cara menggantikan *Underscore* dengan *dash*
<img width="1472" height="756" alt="Part3(5)" src="https://github.com/user-attachments/assets/b18a38f9-760d-48c5-abdd-389986a3bb7c" />
<img width="1920" height="1080" alt="Salah Command(6)" src="https://github.com/user-attachments/assets/5a0c74be-c523-4c0d-9a06-64be9901a814" />

Saya pun mencoba memakai command yang diberikan pada sebuah website tapi ternyata command nya salah, karena sudah diberikan commandnya pada cluenya saya pun menggunakan command yang diberikan pada clue nya

step 4:
saya melihat untuk step 4 mirip dengan step 3 saya pun mencoba memakai command pada step 3 tetapi diubah dan berhasil
<img width="1476" height="756" alt="Iseng Coba Command Lagi(7)" src="https://github.com/user-attachments/assets/92b639f1-b927-4887-bb3d-9d7cb85a4a0c" />

step 5:
seperti biasa saya melihat clue bahwa kode tersebut telah di enkripsikan dengan rot13 jadi saya mencari cara untuk men decrpty kode tersebut
<img width="1920" height="1080" alt="Cari Decrypt(8)" src="https://github.com/user-attachments/assets/c150899e-c49b-4cce-854d-bb8e4311f918" />

namun ternyata penulisan format yang di google salah dan saya pun menggunakan clue yang di berikan dan selesai
<img width="1471" height="751" alt="Salah Penulisan (9)" src="https://github.com/user-attachments/assets/b02b803b-fcd6-422c-8995-e87823390d52" />
<img width="1475" height="752" alt="Selesai(10)" src="https://github.com/user-attachments/assets/50451091-68df-48fe-950b-40433957623b" />

# Web
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e24d30a2-b6af-4f44-b222-7ad41d7969d3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d990ae19-c042-4421-bf77-d5079a50201f" />


