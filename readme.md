# Laravel Web Installer with oracle option | A Web Installer [Package](https://packagist.org/packages/rachidlaasri/laravel-installer)

Forked from [Rashid Laarsi](https://github.com/rashidlaasri/LaravelInstaller), whose project has

[![Total Downloads](https://poser.pugx.org/rachidlaasri/laravel-installer/d/total.svg)](https://packagist.org/packages/rachidlaasri/laravel-installer)
[![Latest Stable Version](https://poser.pugx.org/rachidlaasri/laravel-installer/v/stable.svg)](https://packagist.org/packages/rachidlaasri/laravel-installer)
[![License](https://poser.pugx.org/rachidlaasri/laravel-installer/license.svg)](https://packagist.org/packages/rachidlaasri/laravel-installer)

- Added 'oracle' as selectable option.

##Additional setup instructions

Add this to your composer.json:<br>

`"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/tloader11/LaravelInstaller"
        }
    ]`
<br>
next, use: <br>
    `composer require rachidlaasri/laravel-installer:4.0.3`
<br>
this version currently overrides the latest stable release and thus gives you the oracle option.
<br>Then use:<br>

`php artisan vendor:publish --tag=laravelinstaller`


##Please refer to his github for detailed setup instructions

[rashidlaasri/LaravelInstaller](https://github.com/rashidlaasri/LaravelInstaller)

## License

Laravel Web Installer is licensed under the MIT license. Enjoy!

