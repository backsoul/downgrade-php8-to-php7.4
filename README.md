# downgrade-php8-to-php7.4

```
mkdir /tmp/php7bin
```
```
ln -s /usr/bin/php7 /tmp/php7bin/php
```
```
export PATH="/tmp/php7bin:$PATH"
```




### now /bin/env php will find php7 in this shell
