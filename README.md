# BASDEVELOP

* 環境構築手順
git clone後に
以下のコマンドを実行

1.cd develop/docker<br>
2.docker-compose run --rm --no-deps php-fpm composer create-project laravel/laravel --prefer-dist .<br>
3.docker-compose run --rm --no-deps php-fpm composer require predis/predis<br>
4.docker compose up -d<br>
