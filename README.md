# lab11Web
# LANGKAH PRAKTIKUM

Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian
Apache klik Config -> PHP.ini
Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan
diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.
![image](https://user-images.githubusercontent.com/101730390/172670786-4c780de4-4e10-4045-9fd5-2a4fe407c7a7.png)

Instalasi Codeigniter 4
Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara
manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara
manual.
![image](https://user-images.githubusercontent.com/101730390/172670910-2266994a-bb46-4da1-acfe-ddc87c298951.png)

Menjalankan CLI (Command Line Interface)
Codeigniter 4 menyediakan CLI untuk mempermudah proses development. Untuk
mengakses CLI buka terminal/command prompt.
![image](https://user-images.githubusercontent.com/101730390/172671312-8a8abbd2-1f88-4634-97d0-9883e49c81ed.png)
![image](https://user-images.githubusercontent.com/101730390/172671473-2bffffa7-c9f4-49aa-a102-7224feeb86f8.png)

Mengaktifkan Mode Debugging
Codeigniter 4 menyediakan fitur debugging untuk memudahkan developer untuk
mengetahui pesan error apabila terjadi kesalahan dalam membuat kode program.
Secara default fitur ini belum aktif. Ketika terjadi error pada aplikasi akan ditampilkan
pesan kesalahan seperti berikut.
![image](https://user-images.githubusercontent.com/101730390/172673541-64cad38e-7c68-48a2-a3ad-83f9807ec762.png)

Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable
CI_ENVIRINMENT menjadi development.
![image](https://user-images.githubusercontent.com/101730390/172673849-1fcaae84-cdf3-4be9-ae52-fbb45ac3cc6b.png)
![image](https://user-images.githubusercontent.com/101730390/172674252-38e1abab-3bd4-4915-8cb5-740d43c7f68e.png)

Contoh error yang terjadi. Untuk mencoba error tersebut, ubah kode pada file
app/Controller/Home.php hilangkan titik koma pada akhir kode.
![image](https://user-images.githubusercontent.com/101730390/172674422-b13646b2-de71-42b5-82e6-6dc4aaeda403.png)

Membuat Route Baru.
Tambahkan kode berikut di dalam Routes.php
![image](https://user-images.githubusercontent.com/101730390/172675043-4632229d-bdbd-4472-8187-d37e895241c3.png)

Untuk mengetahui route yang ditambahkan sudah benar, buka CLI dan jalankan
perintah berikut.
![image](https://user-images.githubusercontent.com/101730390/172675266-1ac97bf5-99fc-4bda-8f75-8f4d7a691b24.png)
![image](https://user-images.githubusercontent.com/101730390/174103202-a9d9d180-3b1a-487a-80d7-a0d975132b77.png)


Membuat Controller
Selanjutnya adalah membuat Controller Page. Buat file baru dengan nama page.php
pada direktori Controller kemudian isi kodenya seperti berikut.
![image](https://user-images.githubusercontent.com/101730390/172676272-0f928042-8608-43ab-9810-8071a333241a.png)
![image](https://user-images.githubusercontent.com/101730390/172676436-768703e6-a6bc-43a4-b1f0-ad0ebf253a82.png)

Auto Routing
Secara default fitur autoroute pada Codeiginiter sudah aktif. Untuk mengubah status
autoroute dapat mengubah nilai variabelnya. Untuk menonaktifkan ubah nilai true
menjadi false.
![image](https://user-images.githubusercontent.com/101730390/172677035-15511078-6ae7-4484-aa9a-4a3241297a7a.png)
![image](https://user-images.githubusercontent.com/101730390/172677507-8a56c166-fa7c-411f-b30a-6df695edc06e.png)
![image](https://user-images.githubusercontent.com/101730390/174104625-940cfa0a-481f-45db-a32e-8a2bbff1809b.png)


Membuat View
Selanjutnya adalam membuat view untuk tampilan web agar lebih menarik. Buat file
baru dengan nama about.php pada direktori view (app/view/about.php) kemudian isi
kodenya seperti berikut.
![image](https://user-images.githubusercontent.com/101730390/172678741-c15c51d5-2530-4bb8-a107-a2660267f279.png)

Ubah method about pada class Controller Page menjadi seperti berikut:
![image](https://user-images.githubusercontent.com/101730390/172678818-0e8101b3-f817-41b6-a482-bd98c573822f.png)

![image](https://user-images.githubusercontent.com/101730390/172678857-ab551e95-5a06-4e04-aafa-3445201f9695.png)

Kemudian buat folder template pada direktori view kemudian buat file header.php dan
footer.php
![image](https://user-images.githubusercontent.com/101730390/172680282-3703ba37-683f-4887-a525-8714e68cd68b.png)
![image](https://user-images.githubusercontent.com/101730390/172680337-e5518d78-472e-484e-9fcc-1890df9a2680.png)
![image](https://user-images.githubusercontent.com/101730390/172680460-d1a04d9d-5fb2-4a58-811e-a095b83b3ea1.png)

![0](https://user-images.githubusercontent.com/101730390/172699382-7bd04d14-4217-4548-82e7-c8812bfd8d91.jpeg)

# PRAKTIKUM 12
Membuat Database dan Tabel
![image](https://user-images.githubusercontent.com/101730390/174098665-25b2b1b1-ab92-42b2-aa04-740b933427cb.png)




Membuat konfigurasi untuk menghubungkan dengan database server melalui file .env
![image](https://user-images.githubusercontent.com/101730390/174098940-f42bd5c2-b748-4ef1-b46e-1b9db1f689a2.png)


Membuat file baru dengan nama ArtikelModel.php
![image](https://user-images.githubusercontent.com/101730390/174099211-735a57be-92c1-4441-88d0-bf018a7d3c70.png)


Membuat file baru dengan nama Artikel.php
![image](https://user-images.githubusercontent.com/101730390/174099390-c4c66fba-f4f0-4d87-a002-321d7dac2110.png)

Membuat file baru dengan nama index.php
![image](https://user-images.githubusercontent.com/101730390/174099863-9605e522-2397-4517-b38b-ed9b25e99df5.png)


Cek hasil coodingan melalui link URL : http://localhost:8080/artikel
![image](https://user-images.githubusercontent.com/101730390/174331346-509b8336-259e-4059-aec7-93e88f097899.png)


mambahkan beberapa data pada database dan cek hasil nya
![image](https://user-images.githubusercontent.com/101730390/174105629-73e33aad-a0f3-46c3-98f9-3f4f8b624a98.png)


![image](https://user-images.githubusercontent.com/101730390/174331430-48112625-0d59-4696-8fe9-aace55001b91.png)


Tambahkan fungsi baru pada Controller Artikel dengan nama view().
![image](https://user-images.githubusercontent.com/101730390/174331875-6213da62-984c-48ac-93dc-897cc5f6302c.png)


Membuat file baru dengan nama detail.php
![image](https://user-images.githubusercontent.com/101730390/174332441-aed11e91-df74-46fa-92d8-ff504f6ea81f.png)


Tambahkan routing untuk artikel detail
![image](https://user-images.githubusercontent.com/101730390/174332472-f28212a2-3f2e-46b8-9b96-ff6b077f9e14.png)


Cek hasil coodingan melalui link URL : http://localhost:8080/artikel/artikel-kedua
![image](https://user-images.githubusercontent.com/101730390/174332577-356cbb4b-ff67-49b0-b359-7e91392c30c8.png)


Buat method baru pada Controller Artikel dengan nama admin_index()
![image](https://user-images.githubusercontent.com/101730390/174332786-2d9d6219-7ea8-4930-a22f-39eb71b4b1b6.png)


Membuat file baru dengan nama admin_index.php
![image](https://user-images.githubusercontent.com/101730390/174333268-4793e100-f600-42c3-b232-d14d99f61b05.png)


![image](https://user-images.githubusercontent.com/101730390/174333344-8a0f7985-73ae-46cc-b02d-d941cf7b53bd.png)


Membuat file baru dengan nama admin_header.php
![image](https://user-images.githubusercontent.com/101730390/174334550-2f954de5-92dc-4e4e-8589-e37c0f518c90.png)


Membuat file baru dengan nama admin_footer.php
![image](https://user-images.githubusercontent.com/101730390/174334589-7403e854-be0c-4090-8a4b-071ad3d7242d.png)


Tambahkan routing untuk menu admin
![image](https://user-images.githubusercontent.com/101730390/174333980-b6c1ca17-0918-49ad-961b-ceb0ac75840e.png)


Cek hasil coodingan melalui link URL : http://localhost:8080/admin/artikel
![image](https://user-images.githubusercontent.com/101730390/174334755-5637695d-00aa-4db1-bb20-5b5e505e9611.png)


Tambahkan fungsi/method baru pada Controller Artikel dengan nama add()
![image](https://user-images.githubusercontent.com/101730390/174334859-1f272690-a095-4779-bd2a-91f9852026b2.png)


Membuat file baru dengan nama form_add.php
![image](https://user-images.githubusercontent.com/101730390/174335131-b1e4e129-71d5-4e28-bac1-4402820339a4.png)


Cek hasil coodingan melalui link URL : form_add.php
![image](https://user-images.githubusercontent.com/101730390/174335215-7ad91f48-3fa1-4b10-b98d-3084088784c2.png)


Tambahkan fungsi/method baru pada Controller Artikel dengan nama edit()
![image](https://user-images.githubusercontent.com/101730390/174335438-df633717-1577-4744-aa0e-b722a9eb56d7.png)


Kemudian buat view untuk form tambah dengan nama form_edit.php
![image](https://user-images.githubusercontent.com/101730390/174335674-cd6368da-fc43-4ec9-b46f-510257346583.png)


Cek hasil coodingan melalui link URL : http://localhost:8080/admin/artikel/edit/1
![image](https://user-images.githubusercontent.com/101730390/174335768-38913d99-62d9-452b-a334-ba41cb868d46.png)


Tambahkan fungsi/method baru pada Controller Artikel dengan nama delete()
![image](https://user-images.githubusercontent.com/101730390/174335875-2263ccfe-0364-45e5-8278-3458d0b55d71.png)

# PRAKTIKUM 13
Membuat Tabel User
![image](https://user-images.githubusercontent.com/101730390/174476199-0f8de458-be73-4c3b-bc89-03e39961f75d.png)

Membuat Model User
Selanjutnya adalah membuat Model untuk memproses data Login. Buat file baru pada
direktori app/Models dengan nama UserModel.php
![image](https://user-images.githubusercontent.com/101730390/174476537-24c7dff9-9b09-43b4-9a7a-902b8fe9fd28.png)


Membuat Controller User
Buat Controller baru dengan nama User.php pada direktori app/Controllers.
Kemudian tambahkan method index() untuk menampilkan daftar user, dan method
login() untuk proses login.
![image](https://user-images.githubusercontent.com/101730390/174476695-7b733a7c-e9f9-4e0a-8d53-554312043177.png)

![image](https://user-images.githubusercontent.com/101730390/174476702-798d54e3-0c5f-417c-b13c-12486cd9b06b.png)


Membuat View Login
Buat direktori baru dengan nama user pada direktori app/views, kemudian buat file
baru dengan nama login.php.
![image](https://user-images.githubusercontent.com/101730390/174490559-04c6a7fb-480f-464d-af1f-aa2feb73c539.png)
![image](https://user-images.githubusercontent.com/101730390/174490580-1228096a-2159-4ee0-a9b9-488840dff17d.png)



Membuat Database Seeder
Database seeder digunakan untuk membuat data dummy. Untuk keperluan ujicoba modul
login, kita perlu memasukkan data user dan password kedaalam database. Untuk itu buat
database seeder untuk tabel user. Buka CLI, kemudian tulis perintah berikut:
![image](https://user-images.githubusercontent.com/101730390/174490268-9dd4dc11-7ad5-4af3-8079-6ea8c145d1f0.png)

Selanjutnya, buka file UserSeeder.php yang berada di lokasi direktori
/app/Database/Seeds/UserSeeder.php kemudian isi dengan kode berikut:
![image](https://user-images.githubusercontent.com/101730390/174490302-10c4a4e5-df74-478e-8f7c-64a6935cd375.png)

Selanjutnya buka kembali CLI dan ketik perintah berikut:
![image](https://user-images.githubusercontent.com/101730390/174490370-d9a5d725-da1a-4c6d-8d3a-d7d2e34c277a.png)

Selanjutnya buka url http://localhost:8080/user/login seperti berikut:
![image](https://user-images.githubusercontent.com/101730390/174490396-aac48416-1d05-4fff-8f1c-9b801a24a8dc.png)

Menambahkan Auth Filter
Selanjutnya membuat filer untuk halaman admin. Buat file baru dengan nama Auth.php
pada direktori app/Filters.
![image](https://user-images.githubusercontent.com/101730390/174490416-c504fba6-32dc-47a1-9767-568466c75744.png)

Selanjutnya buka file app/Config/Filters.php tambahkan kode berikut:
![image](https://user-images.githubusercontent.com/101730390/174490449-7b43e73f-85e8-4557-b21d-887b14cf8be9.png)

Selanjutnya buka file app/Config/Routes.php dan sesuaikan kodenya.
![image](https://user-images.githubusercontent.com/101730390/174490482-5ef2ada7-df15-416e-ad5a-85dc2e72e4d2.png)

Uji Coba Login
Selanjutnya buka url http://localhost:8080/user/login seperti berikut:
![image](https://user-images.githubusercontent.com/101730390/175334489-d8d9227c-5fde-4e5a-98ec-bb1fe27d41f8.png)

Fungsi Logout
Tambahkan method logout pada Controller User seperti berikut:
![image](https://user-images.githubusercontent.com/101730390/175335143-54d341cd-a909-44c2-91c5-d86c5e5d8e89.png)

hasil browsernya :
![image](https://user-images.githubusercontent.com/101730390/175339813-81b17a1f-999e-45f7-bef7-024d7ccd4e65.png)
