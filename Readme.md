# **Database Management Final Exam: Movie App**
* 1207050034 - Faizal Ramadhan
* 1207050028 - Difa Fauzan 
* 1207050137 - Jessy Faujiyyah Khairani

![image](https://user-images.githubusercontent.com/69755016/209465534-498c0cc9-a27c-4708-8544-5cf0e1af2427.png)

## **Setup**
1. Kunjungi situs Firebase di console.firebase.google.com
2. Membuat projek baru dengan meng-klik tombol add project
![image](https://user-images.githubusercontent.com/69755016/209465712-9b072812-249e-4202-8da1-4247f8f03026.png)
3. Masukkan nama projek sesuai kebutuhan
![image](https://user-images.githubusercontent.com/69755016/209465740-e98fb074-872f-4080-8738-f94cad0cd61e.png)
4. Pilih opsi penggunaan google analytics (opsional)
![image](https://user-images.githubusercontent.com/69755016/209465762-c980f989-421b-48b0-bdc3-58bb05e8905c.png)
5. Tunggu sampai proses pembuatan projek selesai
![image](https://user-images.githubusercontent.com/69755016/209465845-04898264-0c90-4551-bb65-1f4e5fcb0f34.png)
6. Setelah projek selesai dibuat, siapkan database firestore-nya terlebih dahulu. Pilih menu Build > Firestore Database di sidebar
![image](https://user-images.githubusercontent.com/69755016/209465875-e7a7d77e-aa1e-450a-8622-a7a905edce42.png)
7. Setelah memasuki halaman firestore, buat database baru dengan cara klik tombol create database
![image](https://user-images.githubusercontent.com/69755016/209465887-2e0953c0-2ee0-4c1d-9d9c-90248e99ec87.png)
8. Pilih opsi database yang sesuai dengan kebutuhan kita, jika sudah klik tombol biru di sudut kanan bawah pop-up\
![image](https://user-images.githubusercontent.com/69755016/209465896-97732d30-efe9-4c14-8bc2-4a6c233b1fb2.png)
9. Setelah itu, akan dibuat database firestore yang nantinya bisa memuat collections, documents, dan fields yang kita butuhkan. Database sudah siap digunakan
![image](https://user-images.githubusercontent.com/69755016/209465909-30687218-a506-42c9-a9fb-8ee6909c83cd.png)

## **Konfigurasi di Aplikasi**
1. Buka project overview di console firebase, pilih icon web sesuai yang ada pada gambar berikut
![image](https://user-images.githubusercontent.com/69755016/209466150-c017e611-5bb4-415e-8b0e-b18994748841.png)

2. Masukkan nama aplikasi, lalu klik register app

![image](https://user-images.githubusercontent.com/69755016/209466204-614849a3-8410-4244-a1cb-3e4bd4d89aa5.png)

3. Klik tombol continue to console di bagian bawah page
![image](https://user-images.githubusercontent.com/69755016/209466226-003fe670-251a-4c4e-9038-69cf0f19a166.png)

4. Kembali ke halaman project overview, lalu pilih klik tulisan 1 apps dan pilih app yang baru kita buat
![image](https://user-images.githubusercontent.com/69755016/209466263-22f721d0-8946-491f-91c2-8590fd294dd4.png)

5. Pada toolbar, pilih menu Service Accounts
![image](https://user-images.githubusercontent.com/69755016/209466389-f21304db-af61-48d7-87da-23c60b1045a1.png)

6. Setelah masuk ke menu service accounts, klik tombol generate new private key
![image](https://user-images.githubusercontent.com/69755016/209466417-3bbd287d-4191-4d33-a348-0ff6457e2dc9.png)

7. Secara otomatis akan terdownload private key baru. Setelah download selesai, buka file json tersebut menggunakan code editor pilihan, dan copy semua baris code didalamnya

8. Clone repositori ini, lalu masuk ke folder Firestore

![image](https://user-images.githubusercontent.com/69755016/209465940-b0ff8bee-aba7-4aa6-9427-ed0b9528c203.png)

9. Buka file creds.js, lalu replace semua yang ada di dalam file tersebut menggunakan private key baru kita

10. Simpan perubahan pada file tersebut, lalu buka folder firestore menggunakan terminal, lalu masukkan kode node server.js

11. Tunggu sampai proses serve berjalan dengan baik, lalu buka aplikasi demo-nya di http://localhost:5002