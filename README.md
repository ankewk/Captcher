# Captcher
Captcha Generator (PHP + GD)

## Basic usage
```php
use CodeRider\Captcher

$cap = new CaptchaGenerator(200, 50);
$captchaImage = $cap->generate();
$captchaText = $cap->getCaptchaText();
```

*$captchaImage* output:  
![alt tag](https://raw.githubusercontent.com/coderiderpl/Captcher/master/example/captcha-example.jpg)

*$captchaText* output:  
ERZ2

## Custom options
