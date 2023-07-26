# Cara Instalasi

1. `git clone https://github.com/NUISugeng/Mading-JEWEPE.git`
2. `cd Mading-JEWEPE`
3. `composer update`
4. Buat database di MySQL
5. `cp .env.example .env`
6. Ubah file `.env`

```
DB_HOST=127.0.0.1
DB_DATABASE=lara_blog
DB_USERNAME=root
DB_PASSWORD=
```

7. `php artisan migrate`
8. `php artisan db:seed --class=UserTableSeeder`
9. `php artisan key:generate`
10. `php artisan serve`