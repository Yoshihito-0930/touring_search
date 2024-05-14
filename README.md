# ■サービス概要  
バイク乗りの方向けにツーリングスポットを探してくれるサービスです。  
景勝地や峠道などの「カテゴリ」や「距離や時間」を指定すると現在地から行けるツーリングスポットをお勧めしてくれます。

# ■ このサービスへの思い・作りたい理由  
バイクでツーリングをするのがとても好きで、ツーリングスポットを探す際、以下の手段を活用していました。  
- ブログやSNS、Googleマップ等で検索して探す
- 知り合いやカフェで聞く
- ツーリングマップル等書籍で探す  
上記の手段を活用し、Googleマップで行きたい場所を保存して後日バイクで行っていました。
また、友人と旅先で明日どこ行くかで迷い、時間を割いてツーリング先を決める事もありました。
複数のサービスを跨いでツーリングスポットを探して保存するのは効率が悪く、一つにまとまったサービスを作りたいと思いいたりました。  

# ■ ユーザー層について  
バイク乗りを中心に以下のユーザー向けになります  
- ツーリングスポットを探したい方・探すのが面倒な方
- 同じ場所ばかり行ってしまい飽きてしまった方
- 距離または時間で行き先を決めたい方

自分を含め周りのバイク乗りの方がどういったツーリングをしているか聞いた際、上記の内容が多かったので対象にしました。  

# ■サービスの利用イメージ  
ツーリングスポットを「探す」「保存する」「決める」を一つにまとめたサービスになります。  
複数のサービスを跨がる手間を無くします。

# ■ ユーザーの獲得について  
バイク乗りの中でも、新しいスポットを求めているアクティブなライダーや、週末のみツーリングを楽しむカジュアルなライダーなど

# ■ サービスの差別化ポイント・推しポイント
- 類似のサービスとして以下のサービスがあります。
  - Googleマップ
  - [ツーリングサポーター(有料)](https://play.google.com/store/apps/details?id=com.navitime.local.bike&hl=ja&gl=US&pli=1)

上記のサービスとの差別化として下記のサービスがあります。
- 行きたい場所のカテゴリを決めて検索(峠、展望所、道の駅、神社、キャンプ場等バイク乗りによって乗る目的が分かれているため)
- 走りたい距離または時間で検索（何キロ以上、何分以上等）

# ■ 機能候補  
- MVP
  - ユーザー登録機能
  - ログイン機能
  - パスワードリセット機能
  - 行き先検索, マップ表示(Google Maps APIを利用)
  - 条件検索機能(カテゴリや距離時間の指定)

# ■ 機能の実装方針予定
- 実装予定機能
  - ロケーション保存機能(後で行きたい場所を保存する)
  - ブックマーク機能
  - SNSシェア機能
  - 通知機能(サービスを継続的に使ってもらえるようにメールまたはLINE Messaging APIで保存したロケーションを通知)
  - 経由地追加機能(複数の目的地へ行きたい方向け)


# ■ ER図
[![Image from Gyazo](https://i.gyazo.com/1749643e17bb6ccb9574ac01e283c194.png)](https://gyazo.com/1749643e17bb6ccb9574ac01e283c194)
