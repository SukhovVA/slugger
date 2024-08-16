# Конвертор url 
Конвертирует строку url в slug
## Требования
- PHP >= 7.0
- ext-mbstring
## Установка
composer require sukhov/slugger
## Использование
```
<?php
$slug = Slugger::urlToSlug('example-url');
echo $slug'
```