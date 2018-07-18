# s_cache
スピードテスト対策、キャッシュ再利用の.htaccessの書き方

```
#ブラウザキャッシュの設定
ExpiresActive On
ExpiresByType text/css "access plus 1 weeks"
ExpiresByType image/gif "access plus 1 weeks"
ExpiresByType image/jpeg "access plus 1 weeks"
ExpiresByType image/png "access plus 1 weeks"
ExpiresByType text/javascript "access plus 1 weeks"
ExpiresByType application/x-javascript "access plus 1 weeks"
ExpiresByType application/javascript "access plus 1 weeks"
```
数値は良しなに変えてね。
