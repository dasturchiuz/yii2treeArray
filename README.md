NestedSetsTreeBehavior
======================
NestedSetsTreeBehavior this is the connector between
https://github.com/creocoder/yii2-nested-sets

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require dasturchiuz/treebehaviorcategories
```

or add

```
"dasturchiuz/treebehaviorcategories": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your model  :

```php
'htmlTreeCategory'=>[
    'class' => \dasturchiuz\treebehaviorcategories\NestedSetsTreeBehavior::className()
]
```
use
```php
SomeModel::findOne($id)->treeCategory()
```
to get arrays


