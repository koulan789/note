## Composer 国内镜像
~~~
"repositories": {
    "packagist": {
        "type": "composer",
        "url": "https://packagist.phpcomposer.com"
    }
}
~~~
## Composer 配置国内镜像
~~~
composer config -g repo.packagist composer https://packagist.phpcomposer.com
~~~

## 优化自动加载索引
~~~
composer dump-autoload --optimize
~~~