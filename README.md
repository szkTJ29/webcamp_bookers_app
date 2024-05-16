# Bookers

本を読んだユーザーが、本のタイトルと感想を投稿することができるwebアプリケーション


* 使用言語・フレームワーク<br>
  →使用言語：Ruby, Javascript, HTML, CSS<br>
  →フレームワーク：Ruby on rails

* 開発環境（インフラ・DB）<br>
 →開発環境：AWS cloud9<br>
 →サーバー：AWS EC2<br>
 →DB：sqlite3

* なぜその言語・フレームワークを選んだか<br>
  →Rubyを学習したことがなかったため、開発を行いながらRubyの学習も進めたいと考えたため<br>
  →MVCパターンについて学習することでフロントエンドとバックエンドの理解が深まると考えたため

* 成果物のこだわり<br>
  →Ruby on railsで基本とされている7つのアクションを全て利用した（new, create, index, show, edit, update, destroy）

* 反省点<br>
  →画面レイアウトをあまり考えずに開発を行なってしまった

* <h5>画面レイアウト</h5>
<h3>トップページ</h3>
→startをクリックして投稿一覧に遷移
<img width="1710" alt="top" src="https://github.com/szkTJ29/webcamp_bookers_app/assets/87642790/46724604-98d0-4498-ad39-5d096742ca31">
<h3>投稿一覧</h3>
→Showをクリックして投稿詳細、Editをクリックして演習に遷移、Destroyをクリックして投稿削除、フォームにtitleとbodyを入力後Create Bookをクリックして新規投稿
<img width="1710" alt="index" src="https://github.com/szkTJ29/webcamp_bookers_app/assets/87642790/6737b524-0a7d-46db-a21d-2dec07523e77">
<h3>投稿詳細</h3>
→Editをクリックして編集、Backをクリックして投稿一覧に遷移
<img width="1710" alt="show" src="https://github.com/szkTJ29/webcamp_bookers_app/assets/87642790/d8edf165-6188-45f2-af8d-7f29fa881d28">
<h3>編集</h3>
→Showをクリックして投稿詳細、Backをクリックして投稿一覧に遷移、Update Bookをクリックして投稿内容更新
<img width="1710" alt="edit" src="https://github.com/szkTJ29/webcamp_bookers_app/assets/87642790/e24db00a-b3a4-4802-a8db-464397d6ffaf">
