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
![Screenshot (4)](https://user-images.githubusercontent.com/109930345/182274234-f9d6064e-9a10-4747-991a-656741dd83e2.png)








setelah mengaktifkan server silahkan menuju ke browser/chrome salin link dibawah ini lalu tempelkan ke browser/ chrome 
```
hhtp//localhost:8000/kategori
```
hasilnya akan terlihat seperti itu



