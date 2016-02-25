# yii2-tagsinput

[![Latest Version](https://img.shields.io/github/release/wbraganca/yii2-tagsinput.svg?style=flat-square)](https://github.com/wbraganca/yii2-tagsinput/releases)
[![Software License](http://img.shields.io/badge/license-BSD3-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Total Downloads](https://img.shields.io/packagist/dt/wbraganca/yii2-tagsinput.svg?style=flat-square)](https://packagist.org/packages/wbraganca/yii2-tagsinput)


## Install

Add to your composer.json file

```
"repositories": [
        {
            "url": "https://github.com/WondersLabCorporation/yii2-tagsinput.git",
            "type": "git"
        }
    ]
```
and run

```bash
$ composer require WondersLabCorporation/yii2-tagsinput:dev-master
```

or add

```
"WondersLabCorporation/yii2-tagsinput": "dev-master"
```

to the require section of your `composer.json` file.


## Usage

On your view file.

```php

<?php
use wbraganca\tagsinput\TagsinputWidget;
?>

<?= $form->field($model, 'tags')->widget(TagsinputWidget::classname(), [
    'clientOptions' => [
        'trimValue' => true,
        'allowDuplicates' => false
    ]
]) ?>

```

For more options, visit: http://bootstrap-tagsinput.github.io/bootstrap-tagsinput/examples/
