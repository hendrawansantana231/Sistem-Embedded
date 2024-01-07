# B. Transmisi Data Menggunakan Protokol HTTP

## 1. Keterangan Singkat (Abstrak)
<p align="justify">Percobaan ini dimulai dengan pembuatan database lokal "banjir_db" dan tabel "smartwater" menggunakan phpMyAdmin. Lalu diberikan kode JSON untuk flow program Multi-Protocol IoT Server yang perlu diimport di Node-RED. Selanjutnya, melalui program pada ESP32 dilakukan transmisi data dummy ke Node-Red menggunakan protokol HTTP metode GET dan protokol HTTP metode POST. Output dari percobaan ini berupa hasil dari serial monitor, debugging Node-Red, dan tampilan dashboard Node-RED.
   
## 2. Alat dan Bahan
1. Node-RED
2. ESP32
3. XAMPP

## 3. Source Code
Penjelasan kode untuk Metode Get

![Penjelasan Kode](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/9be9d212-06e8-468c-9b59-da340606c74f)


Penjelasan kode untuk Metode POST

![Penjelasan Kode](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/b666ab56-74a4-4af3-87fc-99a53458c2f9)


## 4. Flow Chart

![Flow Program](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/baa828d5-11a8-4f7f-ae14-edb74b0f5c6a)


## 5. Hasil Percobaan Transmisi Data Dummy Menuju Node-Red Menggunakan Protokol HTTP Metode GET

1. Flow chart program ESP32
   
 ![1  Flow Chart program ESP32](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/25927dfe-a318-475e-a93b-edabae09d869)

   
2. Output serial monitor
   
![2  Output serial monitor](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/60644250-6564-4c1c-9ea7-91d2dbc3530a)

   
3. Debug Node-RED
   
![3  Debug Node-RED](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/ae53a30d-cc3d-45b0-97aa-4bb7ed104079)

4. Dashboard Node-RED
   
![4  Dashboard Node-RED](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/4aa0752f-bbe3-4ba1-b3b7-753fa3c10a0b)

   
5. Tabel database MySQL
   
![5  Tabel database MySQL](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/2d3ddb87-eefd-4b38-96fb-cd07d1ddde89)


## 6. Hasil Percobaan Transmisi Data Dummy Menuju Node-Red Menggunakan Protokol HTTP Metode POST
1. Flow chart program ESP32
   
   ![1  Flow Chart program ESP32](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/47bdbb5b-4c43-4c18-9b80-44661f8fc148)


2. Output serial monitor
   
![2  Output serial monitor](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/5bac1a03-c848-4941-8523-05a2554c849c)

   
3. Debug Node-RED
   
![3  Debug Node-RED](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/7727150e-08d9-46bf-800a-6739ea0ab571)

   
4. Dashboard Node-RED
   
![4  Dashboard Node-RED](https://github.com/hendrawansantana231/Sistem-Embedded/assets/155714822/57cd6fd5-754f-4e84-8ad6-1368d2f64860)


<p align="justify">
<b><p>7. Analisa </p></b>
<p>Kode tersebut mengonfigurasi dan menghubungkan perangkat Arduino ke jaringan WiFi, dan kemudian secara berkala mengirimkan data sensor simulasi melalui HTTP POST request ke server yang ditentukan. Kode ini digunakan untuk mensimulasikan pengiriman data sensor banjir kepada server yang dapat diakses melalui alamat IP tertentu. Jika koneksi WiFi terputus, pesan kesalahan akan ditampilkan di Serial Monitor.</p>
