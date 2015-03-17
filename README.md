Stage File Proxy Private
==============================

**Please, do not keep passwords in variables if your env is public! Thanks ;)**

Download private file from production to development environment through ssh if 
it doesn't exists in local filesystem (on demand).
 
## Requirements:

* [ssh2 php library](http://php.net/manual/en/book.ssh2.php)

````
sudo apt-get install libssh2-php
sudo /etc/init.d/apache2 restart
````

## Dependencies:

* Stage File Proxy

## Credits

* Ny Media AS
