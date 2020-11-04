# How to run

1. Download the repository: `git clone https://github.com/ksowa/phpmnd-bug-reproduction.git phpmnd-bug-reproduction`
1. Enter the directory: `cd phpmnd-bug-reproduction`
1. Run the container: `docker-compose up -d`
1. Enter the container: `docker-compose exec php bash`
1. Install composer libs: `composer install`
1. Run phpmnd: `./vendor/bin/phpmnd Match.php`

## Output:

```
root@fa123df32d59:/var/www# ./vendor/bin/phpmnd Match.php 
phpmnd 2.3.0 by Povilas Susinskas
Syntax error, unexpected T_MATCH, expecting T_STRING on line 6


--------------------------------------------------------------------------------

Total of Magic Numbers: 0
Time: 00:00.034, Memory: 8.00 MB
```
