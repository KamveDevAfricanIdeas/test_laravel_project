<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

> using this project to test Laravel features and capability.
# My Notes
---
## 1. Frontened
> We have 2 options
- [ ] PHP & Blade. Which is HTML with PHP echoes
- [ ] Vue or React (JS)
- Blade templates are located in the `resources/views` directory
- Modify the `welcome.blade.php` file to customize your homepage
- Add bootstrap via: `<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">`
> Integrate Javascript
- place custom JavaScript files in `public/js/`
and reference them in your Blade files e.g
 `<script src="{{ asset('js/app.js') }}"></script>`
## Backend
> Setting up
- Create a project `composer create-project --prefer-dist laravel/laravel project_name`
- Configure db info, first set up your mysql database and go to .env file to change DB_* info to your settings
- In php, in the php.ini file configure extension_* lines related to mysql by uncommenting (remove ';')
- Now back in cmd, run `php artisan migrate`, if you want a session database
- Now run `php artisan session:table` to check if the table exists.
- Start the server `php artisan server`, everything should be running.
