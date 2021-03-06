Password Generator App
======================

[![SensioLabsInsight](https://insight.sensiolabs.com/projects/d047a615-edf1-4c4e-91d6-d84e82943256/big.png)](https://insight.sensiolabs.com/projects/d047a615-edf1-4c4e-91d6-d84e82943256)

Demo
----

A setup version is available for use at [http://passwords.ofdan.com/]


Installation
---------------

You have three different ways to download the app.

a) Composer
-----------

```bash
composer create-project hackzilla/password-generator-app
```

b) Git
------

```bash
git clone git@github.com:hackzilla/password-generator-app.git
composer install
bin/console cache:clear --env=prod --no-debug
```

c) Download
-----------

https://github.com/hackzilla/password-generator-app/archive/master.zip


Once installed run:

```bash
composer install
bin/console cache:clear --env=prod --no-debug
```

d) Update Front-end dependencies

* https://blog.engineyard.com/2014/frontend-dependencies-management-part-1
* npm install
* ./node_modules/bower/bin/bower install


Components
----------

* Password Generator Library [https://github.com/hackzilla/password-generator]
* Password Generator Bundle [https://github.com/hackzilla/password-generator-bundle]
