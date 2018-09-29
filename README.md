Yii 2 Basic Project With Template Admin Gentelella
============================

Yii 2 Basic Project Template is a skeleton [Yii 2](http://www.yiiframework.com/) application best for
rapidly creating small projects.

The template contains the basic features including user login/logout, a contact page, and modified layout main use gentelella.
It includes all commonly used configurations that would allow you to focus on adding new
features to your application.

For more detail, see https://github.com/yiister/yii2-gentelella

[![Latest Stable Version](https://poser.pugx.org/yiisoft/yii2-app-basic/v/stable.png)](https://packagist.org/packages/yiisoft/yii2-app-basic)
[![Total Downloads](https://poser.pugx.org/yiisoft/yii2-app-basic/downloads.png)](https://packagist.org/packages/yiisoft/yii2-app-basic)
[![Build Status](https://travis-ci.org/yiisoft/yii2-app-basic.svg?branch=master)](https://travis-ci.org/yiisoft/yii2-app-basic)

DIRECTORY STRUCTURE
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      themes/             contains files themes gentelella
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources



REQUIREMENTS
------------

The minimum requirement by this project template that your Web server supports PHP 7.1.0.


INSTALLATION
------------

### Install

If you do not have [Composer](http://getcomposer.org/), you may install it by following the instructions
at [getcomposer.org](http://getcomposer.org/doc/00-intro.md#installation-nix).
If you do not have [Git](https://git-scm.com/), install it by following the instructions.

You can then install this project using the following command:

~~~
git clone https://github.com/wlnoor/yii2-gentelella.git
composer install
~~~

Now you should be able to access the application through the following URL, assuming `yii2-gentelella` is the directory
directly under the Web root.

~~~
http://localhost/yii2-gentelella/web/
~~~

Or you can use `php yii serve` command in the directory directly under aplication.

~~~
http://localhost:8080
~~~

VIEW
------------

The following is a display on the admin page

![Images](/web/images/view-layout.png)
