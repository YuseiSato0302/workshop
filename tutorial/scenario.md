# シナリオ

## 目的

2015年のSEゼミのテーマは「OSS開発」です。2015年のSEゼミ第3弾の「OSS
Hack 4 Beginners」の目的は「OSSの開発参加への不安を取りのぞくこと」で
す。

## 目的の背景

SEゼミ第4弾のイベント「OSS Hack Weekend」をより充実した時間とするため
に、「OSSの開発に参加してみたいけど漠然とした不安があり手を出せていな
い…」という学生の「不安」を取りのぞくことを重視します。不安があるとの
びのびと楽しくOSSの開発に参加できないからです。のびのびと楽しくOSSの開
発に参加できる準備をして、「OSS Hack Weekend」を充実した時間としましょ
う。

## 目的の実現方法

「不安」の原因は次のことだと予想しました。

  * 「やり方」を知らないから「不安」なのではないか。
  * やったことがないから「不安」なのではないか。
  * 「失敗が怖い」から「不安」なのではないか。

これらの「不安」を解決するために次のことを実施します。

  * 「やり方」を伝える。
  * 「やり方」を自分でやってみる。
  * やるときは「失敗」しても大丈夫な状況でやる。

具体的には次の方法を実施して「不安」を取りのぞきます。

  * オススメのOSS開発参加方法を紹介
  * オススメの方法を実践
  * 対象OSSはメンターが開発に関わっているOSS

OSSの開発に参加する方法は無数にありますが、「好きなようにやっていいん
だよ」と言うと不安が増す原因になってしまいます。そこで、トレーナーがオ
ススメの方法を1つだけ説明し、このイベントではその方法を使って「やって
みます」。あえて1つに限定することにより迷いポイントが減り、不安を軽減
できるのではないかという考えです。

そして、オススメの方法を実際に参加者が試してみます。このとき、「こんな
issueを立てて嫌がられないかな…」と「不安」にならないよう、開発対象の
OSSはメンターが開発に関わっているOSSにします。メンターからその場で「そ
れをやっても大丈夫だよ、やってみよう！」と言ってもらえたら、その「不安」
を取りのぞけるのではないかという考えです。

## 目的達成の評価方法

イベント後、「OSS Hack Weekend」までの間に、自分1人でもOSSの開発に参加
できる「気がするか」どうかを判断基準とします。「気がする」なら、OSS開
発への心理的敷居は十分に下がっていて、OSS開発参加への具体的なとっかかり
方法が身についた、と判断します。

（これから新しく使うOSSに対しても問題と思ったことを報告しようと思う、
という判断基準も追加してよさそう。）

## 大事にしたいこと

  * つまづいたらOSSの開発に参加するチャンス！と思う心意気を持ってもらいたい
    * グチって終わり、にはなって欲しくない
    * 自分が通った後に道ができる、くらいの気持ちで行動して欲しい
  * フィードバックするときは相手が理解しやすいように書くということを意
    識してもらいたい
    * リーダブルコードと目指すところは同じ
    * コツ
      * 具体的に書く
      * 省略しない
      * やったことを書く
      * やっていないことも書く
      * 期待していることを書く
      * 実行結果を書く（コマンドの実行とかバックトレースとかもろもろ）
  * インターネット越しの関係では能動的に動かないと情報共有が難しいので困っ
    た時に相談する習慣をつける
    * 自分の状態を理解しやすいように書く（↑を参考に）
  * 楽しむ！

メンターの人の動き方の方針：

  * 答えを教えない（特に自分が開発に関わっているOSSが対象OSSの人は注意！）
  * 自分ならこういうときにどう考えてどう行動するかを伝える
  * 自分がフィードバックを受ける側ならこう受け取る、ということを伝える

## 開始前

  * 参加者は開発OSS別にグループ分けされていること
    * 座席を事前に決めておくのでそこに座ってもらう
  * 参加者はGitHubアカウントが書かれた名札をつけていること
  * 早く着いた参加者にはネットワークの設定をしてもらう
  * 早く着いた参加者には [シナリオ](scenario.md) の説明を読んでいてもらう
  * メンターはGitHubアカウントが書かれた名札をつけていること
  * [事前アンケート](https://creativesurvey.com/reply/34986d55eb5032db38c04bf0facfaf)を書いてもらう

## 10:00 アイスブレーク1

（主催のSEプラスさんによるもの）

## 10:05 OSS開発手順を説明

目的：

  * 参加者がどうやってOSS開発に着手すればよいかわかる

目的のために達成したいこと：

  * トレーナーはスライドを使って↓に書いているやり方を説明する。
    （スライドはoverview/や↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/sezemi-2015-oss-hack-4-beginners-overview/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/sezemi-2015-oss-hack-4-beginners-overview)
  * 一通りの流れがわかる
    * 頭でわかる（知識としてわかる）
    * 見てわかる（実際に自分ができなくてもいい。頭でわかったと思ったことが実際に行われていると知覚できればそれでいい。）

やること：

  * 一通りの流れを説明する
  * 説明した流れを実際のOSSに対してやってみせる
    * 説明の復習と説明だけではピンとこないところの補完、という意図
    * 対象は[DBFlute](http://dbflute.seasar.org/)とする

## 10:50 休憩

10分休憩。

  * [アンケート](https://creativesurvey.com/reply/d77768aa7e81b4a77981156c0d7732)
    を書けるところは今後の休憩の時に随時書いていってねと連絡する。
    （アンケートはタブを閉じても回答を再開可能。）
  * 対象OSSを確認する
    * 対象OSSリスト
      * Java: [Mixer2](http://mixer2.org/site/ja/)
      * Ruby（Rails経験者）: [jpmobile](http://jpmobile-rails.org/)
      * Ruby（Rails未経験者）: [rws-ruby-sdk](https://github.com/rakuten-ws/rws-ruby-sdk)
      * C: [Groonga](http://groonga.org/ja/)
      * Python: [Pikzie](http://pikzie.sourceforge.net/index.html.ja)
      * Node.js: [Sharetary](https://github.com/clear-code/sharetary)
      * PHP（英語に苦手意識がないなら）: [HTTP Accept-Language](https://github.com/zonuexe/php-http-accept-language)
      * PHP（英語に苦手意識があるなら）: [rws-php-sdk](https://github.com/rakuten-ws/rws-php-sdk)

## 11:00 対象OSSを動かす

目的：

  * OSS開発に着手したときに最初にやるべき「動かすこと」を実際にやる

目的達成のために達成したいこと：

  * 困ったら相談するという習慣を身につけて欲しい
    * 実際はリモートで相談することになるが、まずは隣同士、グループ内で相談できるようになる
  * 動かすことに集中する
    * 他のことに手を出したくなるかもしれないけど、まず動かすことが大事、ということを覚えてもらう
  * ドキュメントに不備があるときに、文句を言う（Twitterでアピールするとか）よりも、次にドキュメントを読んだ人が困らないように直しておこう、と考える習慣を身につけてもらう
    * 文句を言うことはスゴイことでもカッコイイことでもない！文句を言っている時間を使って直そう。

やること：

  * forkする
  * ドキュメント（READMEなど）に書いている通りにインストールしてみる
    * ドキュメントにtypoや古い記述など不備があったらforkした自分のリポジトリーのissueにメモしておく。後でpull requestするから。
    * インストール方法や使い方をググる前に公式ドキュメントを参照する習慣をつける。
      ググって見つかる非公式の情報がないと使えないOSSよりも公式ドキュメントを読めばわかるOSSにするべきで、そうなっていないなら私たちが開発に参加してよいものにするべき。
  * インストールできたらドキュメントに書いている通りに動作を確認する
  * グループの他の人がまだ動かせていなかったらフォローする。
  * 動いたら「開発用にインストール」する
    * ドキュメントに不備があったらメモしておくというやり方は「動かす」ときと同じ
  * 「開発用にインストール」できたら「テスト」を動かす
    * ドキュメントに不備があったらメモしておくというやり方は「動かす」ときと同じ
    * テストが動かなかったらメモしておく。やり方は「動かす」ときと同じ。

## 12:00 （昼食: pixivさんご提供の無料ランチ！）

スポンサー（と運営）の人と一緒にランチを食べます。いろんなことを聞くチャ
ンスです。

やること：
  * トレーナーは全体をながめてより多くの人たちが交流できるようにします。
  * 30分経ったらスポンサーチェンジ（スポンサーが他のグループに移動）をする。

## 13:00 スポンサーからのLightning Talk

スポンサー・メンター・インターンシップなどを知る機会です。1社5分ほどお話があります。

登壇予定：

  * ...

## 13:30 対象OSSを動かす（続き）

## 14:50 休憩

10分休憩。

  * [アンケート](https://creativesurvey.com/reply/d77768aa7e81b4a77981156c0d7732)
    を書けるところは今後の休憩の時に随時書いていってねと連絡する。
    （アンケートはタブを閉じても回答を再開可能。）

## 15:00 プロジェクトにフィードバックする

目的：

  * 動かす・開発用にインストール・テストを実際にやってみて気づいたことをOSSプロジェクトにフィードバックすることを「体験」する
    * issueでもpull requestでもよい

目的達成のために達成したいこと：

  * トレーナーはスライドを使って↓に書いているやり方を説明する。
    （スライドはfeedback/や↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/sezemi-2015-oss-hack-4-beginners-feedback/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/sezemi-2015-oss-hack-4-beginners-feedback)

やること：

  * 動かす・開発用にインストール・テストのなかで見つけたドキュメントの
    不備がどんなものか他の人に伝わるようにまとめる
    * わかりにくかったところに対する改善案をまとめるのもよい。
  * まずは自分の考えを整理する
    * OSSの開発ではインターネット越しのやりとりが基本なので、文章で伝える必要がある。
    * 少なくとも自分が理解できるような文章にまとめること。
    * 自分の考えを文章にまとめるのは難しいと思うのでメンターには考えの整理を手伝ってあげて欲しい。
    * まとめたものは自分のissueにコメント。
  * 自分の考えがまとまったら開発者に伝わるようにまとめ直す
    * 「読む人」が理解できることが大事
    * リーダブルコードが目指しているように読む人が理解できるようにまとめてみよう
    * メンターは読む人視点を伝えてあげて欲しい。
    * これもまとめたものは自分のissueにコメント。
  * 実際に報告する
    * これはupstream（開発元）のissueに報告。

## 16:50 休憩

10分休憩。

  * [アンケート](https://creativesurvey.com/reply/d77768aa7e81b4a77981156c0d7732)
    を書けるところは今後の休憩の時に随時書いていってねと連絡する。
    （アンケートはタブを閉じても回答を再開可能。）

## 17:00 まとめ

目的：

  * 今日やったことの意味を再確認する
  * 今日やったことを明日以降に活かす

目的達成のために達成したいこと：

  * トレーナーはスライドを使って↓に書いているやり方を説明する。
    （スライドはconclusion/や↓を参照。）
    * [スライド on Rabbit Slide Show](http://slide.rabbit-shocker.org/authors/kou/sezemi-2015-oss-hack-4-beginners-conclusion/)
    * [スライド on SlideShare](http://www.slideshare.net/kou/sezemi-2015-oss-hack-4-beginners-conclusion)

やること：

  * 今日やったことを再確認
  * 今日やったやりかたの思惑を説明
  * 明日からのヒントを提示
  * 次のステップとしてOSS Hack Weekend情報を提供

## 17:10 質疑応答

  * トレーナーが司会をする
  * 参加者から質問を受け付ける
    * すぐに質問がでない場合はまず[OSS Hack 4 Beginners：メンターのOSS開発参加初期の頃のエピソード](https://github.com/clear-code/sezemi-2015/issues/9)をメンターに紹介してもらう
    * 紹介が1つ終わるごとに参加者に質問がないか聞く

## 17:30 アンケート記入

  * [アンケート](https://creativesurvey.com/reply/d77768aa7e81b4a77981156c0d7732)
    は休憩時間中にも書いてよい

## 18:00 懇親会

そのままpixivさんで懇親会。