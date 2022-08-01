reproducing repo for [phpstan bug 7732](https://github.com/phpstan/phpstan/issues/7732)

Steps
- checkout repo
- run `php 3rd-party/vendor/bin/phpstan`

expected result
- no errors

actual result
```
------ --------------------------------------------------------------------- 
  Line   fn.php                                                               
 ------ --------------------------------------------------------------------- 
  4      Function str_ends_with not found.                                    
         💡 Learn more at https://phpstan.org/user-guide/discovering-symbols  
 ------ ---------------------------------------------------------------------
```