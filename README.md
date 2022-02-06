# SimpleHtmlDom

This is a fork of the original [Simple HTML DOM Parser](https://sourceforge.net/projects/simplehtmldom/) with namespace & bug fixes.

The only noticeable difference to the original package is the composer installation method and namespace reference.

## Changes

Please refer to the `CHANGELOG.md` for a list of changes.

## Installation

```
composer require axllent/simplehtmldom
```

## Documentation

Please note the use of the namespace:

```php
<?php
$dom = SimpleHtmlDom\:file_get_html($url);
// or
$dom = SimpleHtmlDom\str_get_html($html);
```

For official documentation and examples refer to the [official documentation](https://simplehtmldom.sourceforge.io/manual.htm).
