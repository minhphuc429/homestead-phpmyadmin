## About

Simple shell script that automatically installs the latest version of PhpMyAdmin
on a Laravel Homestead box.

## Usage

1. Open the `Homestead.yaml` file on your main machine and add
    ```
    sites:
        - map: phpmyadmin.test
          to: /home/vagrant/code/phpmyadmin
    ```

2. SSH into your Homestead box `vagrant ssh`

3. `cd` to your code/projects directory (by default `~/code`)
   
4. `sudo curl -sS https://raw.githubusercontent.com/minhphuc429/hpma/master/phpmyadmin.sh | sh`

5. Go to [http://phpmyadmin.test](http://phpmyadmin.test). Default credentials are username `homestead` and password `secret`

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
