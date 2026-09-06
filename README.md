# character-diagnosis

GitHub Pages 用・簡易ログイン付き診断サイトです。

## ファイル構成

index.html
login.html
README.md

この3つを `character-diagnosis` リポジトリの直下に置いてください。

## 最初にすること

`login.html` を開き、下の行を探してください。

const PASSWORD = "CHANGE_ME";

`CHANGE_ME` を好きな合言葉に書き換えます。

例：

const PASSWORD = "starfall2026";

## 公開URL

https://ユーザー名.github.io/character-diagnosis/login.html

または

https://ユーザー名.github.io/character-diagnosis/

へアクセスすると、未ログインなら自動的に login.html へ移動します。

## 動作

- login.html で合言葉が正しい
- sessionStorage にログイン済み情報を保存
- index.html を表示
- ブラウザのタブ/セッションを閉じると、基本的に再ログインが必要
- 「ログアウト」で login.html に戻る

## 重要

これは GitHub Pages のような静的サイトで使う「簡易的な入口」です。
本物のアクセス制御ではありません。

HTML/JavaScriptに詳しい人なら、
- ソースを見る
- JavaScriptを変更する
- sessionStorageを操作する

などで回避できます。

「URLを知っている人にも中身を絶対に見せたくない」用途には向きません。
