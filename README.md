# api-setup-practice

## 概要

COACHTECH 教材 Tutorial 11-1「API開発環境の構築と疎通確認」で作成した成果物です。
GET /api/hello にアクセスすると、「hello, API!」というメッセージをJSON形式で返すAPIを作成しました。

## 使用技術

- PHP 8.x
- Laravel 10.x
- REST API（JSONレスポンス）
- Postman（動作確認）

## 学んだこと

- APIのルートを設定する方法を学んだ。
- GETリクエストを受けて、JSONで返す方法を学んだ。

## 動作確認

PostmanでGET 'http://localhost/api/hello'にアクセスして、ステータスコード'200 ok'であること、JSON形式でメッセージがかえってきたことを確認した。
