###### Nama  : christoper felix sanjaya 

###### Kelas : XII RPL 1

###### Absen :20
## modul-3
### routing

>tugas soal nomor 1 buatlah route yang menuju ke halaman kategori 

>tugas soal nomer 2 buatlah halman tambah data di setiap route 

pertama-tama membuat *"class controller"* di vscode ke terminal cara cepat *"ctrl+shift+*" lalu comand dibawah ini 

```
php artisan mak:controller kategoricontroller
```

dibawah ini tugas 1&2 codenya
```

<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class KategoriController extends Controller
{
    public function home ()
    {
   return 'Mengakses fungsi di controller menggunakan route';
}
public function add ()
{
    return 'mengakses halaman tambah data di setiap route kategori controller';
}
}

```

cara melihat hasilnya silahkan mengaktifkan xampp dan cmd 
![image](https://user-images.githubusercontent.com/109930345/183361219-947fe9ea-cafa-4d3b-ae38-d7d8908fd243.png)



setelah mengaktifkan server silahkan menuju ke browser/chrome salin link dibawah ini lalu tempelkan ke browser/ chrome 
```
hhtp//localhost:8000/kategori
```
hasilnya akan terlihat seperti itu

![image](https://user-images.githubusercontent.com/109930345/183361458-18dbb357-819a-42ca-845c-ba04a87e1d35.png)

![image](https://user-images.githubusercontent.com/109930345/183361521-ac854285-fada-4fd2-854e-1f656c9b8542.png)



