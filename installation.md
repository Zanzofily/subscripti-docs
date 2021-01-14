# Installation

> Subscribti is laravel-based, your server must have the requirements for laravel 5.8 to get subscripti installed.

## Installation Requirements

- PHP: 7.1.3 or greater
- PDO PHP extension
- JSON PHP extension
- OpenSSL PHP extension
- XML PHP extension
- Mbstring PHP extension
- Ctype PHP extension

## Installation Steps

1. Upload the contents of `subscribti` folder to your application `root` folder
2. Modify `.env` file with your database information
3. Change the jwt encryption token:
   - If you've ssh access to your server run `php artisan jwt:secret`
   - If you don't, modify `JWT_SECRET` in .env file, replacing some of the characters
4. Import `subscripti.sql` file to your data
5. Visit `app_url/manager` and feel free to modify the admin's password

> Documentation will be updated with a command line installation command in the next minor update.
