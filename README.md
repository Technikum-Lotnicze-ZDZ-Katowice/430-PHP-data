# 430-PHP-data

```php


$startX = 100;
$startY = 100;
$koniecX = 200;
$koniecY = 200;

ImageRectangle($obrazek, $startX, $startY, $koniecX, $koniecY, $czarny);
ImageFilledRectangle($obrazek, $startX, $startY, $koniecX, $koniecY, $czarny);

```

```php
<?php

$od  = "From: uzytkownik@kursphp.com \r\n";
$od .= 'MIME-Version: 1.0'."\r\n";
$od .= 'Content-type: text/html; charset=iso-8859-2'."\r\n";
$adres = "przyklad@uzycia.pl";
$tytul = "Tytuł wiadomości";
$wiadomosc = "<html>
<head>
</head>
<body>
   <b>Witam serdecznie!</b><br/>
   Zapraszam na stronę: <a href="https://kursphp.com">Kurs PHP</a>   
</body>
</html>";

// użycie funkcji mail
mail($adres, $tytul, $wiadomosc, $od);

?>
```

### Zadania

ZAD43001 
Przygotuj aplikację 

### Info
https://kursphp.com/nauka-php-online/
