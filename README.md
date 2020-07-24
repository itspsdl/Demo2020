個人プロジェクト制作物デモ大会・プログラム
========

* 日時
   * 2020年7月21日（火） 17:15-18:55（9-10限）
   * 2020年7月22日（水） 17:15-18:55（9-10限）
* 場所: Zoom
   * 参加を希望される方は ![](http://www.se.cs.titech.ac.jp/~hayashi/mail) までご連絡ください．
* デモ: 1件10分程度（発表7-8分，質疑1-2分程度）

---

## 7月21日（火）17:15-

### イントロダクション

### [Online Visual Localization APP based on SfM and Feature Matching](https://github.com/LeeYiZhou/OnlineVisualLocalization)（Yizhou Li）
First, users can use the phone camera to take images of the scene.
The images will be uploaded to the server, and the 3D point cloud and the camera locations/poses corresponding to each image will be estimated by the SfM algorithm.
The user can view the 3D point cloud through the 3D viewer.

In addition, users can also take another image through the mobile phone.
Then, by finding the most similar image by comparing with the features (such as SIFT features) of the existing scene images, the algorithm will return the camera locations/poses corresponding to this newly input image.

Then, the user can see where he was in the 3D scene when he took the image.

### [顔隠しカメラ](https://github.com/tehhuu/Face-Hiding-Camera)（張 浩達）
写真を撮ったのはいいけど、顔をさらけ出したまま他人に共有するのは怖い…と感じたことは誰しもがあるでしょう。
そこで、撮った写真の顔をうまく隠して保存できるアプリを作りました。
これで気にせず写真を共有できます！

### フェイスフォトtheセレクト（原 大樹）
このアプリは、複数の顔写真の中から、写りが最も良い写真を選び出します。
これまで、顔写真をLINEやInstagram等のアプリで共有する際、カメラで何枚も撮影して見比べて一番良い写真を選んでいたと思います。
その手間を省き、判断も均質にするのがこのアプリです。
内臓カメラと連携し、瞬時に人工知能によって適切な写真を選び出します。
また、選んだ写真を他アプリで共有する機能もあります。

### [似たような画像検出アプリ](https://github.com/Xuan-Zhang-20/SimilarImageDetection)（Zhang Xuan）
既存の写真管理アプリを使えば、デバイス上の写真を管理することができます。
しかし、Androidシステムの写真アプリには類似画像を検出する機能はありません。
例えばpixivのようなサイトを利用している人は、重複した画像をダウンロードしていることが多いです。
だから、デバイス上で類似した画像を見つけるためにこのアプリを設計し、ユーザーが重複した画像を削除できるようにします。

### [Circular Dotter](https://github.com/g2xpf/CircularDotter)（辻 裕太）
スマートフォンでドット絵を描いて保存することができるアプリ。
このアプリを開いた状態でスマートフォン本体を回転させることで、描画色や筆サイズの選択、塗りつぶしツールの利用など、様々な操作の切り替えが可能になっている(予定)。

### [ポケモン対戦支援アプリ](https://github.com/shohataka/pokeCapture)（所畑 貴大）
Nintendo Switchのゲーム「ポケットモンスター ソード・シールド」における対戦の支援アプリ。
カメラで相手のパーティの写真を撮ることでポケモンを認識してパーティの保存、過去の記録から選出率の計算をしてくれる。

---

## 7月22日（水）17:15-

### イントロダクション
  
### [二度寝防止目覚まし](https://github.com/tiot07/Alarm)（木村 友祐）
アラームを止めた後、端末の加速度情報を収集する。
集めた情報から、動いていないと判定された場合は一定時間後に再度アラームが鳴る。
動いているかどうかを判定する閾値は、端末を手に持っていたり、使用せずともポケットに入れていればクリアする程度に調整する。

### [Focus](https://github.com/esperanto9657/Focus)（朱 嘉基）
Focusはユーザーが勉強や仕事に集中したいときに、ついついスマートフォンに手を出してしまわないよう監視してくれるアプリです。
加速度センサーで動きを察知したり、アプリの切り替えを検知したりした時にアラートを鳴らし、設定した時間内に無事集中できた時はスコアを加算してモチベーション維持をサポートします。

### [Pinner](https://github.com/Durun/Pinner)（安藤 直樹）
カレンダーに写真や書類をピン留めする感覚で、日時と情報をリンクさせ、指定した時間にリマインドできるアプリです。
Google Calendarと連携し、写真や文書ファイル、テキストやリンクをカレンダーに登録することで機能を実現します。

### [何食べるかを決めるやつ](https://github.com/RyotaroShin/sdl.myApplication)（進 亮太朗）
出かけた時に、何を食べるのかを悩むことはありませんか？
僕はあります。
そこで、近くにある飲食店からランダムに店を選択するアプリを制作しました。

### [RandomWalker](https://github.com/RMitsui/RandomWalker)（三井 亮称）
RandomWalkerは現在地を出発し現在地に戻ってくるお散歩経路をランダムで提案するアプリです。
自分では選ばないような道を使って街を歩けば、新しい発見があるかもしれません。
提案されたお散歩経路を使ってGoogleMapアプリに経路案内させたり、経路案内を行うリンクを取得出来ます。
また、散歩する時間と方角を設定することが出来ます。

### [IIDX Result Manager](https://github.com/wtks/android-iidx-result-manager)（岸本 崇志）
音楽ゲーマーは、自分の成長を記録したりプレイを友達に自慢するために、リザルト画面の写真を頻繁に撮る。
その結果、カメラロールがリザルト写真で埋まり、しかもアルバムの小さなサムネイル表示ではどれが何のプレイのリザルトなのかがよく分からない問題が発生する。
これを解決するために、僕が遊んでる音楽ゲームであるbeatmania IIDXに特化したリザルト写真管理アプリを開発する。
  
### [聖地キャプチャ](https://github.com/Advanjef/HolyLandCapture)（日野 健人）
画像を透かしながら写真を撮ることができる．
スマホに保存されている画像を選択し、この画像の透明度を調整しながらカメラのプレビューができる．
画角を調整しそのまま写真を撮影できるため、元の画像と似たアングルの写真を簡単に撮ることができる．
  
