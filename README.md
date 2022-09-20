# Laravel Role Permissions - Laravel  `9.x`

A project which manage Role, Permissions and every actions of your Laravel application. A complete solution for Role based Access Control in Laravel.


```
Email - superadmin@example.com
Password - 12345678
```

- Laravel `9.7` & PHP - `8.x`


## Project Setup
Git clone -
```console
git clone https://github.com/khalidzaibi/laravel-role-permissions.git
```

Go to project folder -
```console
cd laravel-roles-permissions
```

Install Laravel Dependencies -
```console
composer install
```

Create database called - `laravel_role`

Create `.env` file by copying `.env.example` file
```console
cp .env.example .env
```

Generate Artisan Key (If needed) -
```console
php artisan key:generate
```

Migrate Database with seeder -
```console
php artisan migrate --seed
```

Run Project -
```php
php artisan serve
```

Since, there is any problem to seeder, Please import the .sql file directly - https://github.com/khalidzaibi/laravel-role-permissions/blob/main/database/sql/roles_permission.sql

So, You've got the project of Laravel Role & Permission Management on your http://localhost:8000

## How it works
1. Login using Super Admin Credential -
    1. Email - `superadmin@example.com`
    1. Password - `12345678`
2. Create Admin
3. Create Role
4. Assign Permission to Roles
5. Assign Multiple Role to an admin
6. Check by login with the new credentials.
7. If you've not enough permission to do any task, you'll get a warning message.

