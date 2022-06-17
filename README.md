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

