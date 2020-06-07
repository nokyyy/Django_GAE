# Django_GAE
 
# Features

PythonのDjangoを使って、
ホームのページ/ ブログ一覧のページ/ ブログ作成のページ/ admin の４つでできています

DBは mysql を使用しました

Google App Engineにデプロイしました
https://blpgapp.an.r.appspot.com/

# Requirement
 
* python3
* JavaScriptが動くブラウザ
 
# Installation

インストール必要なものは「requirement.txt」 に記載
 
# Usage

仮想環境を作り、Djangoを入れ
setting.pyの「DATABASE」の中で使用するDBを記入してください(ディホルトはsqlite3)
ローカル環境であれば「manage.py」ファイルと同じ階層で「python manage.py runserver」のlinuxコマンドを
打っていただけばローカルサーバーが起動し、見られるようになると思います

# Note
 
MySQLにDBを作る際に pymysql をimportすると終始manage.pyがエラー表記になりますが、デプロイするときは問題なく動きます。
 
# Author

nokyyy
 
# License
 
 nokyyy owns copyright on these sites nokyyy uploaded
