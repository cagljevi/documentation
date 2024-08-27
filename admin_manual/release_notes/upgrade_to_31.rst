=======================
Upgrade to Nextcloud 31
=======================

System requirements
-------------------

* PHP 8.1 is now deprecated but still supported.

PHP configuration
-----------------

We have a new setup warning to check if the memory reserved for APCu is high enought. If you see this warning, you should increase the memory reserved for APCu. You can do this by increasing the value of the ``apc.shm_size`` directive in your ``php.ini`` file. It is generally adviced to review this value and increase it if necessary depending on your instance size.