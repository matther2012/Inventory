This is the LCDI's internal inventory tracking system. 

It hooks into our AD for logins.


The original project was written very quickly due to necessity in the lab.  
There are probably bugs, errors, and algorithms that make no sense....but it works :P


Change the mysql credentials in includes/functions.php and admin.php


edit and rename the adLDAP module to fit your company's domain
includes/adLDAP/src/adLDAP.php.sample

## Bolt Installation

The following was originally found at https://docs.bolt.cm/installation, and has been adapted for this project.

Clone the bolt repo:
```
git clone git://github.com/bolt/bolt.git bolt
cd bolt
```

In order to find the latest stable branch, use the command below. The current stable version as of 01/26/2016 is "v2.2.16".
```
git tag
```

Then checkout the version desired:
```
git checkout <version> // presently "git checkout v2.2.16"
```

Install composer:
```
curl -s http://getcomposer.org/installer | php
php composer.phar install
```

And now just setup the correct file permissions:
```
chmod -R 777 files/ app/database/ app/cache/ app/config/ theme/ extensions/
```

## Bolt Setup


