# wordpress-ansible

#### Prerequisites:
 * nginx installed
 * php-fpm 7 installed
 * nginx and php configured to serve from `/var/www/html/wordpress` path with user `www-data`

#### Usage:
 * Include your hosts in `hosts` file. and then run:
```
sudo ansible-playbook playbook.yml -i hosts -u <username> -b
```

#### Notes
 * This was tested to be working on debian 9 EC2 host.
