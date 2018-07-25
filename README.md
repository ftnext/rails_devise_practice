# README

Railsでdeviseを触ってみるためのリポジトリ  

以下を参考に触ってみる  
[[\*Rails\*] deviseの使い方（rails5版）](https://qiita.com/cigalecigales/items/f4274088f20832252374)

* Ruby version: 2.4.1
* Rails version: 5.1.4
* devise version: 4.4.3

環境構築はDockerを用いている。(DBはmysqlを使用)  
このリポジトリをcloneした後、

```
$ docker-compose up -d
```

をすると環境が立ち上がる。  
初回起動時はrailsコマンドによるDBの設定が必要。

```
$ docker exec -it <webコンテナ名> bash
# rails db:create
# rails db:migrate
```

MIT License
