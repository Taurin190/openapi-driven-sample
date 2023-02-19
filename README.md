# openapi-driven-sample
openapiのスキーマを起点に開発したサンプル。

## アプリ内容
[別リポジトリ](https://github.com/Taurin190/nuxt-sample)で扱うコンテンツを管理するツールにしたい。

### 機能
- 認証
  - ログイン
  - ログアウト
  - サインイン
  - メール認証
- 管理
  - ユーザ
    - 招待
    - 一覧取得
    - 詳細取得
    - ロール変更
    - 削除
  - ロール
    - 作成
    - 変更
    - 削除
    - 一覧取得
  - 劇場
    - 追加
    - 変更
    - 削除
    - 一覧取得
    - 詳細取得
- コンテンツ管理
  - 映画
    - 追加
    - 変更
    - 削除
    - 一覧取得
    - 詳細取得
  - キャンペーン
  - ニュース
  - イベント
  - よくある質問
  - サービス

# 使い方
## Redocly
[元ドキュメント](https://github.com/Redocly/openapi-starter)を参照。

ローカルで起動し参照。
```
npm start 
```
出力ファイル作成
```
npm run build
```

## oapi-codegen
Goコード出力
```
$ oapi-codegen dist.yaml > openapi.gen.go
```

## openapi-generate
フロントのTSコードを出力
```
$ npm run openapi-generate
```