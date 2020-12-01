
# Laravel-8-Crud instruction


1. Create a Laravel 8 CRUD Application Project.For creating the Laravel 8 application, we will be using the composer. You can use command prompt or terminal for hitting the below command. $ composer create-project --prefer-dist laravel/laravel laravel-8-crud
2. Create and Configure Database For Laravel 8 CRUD.CREATE DATABASE laravel8_crud; . When the database is ready, let’s configure it for the Laravel 8 project. For the database configuration, navigate to the .env file and replace the credentials as showing below.
3. In this CRUD application, I will work on the Article for applying the CRUD operations. So, I will create a model and migration for the Article. php artisan make:model Article --migration .
4. Create a Model and Migration For Article.The migration file for the article has been added inside the database/migrations folder as well.
So, in the create_articles_table migration, we will add some fields.Now, we have the schema for the articles table. Therefore, let’s migrate it inside the database. php artisan migrate .
5. Add Mass Assignment For the Article Model.
6. Create a Controller For the Article. php artisan make:controller ArticleController --resource .
7. Now, for the ArticleController’s functions, we will have to create a resource route. The route will be the type of web. So, add the route in the web.php file.
8. Create Views For the Laravel 8 CRUD Application : 

1). master.blade.php;
2). index.blade.php;
3). create-article.blade.php;
4). show-article.blade.php;
5). edit-article.blade.php;

9. Laravel 8 CRUD Application Result : php artisan serve http://127.0.0.1:8000/articles .
Or clone the repository and edit the .env.example file.

Thanks!
