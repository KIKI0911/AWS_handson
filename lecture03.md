# 第3回課題
## 1. APサーバを調べる
- APサーバーの名前とバージョンを確認してみましょう。

  A. Puma version 5.6.8
>![スクリーン ショット 2024-03-08 に 午前8 02 00](https://github.com/KIKI0911/AWS_handson/assets/148507850/111ee50c-836d-4e95-9e2d-82fd5df48149)


- APサーバーを終了させた場合、引き続きアクセスできますか？

   A. アクセスできない
> ![スクリーン ショット 2024-03-08 に 午前7 05 40](https://github.com/KIKI0911/AWS_handson/assets/148507850/172774c0-19f5-441b-8575-b3c4513a1ca7)


# 2. DBサーバについて調べる
- サンプルアプリケーションで使ったDBサーバー(DBエンジン)の名前と、いう間cloud9で動作しているバージョンはいくつか確認してみる
> ![スクリーン ショット 2024-03-08 に 午前7 07 25](https://github.com/KIKI0911/AWS_handson/assets/148507850/ae1a4c61-8440-40d3-b55b-fdb42ae0c53a)

- DBサーバーを終了させて場合、引き続きアクセスはできますか？

  A. アクセスできない
> ![スクリーン ショット 2024-03-08 に 午前7 38 24](https://github.com/KIKI0911/AWS_handson/assets/148507850/c6067639-c1c7-421a-aaba-c6a183be06dd)

> ![スクリーン ショット 2024-03-08 に 午前7 42 01](https://github.com/KIKI0911/AWS_handson/assets/148507850/14cb9240-f24c-4b98-955f-b65ef5533da4)

- Railsの構成管理ツールの名前はなんでしたか？

A. Builder

## 3. Webアプリへアクセス

> ![スクリーン ショット 2024-03-07 に 午前7 54 23](https://github.com/KIKI0911/AWS_handson/assets/148507850/7ebe90e9-e6c2-41d6-ae73-89476790a6be)


## 課題から学んだこと

・DBサーバーの起動、停止、確認のコード
・DBサーバーを停止した後の確認はsudo service mysqld startを実行した後に確認すること。

DBサーバーの起動

``` $ sudo service mysqld start ```

DBサーバーの停止

``` $ sudo service mysqld stop ```

DBサーバーの確認

``` $ sudo service mysqld status ```
