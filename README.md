yii2-jstree
===========
Widget for Yii Framework 2.0 to use [JsTree](http://www.jstree.com)
Fork
------------
Changes to [thiagotalma/yii2-jstree-widget](https://github.com/thiagotalma/yii2-jstree-widget):
- Provides JSTree Version 3.0.8
- Supports search.search_callback

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist p4-solutions/yii2-jstree-widget "*"
```

or add

```
"p4-solutions/yii2-jstree-widget": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by :

```php
<?=  \p4solutions\jstree\JsTree::widget([
    'attribute' => 'attribute_name',
    'model' => $model,
    'core' => [
        'data' => $data
        ...
    ],
    'plugins' => ['types', 'dnd', 'contextmenu', 'wholerow', 'state'],
    ...
]); ?>
```
