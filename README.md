# Demo for [Laravel Eloquent vs Collection Count](https://patriqueouimet.ca/tip/eloquent-vs-collection-count)

How to install the demo application

```
git clone https://github.com/patoui/laravel-eloquent-vs-collection-count.git
cd laravel-eloquent-vs-collection-count
composer install
touch database/database.sqlite
php artisan migrate
php artisan serve
```

Then visit these two and see the difference in the debugbar console

- [http://127.0.0.1:8000/collection](http://127.0.0.1:8000/collection)
- [http://127.0.0.1:8000/eloquent](http://127.0.0.1:8000/eloquent)
