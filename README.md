Vökuró
======

Phalcon is a web framework delivered as a C extension providing high performance and lower resource consumption.

This is a sample application for the Phalcon Framework. We expect to implement as many features as possible to showcase the framework and its potential.

Please write us if you have any feedback.

Thanks.

NOTE
----
The master branch will always contain the latest stable version. If you wish to check older versions or newer ones currently under development, please switch to the relevant branch.

Get Started
-----------

#### Requirements

To run this application on your machine, you need at least:

* >= PHP 5.5
* >= Phalcon 3.0
* Apache Web Server with `mod_rewrite enabled`, and `AllowOverride Options` (or `All`) in your `httpd.conf` or Nginx Web Server
* Latest Phalcon Framework extension installed/enabled
* MySQL >= 5.1.5

Then you'll need to create the database and initialize schema:

    echo 'CREATE DATABASE vokuro' | mysql -u root
    cat schemas/vokuro.sql | mysql -u root vokuro

Also you can override application config by creating app/config/config.dev.php (already gitignored).

Installing Dependencies via Composer
------------------------------------
Vökuró's dependencies must be installed using Composer. Install composer in a common location or in your project:

```bash
curl -s http://getcomposer.org/installer | php
```

Run the composer installer:

```bash
cd vokuro
php composer.phar install
```

Improving this Sample
---------------------
Phalcon is an open source project and a volunteer effort. Vökuró does not have human resources fully dedicated to the mainteniance of this software. If you want something to be improved or you want a new feature please submit a Pull Request.

License
-------
Vökuró is open-sourced software licensed under the New BSD License.
