# add-captcha
thinkphp5 加法验证码类库

## 安装
> composer require oeynet/add-captcha

## Usage
controller class ...method
```php

    public function getVerify()
    {
        $captcha = new CaptchaHelper();
        return $captcha->entry(1);
    }

```

## 效果
![](./readme/1.png)
