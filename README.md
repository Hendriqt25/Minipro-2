# Minipro-2

Nama : Hendri Zaidan Safitra

NIM : 2409116013

Kelas : A

Tema : Sistem Reservasi Hotel

# Flowchart

![Hendri drawio](https://github.com/user-attachments/assets/37f6d876-3d5f-4f06-9141-32377cb2b841)

# Menu Login

![image](https://github.com/user-attachments/assets/cd13a105-5629-482d-9075-4e774d62bb1f)

Pada gambar diatas, user harus memilih sesuai rolenya yaitu ada Admin dan Tamu.

# Penjelasan Menu Login
  1. Admin Untuk Admin bisa melakukan sistem CRUD(Create,Read,Update,Delete) pada database kamar hotel.
  2. Sedangkan Tamu hanya dapat melakukan reservasi, melihat daftar kamar pada kamar hotel yang telah disediakan.
  
  - Seandainya jika user menginputkan angka mode selain 1 dan 2,

![image](https://github.com/user-attachments/assets/37742fba-1951-498a-bc9d-fc0f4b80914e)

jika user menginputkan angka selain 1 dan 2 otomatis akan kembali ke Menu Mode Login.

# Fitur Menu Admin

  ![image](https://github.com/user-attachments/assets/cd0a0647-1ac3-40d1-bc3e-e999ded0c8e2)

Jika user menginputkan angka 1 otomatis langsung ke menu admin Hotel Jatra Balikpapan.

Pada mode admin, Diberikan pilihan 6 Fitur seperti gambar di atas dan di minta untuk menginputkan fitur sesuai dengan angka fitur yang disediakan.

# Penjelasan Fitur Admin
  1. Daftar Kamar

     ![image](https://github.com/user-attachments/assets/1170cf7a-58a8-48d1-9095-dce82fe1426b)

     fitur daftar kamar ini digunakan untuk melihat kamar hotel apa saja yang tersedia. Disaat daftar kamar sudah muncul dalam output otomatis akan looping kembali ke fitur menu admin.

  2. Tambah Kamar

     ![image](https://github.com/user-attachments/assets/6b29b29f-6f8d-49d4-8542-aa0c04bece93)

     Untuk tambah kamar hotel, input angka 2

     ![image](https://github.com/user-attachments/assets/fe8cdc57-facb-49e4-ae60-db8f49abd923)

     Masuk dalam fitur "tambahkan_kamar", terlebih dahulu di tampilkan daftar kamar pada Hotel Jatra Balikpapan.

     Disini admin akan diminta memasukkan/ menginput nomor lantai, nomor kamar, tipe kamar, fasilitas kamar sesuai keinginan admin.

      ![image](https://github.com/user-attachments/assets/9b3533b5-3a37-4e80-ad35-542b584ea3a6)
     
     Tambahan kamar berhasil, masuk ke daftar kamar Hotel Jatra Balikpapan dan output otomatis akan looping kembali ke fitur menu admin.

  3. Update Kamar
     
     ![image](https://github.com/user-attachments/assets/c49d11f3-677d-42e7-b718-372a30fbadfe)

     Pada gambar di atas ini adalah contoh update daftar hotel. Pertama admin menginput nomor kamar kemudian admin bisa mengupdate nomor kamar dengan cara menginputkan     
     nomor kamar baru, tipe kamar baru, dan fasilitas kamar baru.

     ![image](https://github.com/user-attachments/assets/6bbc815a-54ee-437a-ac40-988b1c7879ac)

     dan setelah diubah dan diliat pada daftar kamar otomatis nomor kamar, tipe kamar, fasilitas kamar akan berubah dan output otomatis akan looping kembali ke fitur menu 
     admin.

     -jika admin menginput nomor kamar tidak valid

     ![image](https://github.com/user-attachments/assets/1039f872-6598-4a6f-8327-a411b7e59047)

     jika admin menginputkan nomor kamar yang tidak Valid, menampilkan output dinyatakan gagal, data perubahan/update tadi tidak akan terubah/terupdate pada database     
     tersebut dan output otomatis akan looping kembali ke fitur menu admin.

 4. Hapus kamar

    -Sebelum di Hapus
    
    ![image](https://github.com/user-attachments/assets/8ffea569-6483-4813-bda3-ec524187d547)

    -Sesudah di hapus

    ![image](https://github.com/user-attachments/assets/27867078-0a72-40a2-afed-28e4b625e914)

    Terlihat pada Nomor kamar "404" telah terhapus di daftar kamar saat admin menggunakan fitur Hapus barang.

5. Daftar reservasi
    Admin bisa menlihat jika tidak ada yang reservasi hotel maka:

    ![image](https://github.com/user-attachments/assets/ca12b6ad-4fd8-42f3-9c24-d17e3cc361ab)

    jika ada yang sudah reservasi hotel akan di tampilkan maka:
   
    ![image](https://github.com/user-attachments/assets/d9a067ce-285c-42b4-854f-b952dc5c5111)

6. Keluar atau mulai ke Mode Login

    Jika admin sudah cukup menggunakan fiturnya, admin bisa memilih fitur ke 6 yaitu Keluar atau Mulai ke Mode Login. Disaat memilih admin akan diberikan dua opsi yaitu     
    Keluar yang bisa diartikan langsung keluar exit dari program dan mulai ke Mode Login yang otomatis ketika admin input "Mulai", admin akan diarahkan ke Mode Login lagi.


    ![image](https://github.com/user-attachments/assets/28ff7516-8067-46de-a867-b5d62e80eac8)


    - Jika keluar,

    ![image](https://github.com/user-attachments/assets/1db44936-0897-44ea-9be8-e34b2be6df78)

    - Jika mulai,

    ![image](https://github.com/user-attachments/assets/83bfd736-ea72-4692-831c-cca7f7377438)

# Jika admin input menu admin selain 1-6

![image](https://github.com/user-attachments/assets/8d72fe78-16d4-4e17-a70f-27386aa37576)

Maka outputnya pilihan tidak valid dan otomatis akan looping kembali ke fitur menu tamu.

# Fitur Menu Tamu 

![image](https://github.com/user-attachments/assets/bec8276e-c6b5-4b36-bb21-aa2a50dbfd3c)

Jika user menginputkan angka 2 otomatis langsung ke menu tamu Hotel Jatra Balikpapan.

Pada mode tamu, Diberikan pilihan 4 Fitur seperti gambar di atas dan di minta untuk menginputkan fitur sesuai dengan angka fitur yang disediakan.

# Penjelasan Fitur Tamu
   1. Daftar Kamar

      ![image](https://github.com/user-attachments/assets/1170cf7a-58a8-48d1-9095-dce82fe1426b)

      fitur daftar kamar ini digunakan untuk melihat kamar hotel apa saja yang tersedia. Disaat daftar kamar sudah muncul dalam output otomatis akan looping kembali ke fitur menu tamu.

   2. Buat Reservasi

      Fitur ini dibuat untuk tamu/user yang mau reservasi Hotel Jatra Balikpapan,
      
      Pertama, user terlebih dahulu melihat fitur daftar kamar untuk menentukan/menginput, kemudian input nama,nomor kamar, tanggal reservasi dan pukul reservasi kamar, dengan output sebagai
      berikut.

      ![image](https://github.com/user-attachments/assets/ecb3e9a7-aa38-4c99-b8af-e16e55209e21)

      Jika tamu input nomor kamar yang tidak tersedia,

      ![image](https://github.com/user-attachments/assets/81e3f2dd-caa7-427e-88d9-0c2381ff162b)

      Maka Outputnya "Nomor kamar tidak valid"

      Jika tamu input nomor kamar yang sudah terpesan,

      ![image](https://github.com/user-attachments/assets/276463e0-1b53-4be1-b49c-ae94cb72a6d8)

      Maka outputnya "Nomor Kamar sudah dipesan" dikarenakan nomor kamar 204 udah di reservasi oleh juju,
      dan otomatis akan looping kembali ke fitur menu tamu.

   3. Daftar Reservasi

      Fitur ini dibuat untuk tamu/user yang sudah reservasi dan mengecak apakah sudah reservasi atau belum di Hotel Jatra Balikpapan,

      jika tamu bernama juju, mau mengecek reservasi kamarnya maka,

      ![image](https://github.com/user-attachments/assets/be183cba-1d72-4ac8-9435-0a40fa977aee)

      Terlihat pada tabel bahwa outputnya tamu bernama juju sudah reservasi kamar di Hotel Jatra Balikpapan, dan juga bisa melihat kamar kamar yang sudah direservasi/dipesan.

      jika sebaliknya,

      ![image](https://github.com/user-attachments/assets/c20b7565-e54c-48ba-9b88-c7fba77518fd)

      Maka, Outputnya Tamu bernama juju ini belum reservasi kamar di Hotel Jatra Balikpapan dan otomatis akan looping kembali ke fitur menu tamu.

   4. Keluar atau mulai ke Mode Login
      
      Jika tamu sudah cukup menggunakan fiturnya, tamu bisa memilih fitur ke 4 yaitu Keluar atau Mulai ke Mode Login. Disaat memilih admin akan diberikan dua opsi yaitu     
      Keluar yang bisa diartikan langsung keluar exit dari program dan mulai ke Mode Login yang otomatis ketika admin input "Mulai", tamu akan diarahkan ke Mode Login lagi.

      ![image](https://github.com/user-attachments/assets/f8a3ed4d-a7b8-4f45-9758-16c0ba537a6c)

      Jika mulai,

      ![image](https://github.com/user-attachments/assets/0027f312-8ddc-4bd3-832f-4448e2f6214f)

      jika keluar,
      
      ![image](https://github.com/user-attachments/assets/8da4ea35-717e-4f05-8cc3-5a1f63665690)

# Jika admin input menu tamu selain 1-4

  ![image](https://github.com/user-attachments/assets/d1f830cb-4d33-4d39-b526-31b31c69e9ac)

  Maka outputnya pilihan tidak valid dan otomatis akan looping kembali ke fitur menu tamu.


      


      





    


    



     
     

     


     


     



  





