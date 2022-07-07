# 概要
Ruby On Railsの学習としてblogアプリを作るための環境
<br>
Blogアプリのレポジトリ：https://github.com/KotaY0203/ror_blog_app

# 構築手順
1. このdockerレポジトリをclone。
2. blogディレクトリをdocker-compose.ymlと同階層に作成。
3. blogディレクトリに移動し、[Blogアプリのレポジトリ](https://github.com/KotaY0203/ror_blog_app)をclone。
4. /blog/config/database.ymlを修正。
5. DB作成（下記サンプルコマンド）。
~~~
$ ocker-compose run web bundle exec rails db:create
~~~
