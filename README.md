# question_diagnosis

## サイト概要
・ユーザーにより4択の質問を5つ作成し、その選択により結果が変わる診断テスト作成サイト

### サイトテーマ
・診断テスト作成サイト

### テーマを選んだ理由
・大学生の時に入った軽音楽部でどの楽器をするのか迷った経験から、最初は質問の回答結果によりどの楽器を担当するかが決められる
　というアプリを作ろうと思ったのですが、様々なジャンルの診断・心理テストがあることを知り、音楽に限らず様々なジャンルの診断を
　ユーザー側から作成できるフォーマットサイトを作ろうと考えました。

### ターゲットユーザ
・診断テストを作成したい人
・診断テストを受けたい人

### 主な利用シーン
・様々なジャンルの診断テストを受ける、あるいは作成する際利用する

## 設計書
・ユーザー登録、ログイン機能(devise)
・投稿機能
・いいね機能(Ajax)
・ランキング機能
・ページネーション機能(kaminari)

## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9
