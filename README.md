https://qiita.com/LyasuiB/items/d979bba8289999200b81
を元に作成中

クローン後の対応
1 docker compose up -d
2 docker compose exec app bash
3 (app内で)composer create-project --prefer-dist "laravel/laravel=11.*" .