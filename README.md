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
![image](https://user-images.githubusercontent.com/101730390/172675847-40f26bf2-bdff-4977-a561-e35b6e823f98.png)

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
![image](https://user-images.githubusercontent.com/101730390/172677645-b6f7b6e3-d1e2-43e5-8572-63b1d39acf48.png)

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

