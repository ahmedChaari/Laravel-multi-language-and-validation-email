<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Project 

# Laravel project web for three things : 
# --the first for register with recaptcha V2 
# --the second for validation compte with email address
# --the third translate all project with three language (French , Arabic, English)



## configuration Laravel

if you need to use it, copy env.example and configure.

### SMTP configuration

MAIL_MAILER=smtp </br>
MAIL_HOST=XXXXXXXXXXX </br>
MAIL_PORT=587
MAIL_USERNAME=xxxx.@email.com
MAIL_PASSWORD=password
MAIL_ENCRYPTION=tls
MAIL_FROM_ADDRESS=contact@email.com
MAIL_FROM_NAME="${APP_NAME}"

### recaptcha configuration

RECAPTCHA_SITE_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxx
RECAPTCHA_SECRET_KEY=xxxxxxxxxxxxxxxxxxxxxxxx

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
