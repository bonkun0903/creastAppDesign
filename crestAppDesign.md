# クレスト基本設計

## [作業ルーティーン](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1612669805&range=C5)

## 基本機能

### 一次開発

- 商品の登録・編集・削除機能
- 商品コメント登録・編集・削除機能
- [商品ジャンルごとのタブ分け＆＆配送グループごとのフィルター（一覧表示機能）](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A55)
- ~~[商品登録時配送サイズ（グループ）決定機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A4)~~
- [商品画像の添付、表示順番の変更機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A19)
- [車両情報の自動紐付け機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188)
- [商品の情報入力補助機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A4)
- [商品詳細HTMLの作成支援機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A7)
- [棚上げ作業支援機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A10)
- [在庫シール印刷機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A31)
- [車両情報のCSVアップロード機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A13)
- [競ナビ向け商品データCSVのエクスポート機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A16)
- [ラクーン向け商品データCSVのエクスポート機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A16)
- [商品説明のプレビュー機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A34)

### 二次開発

- ログイン・ログアウト機能（omniAuthを利用したGoogleアカウントログイン）
- 管理者ユーザーによるユーザーの登録・編集・削除機能
  
### 三次開発

- カテゴリIDの検索機能
- 車両情報の一覧機能
- [商品ステータス別にタブ分けする機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A22)
- [レビュー機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A25)
- [通知機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A28)
- [訂正指示対応機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A16)
- 操作マニュアル機能（マニュアル内検索機能付き）
- 登録ガイドライン表示機能（ジャンル別、商品登録にヒントとして掲載）
- [商品落札状況CSV反映機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A52)

## バッジ機能

- 出品OK商品の自動CSVダウンロード機能
- [車両情報の逐次反映機能](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A40)
- [月報集計機能（毎日集計、プレビュー画面あり）](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1620229188&range=A43)

## 画面一覧

- ログイン・ログアウト
- 商品登録
- 商品編集
- 商品詳細
- 商品一覧
- 商品コメント一覧
- 商品コメント詳細
- 車両一覧
- 車両CSVアップロード
- 管理者ページ
  - ユーザー登録
  - ユーザー編集
  - ユーザー詳細
  - ユーザー一覧
- ユーザー詳細
- 月報確認画面
- 共通表示
  - 通知アイコン
  - ユーザーアイコン
- マニュアル画面
- 通知一覧画面
- 通知

## [モデル一覧](https://docs.google.com/spreadsheets/d/1CCfhtsdbCOP2Au_lwMvG9FRbsbBJtt4OBNNqlyF7p1g/edit#gid=1268235951)
