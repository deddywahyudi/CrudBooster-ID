# CrudBooster-ID
Language ID Indonesia CrudBooster

Localization merupakan fitur CRUDBooster apabila anda ingin mengubah bahasa CRUDBooster.
Secara default CRUDBooster masih menggunakan bahasa inggris.

Anda pun dapat menambahkan bahasa anda sendiri dengan membuat file pada : 
Anda bisa membuat folder misalkan id (di dalam folder lang) , kemudian copy dan paste file crudbooster.php . 
Anda tinggal mengganti semua bahasa inggris ke bahasa yang anda kehendaki.
Kemudian jangan lupa untuk mengubah locale pada pengaturan di file app.php sesuai dengan nama folder yang baru saja anda buat.

Setelah perubahan diatas jalankan :
php artisan key:generate
php artisan config:cache

Untuk menghapus cache yang tertinggal, sehingga anda bisa melihat perubahan.
