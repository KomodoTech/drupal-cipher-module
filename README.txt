
Drupal Cipher Module
=======================

https://github.com/KomodoTech/drupal-cipher-module

Site Description
-------------

This is a module implementation of a simple shift cipher

It serves as an example highlighting:

- Custom Modules
- Form Validation
- Basic Regex
- Basic Shift Algorithm


Installation
--------------------------

1. Git Clone Drupal Cipher Module (https://github.com/KomodoTech/drupal-cipher-module.git)

2. Run local apache and mysql servers (development used MAMP application) from project root.

3. From the site's phpMyAdmin page, import cipher.sql.zip from <project root>/sites/db-backup/cipher.sql.zip

4. From the site's dashboard go to modules and make sure that all the necessary modules are enabled:
  
    - Cipher
    
5. If there are any problems try resetting the cache (drush cc all)

If you find a problem that cannot be fixed with cache clearing,let me know through my github. Thank you
