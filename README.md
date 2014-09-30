WordPress-Stack-Vagrant
=======================

Vagrant WordPress stack running on Ubuntu 14.04, NGINX, PHP-FPM, MariaDB, and Varnish.

Utilizing Ansible for Provisioning.

PHP 5.5 optimized with Opcache

NGINX built from source to include Google PageSpeed module.

Includes Varnish HTTP Purge (activated), WordPress Importer (not activated), and Jetpack (not activated) wordpress plugins installed by default.


Requires
=======================

Vagrant (to run)

vagrant-hostmanager (vagrant plugin install vagrant-hostmanager)

Ansible (to provision)
