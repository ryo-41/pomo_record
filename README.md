# ポモドーロ学習記録アプリ  

## サービス概要  
ポモドーロ学習記録アプリはポモドーロテクニックと学習時間の記録と共有ができる、学習サポートサービスです。　　

## 想定されるユーザー層　　
* プログラミング学習をしている人

## サービスコンセプト
* ユーザーが抱えている課題感と提供するサービスでどのように解決するのか  
学習に集中できない人にポモドーロテクニックを提供します。  
また学習時間を記録、共有することで学習を継続するのをサポートします。

* なぜそのサービスを作ろうと思ったのか  
自分がプログラミング学習を始めたばかりの頃は他の誘惑に駆られて学習に集中することができませんでした。  
そんな時にYoutubeでポモドーロテクニックを知り実践してみると効果を感じることができました。  
またMattermostで他の人の学習時間を知ることもモチベーションを維持する助けになりました。  
その経験からポモドーロテクニックと他人との学習時間の共有ができるアプリを作りたいと思いました。  
	
* どのようなサービスにしていきたいか  
学習の効率化とモチベーションを維持するのをサポートできるアプリにしていきたいです。

* どこが売りになるか、差別化ポイントになるか  
差別化されている点はポモドーロタイマーを使いつつ簡単に学習の記録ができて、それを共有できるところです。  
売りポイントは他のポモドーロ・テクニックを使ったサービスよりも学習のモチベーションを上げることに力を入れているところです。
学習時間の共有やランキング、いいね機能でモチベーションを上げるのをサポートします。

## 実装を予定している機能
### MVP
* 会員登録
* ログイン
* ポモドーロタイマー
* タスクの設定
* 学習時間の記録
    * ポモドーロタイマーが終了するたびに、その学習時間が自動的に学習記録に追加される。
* 学習時間の共有
    * 学習時間をコメント付きで投稿できる。
    * 他のユーザーの投稿をカード形式で表示する。
    * 他のユーザーの投稿にいいねできる。
* 通知機能
    * ポモドーロタイマー終了時。
    * ポモドーロタイマー終了の一定時間前。
    * 一定時間以上学習したとき。
    * いいねされたとき。
### その後の機能
* Google ToDoとの連携
    * Google Tasks APIを使用してGoogle ToDoのタスクをインポート、更新できる。
* 学習時間のランキング
    * 学習時間のランキングは登録ユーザーたちの学習時間を期間ごとにランキング形式で表示する。
