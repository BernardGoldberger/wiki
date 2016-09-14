# Installation

### Steps
 1. `CD` to the directory where you want to install Koel.
 2. Run `git clone https://github.com/phanan/koel.git`, this will create a new sub-dir with the Koel repository in it.
 3. Run `git checkout v3.3.1`, [click here](https://github.com/phanan/koel/releases) for the latest version.
 4. Run `composer install`.
 5. Now its time to setup the `.ENV` file in the root folder, if there isn't one create it.
    > the following are the minimum settings required.
```
    DB_CONNECTION
    DB_HOST
    DB_DATABASE
    DB_USERNAME
    DB_PASSWORD
    ADMIN_EMAIL
    ADMIN_NAME
    ADMIN_PASSWORD
```
 6. Run `php artisan koel:init`, this will init your Koel instance, install npm dependency packages and gulp.

Hopefully you ran into no errors, if so, you can now go ahead and Sync your music library :+1:.
