# Laporan Modul 1 dan 2 Praktek Basis Data
#### Catatan : Saya membuat ini waktu saya tidak masuk sekolah karena sakit, dan saya tidak ingin ketinggalan praktek database pak veri

#### Nama : Muhammad Rafi Hidayatulloh
#### Kelas : XI RPL 2
#### Absen : 07

>## MODUL 1

### 1.Install Xampp terlebih dahulu

![image](https://user-images.githubusercontent.com/113582977/190355941-0e429bbf-6c6a-439c-9e22-34ef096e36a0.png)



### 2.aktifkan mysql di xampp

![image](https://user-images.githubusercontent.com/92255670/190300828-bc545470-06b3-49e6-86c7-2a8d147eab8f.png)

### 3.kemudian masuk ke command prompt 

![image](https://user-images.githubusercontent.com/92255670/190300950-b3c6cf63-dc30-454a-88ea-089139b4a69b.png)

- ### Cara membuat title

```
title nama_kaliam
```
![image](https://user-images.githubusercontent.com/113582977/190356554-b7d533f8-6bf0-4b44-97d6-a6ea82dc81df.png)


### 4.Masuk direktori Mysql 

```
cd xampp/mysql/bin
```

![image](https://user-images.githubusercontent.com/92255670/190303407-b4246b76-6ec3-4c79-af39-114aecb26db5.png)

### 5.ketik syntaks berikut untuk masuk ke MariaDB
```
mysql -u root
```

![image](https://user-images.githubusercontent.com/92255670/190308626-753b3710-6ba3-4ce7-8e66-224a08e8780a.png)

**Di atas sudah bisa menuliskan query**



>## Modul 2
- ### Cara melihat daftar database
```
show databases;
```
![image](https://user-images.githubusercontent.com/113582977/190355635-15aa6682-185a-4035-9716-092a691f4130.png)


- ### Cara memilih database
```
use database nama_database;
```
![image](https://user-images.githubusercontent.com/113582977/190355012-48732507-69c1-4ac4-ac7a-ab28728a86fc.png)

- ### Cara membuat database
```
create database nama_database;
```
![image](https://user-images.githubusercontent.com/113582977/190356895-abe957cd-f7a6-4622-b523-3ee23c662a49.png)

- ### Cara membuat table
```
create table name_table(nama varchar(50)not null,no int(3)not null);
```

![image](https://user-images.githubusercontent.com/92255670/190313876-73124c48-987b-467d-b775-a94d8cd51a73.png)

- ### Cara melihat daftar table
```
show tables;
```
![image](https://user-images.githubusercontent.com/113582977/190357126-643ada14-b06e-4672-9aea-c447f1aadc3f.png)

- ### Cara melihat isi (struktur) di sebuah tabel

```
desc name_table;
```

![image](https://user-images.githubusercontent.com/113582977/190357198-664d6d3c-dcd4-4fee-9af9-65cf12490e17.png)



                                                           ## Selesai       
