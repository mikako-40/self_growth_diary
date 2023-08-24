# GrowJourney

## サービス概要
GrowJourneyは、達成・解決したことを記録し、自己成長を実感するためのサービスです。

##　想定されるユーザー層
RUNTEQ受講生、20代〜30代の自分自身の成長が感じにくくなり、モチベーションが低下している人。

## サービスコンセプト
* ユーザーが抱えている課題感と提供するサービスでどのように解決するのか

ユーザーが抱えている課題: 社会に出てからは目に見える成長が少なく、自己肯定感やモチベーションが低下しやすい。

サービスでの解決: GrowJourneyは、ユーザーが日常の成功や成長を簡単に記録し、可視化します。
ユーザーが自身の振り返りを行うことで、達成感を持ち、成長を実感できるよう支援します。

* なぜそのサービスを作ろうと思ったのか:

社会人として働く中で、自分自身成長できているのか不安に思うことや、悩むことが度々ありました。
その度に新入社員の頃や、新しい業務をし始めた時のことを思い出し、
どれだけ出来なかったことがあったか、どれだけ今できるようになっていることがあるかを羅列、認識し、モチベーションに繋げていました。
達成したことや、解決した問題を記録し、振り返ることで自己肯定感が高まり、モチベーションの向上に繋がると思っています。
そのため、日常の小さな成功を記録しすることで、自分自身の成長について実感してもらえるサービスを作ろうと思いました。

* どのようなサービスにしていきたいか:

ユーザーの成長を視覚的に示し、過去の自己と比較できるようにすることで、成長を実感できるようにしたいです。

* どこが売りになるか、差別化ポイントになるか:

  * 視覚的成長の実感が可能
    * ユーザーが目標を達成するたびに花が咲く独自の視覚的アニメーションを提供します。
      他のノートや日記アプリとは異なり、本数を表示するとこで、より目に見える成長を強調し、ユーザーに達成感を提供します。

  * SNS共有機能
    * X(旧:Twitter)で目標の宣言や達成を共有できる機能を持っています。
      これにより、ユーザーは友達やフォロワーと目標達成を共有し、モチベーションを維持できます。
      他のタスク管理アプリと比較して、ソーシャルな要素が強化されています。　

  * LINE通知機能
    * ユーザーが目標を設定し、期限を設定すると、リマインダー通知を受け取ることができます。
      この機能により、ユーザーは目標を達成するための計画を守りやすくなります。

　日記アプリやタスク管理アプリ、習慣化アプリの長所を組み合わせたようなサービスです。


## 実装を予定している機能
### MVP
* 会員登録(LINE)
* ログイン
* 目標・課題一覧
* 目標・課題登録
* 目標・課題詳細
* 達成一覧
* X(旧:Twitter)での共有(目標、達成したとき、達成した花の本数)
* マイページ(アイコン画像アップロード)
* アニメーション機能
  * 達成する度に花が咲くアニメーションgifを表示させる

### その後の機能
* リマインド機能(LINE通知)
  * ユーザーが設定した目標・課題期限をLINE通知でお知らせしてくれる機能
* カテゴリ別の目標設定機能
  * 仕事・家事・健康・趣味など
* ご褒美の設定機能(画像アップロード)
  * 何本達成したら〇〇買う、〇〇するなど
* 応援機能
  * 公開されている他ユーザーの目標に応援ボタンを押せる

### 使用技術・バージョン
### バックエンド
- Ruby 3系
- Rails 7系
- MiniMagick
- CarrierWave
### フロントエンド
- JavaScript
- Tailwind CSS
- daisyUI
### インフラ
- Heroku
- Amazon S3
- PostgreSQL