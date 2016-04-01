# Unsharp Mask for PHP

This implementation is copied from http://vikjavev.no/computing/ump.php and wrapped with composer.


## Introduction

When creating thumbnails in photo editing programs, it is a good idea to apply some kind of sharpening filter. I created this program to do the same with thumbnails created on the fly in PHP. Among other sites, the script has been implemented in the commercial forum software vBulletin. Feel free to copy it from the field below to use on your own website. 


## Usage

```php
require_once __DIR__ . '/vendor/autoload.php';
use Torstein\UnsharpMask;
// ...
UnsharpMask::sharpen($img, $amount, $radius, $threshold);
```
