RBAC admin module with UUID support
===================================
Fork of Mdmsoft RBAC admin extension, with UUID support.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist nex-otaku/yii2-uuid-admin "*"
```

or add

```
"nex-otaku/yii2-uuid-admin": "*"
```

to the require section of your `composer.json` file.


Usage
-----

See "mdmsoft/yii2-admin".

Requirements
-----

Currently (version 3.2 of yii2-admin) module is not working with latest Angular libraries - version 1.6.1 as for 2017.01.08.
So it is tied to version 1.5.8 of Angular libraries.