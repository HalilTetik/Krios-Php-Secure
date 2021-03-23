# Krios Software
## _Krios Php Secure_


Php yazılım zaafiyeti korumasıdır.

## Engellenenler;
> Php version,
> Xss Açıkları,
> Sql İnjection,
> Hsts kuralı,

## Nasıl kullanılır;

> bridge.php dosyasının ilk 15 satırını kendinize göre ayarlayın.
> bridge.php dosyasını korumak istediğiniz sayfalara en üste dahil edin.
 Dahil etme kodu;
```php
 <?php
 include ("bridge.php");
 ?>
```
