Conversion of inactive links in the text
================

Conversion of inactive links in the text into active clickable links

Небольшой класс для преобразования неативных ссылок в тексте в активные.

Installation
------------

```sh
$ composer require skeeks/text-to-active-links "^0.0.1"
```

Or add this to your `composer.json` file:

```json
{
    "require": {
        "skeeks/text-to-active-links": "^0.0.1"
    }
}
```

Usage
-----

```php
<?
    $handler = new \skeeks\textToActiveLinks\TextToActiveLinks();
    $handler->short_link_max_length = 45;
    echo $handler->correct($yourText);
?>
```

```php
<?= (new \skeeks\textToActiveLinks\TextToActiveLinks())->correct($yourText); ?>
```
___

> [![skeeks!](https://skeeks.com/img/logo/logo-no-title-80px.png)](https://skeeks.com)  
<i>SkeekS CMS (Yii2) — quickly, easily and effectively!</i>  
[skeeks.com](https://skeeks.com) | [cms.skeeks.com](https://cms.skeeks.com)
