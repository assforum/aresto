
# Sophisticated online survey software



## About
aresto 

Advanced features like branching and multiple question types make it a valuable partner for survey-creation.



## How to install

### Release
We try to publish a release every other day.
We recommend using those.

### Repository
You may want to use the plain repository, which is also possible.

Please be advised, that we sometimes push development versions into the repository, which may not be working correctly.

## Requirements

### Minimal
The absolute minimal requirements are:
 - Apache >= 2.4 | nginx >= 1.1 | any other php-ready webserver
 - php >= 5.4
    - with mbstring and pdo-database drivers
 - mysql >= 5.5.3 | pgsql >= 9 | mariadb >= 5.5  | mssql >= 2005

### Recommended
We recommend the following setup
 - Web server: nginx (most recent stable version)
 - PHP (most recent stable version)
    - with php-fpm, mbstring, gd2 with freetype, imap, ldap, zip, zlib and database drivers
 - MariaDB or MySQL (most recent stable version)

## Manual
for more information please refer to our [homepage](http://www.limesurvey.org), or have a look at the [manual](http://manual.limesurvey.org) 

## Licence
LimeSurvey software is licenced under the [GPL 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).

Pictures and the LimeSurvey Logo are registered trademarks of LimeSurvey GmbH, Hamburg, Germany.

## Tools used
We are using BrowserStack to run manual tests on different browsers and devices

[![](https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/docs/contributions/browserstack-logo.png "Checkout BrowserStack")](https://www.browserstack.com/)

We are using Scrutinizer to static check our code

[![](https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/docs/contributions/scrutinizer-logo.png "Checkout scrutinizer")](https://scrutinizer-ci.com/)

We are using TravisCI to run automated tests before release:

[![](https://raw.githubusercontent.com/LimeSurvey/LimeSurvey/master/docs/contributions/travisci-logo.png "Checkout TravisCI")](https://travis-ci.org/)

