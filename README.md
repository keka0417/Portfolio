# このリポジトリについて

* 転職用のポートフォリオであるファッションアプリになります


## 使用技術

* 開発
  * Laravel
  * Docker
* デザイン
    * figma
    
* ER図
    * drawio
  

## 環境について

Dockerで下記環境を構築しています。  
詳細は`docker-compose.yml`を参照。

* laravel
    * ポート:8000
    * `src`ディレクトリ配下が`laravel`になります
    
* mysql
    * ポート:3306
    
* phpadmin
    * ポート:8080
  
## 環境構築手順

* このリポジトリを`git clone`する
* `トップディレクトリ`で`docker-compose up -d`を実施し、コンテナ立ち上げ。
* `localhost:8000`にアクセス
    * laravelが立ち上がります
    

## デプロイ

* フローが整備され次第追記
    

