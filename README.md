# how to reproduce

```sh
composer install
```
```sh
php vendor/bin/phpstan analyse
```

---

# Results

### Expected
```
 ------ -------------- 
  Line   Foo.php       
 ------ -------------- 
  12     App\Code\Bar  
 ------ --------------
 ```

### Got
```
 ------ -------------- 
  Line   Foo.php       
 ------ -------------- 
  12     App\Code\Bar  
  12     App\Code\Bar  
  12     App\Code\Bar  
  12     App\Code\Bar  
 ------ --------------
 ```
