# BroadCue（ブロードキュー）

LoL の配信に、スポーツ中継のようなグラフィックを重ねる、無料の HUD です（OBS Studio 用）。

**ダウンロード：[Releases のページ](https://github.com/T0NYS0PP/BroadCue/releases/latest) から `BroadCue-v〇.〇.〇.zip` を落としてください。**

## できること

- 試合が始まると、自動で出ます：スコア、キル速報、ニュース風の見出し、集団戦の集計、ペンタキルのバナー、10分ごとのチームスタッツ、試合結果、全員の強さ（POWER）と試合の心電図
- アカウントの登録も、API キーも要りません。自分の PC の中で動きます
- OBS Studio への追加は、ボタン1つです
- 色・書体・角の丸み・大きさを、自分なりに変えられます
- バロンやドラゴンを取ったときに、自分で用意した映像やロゴを、画面いっぱいに出せます

## 使い方

1. zip を展開して、`start.bat` をダブルクリックします（Windows が警告を出したら「詳細情報」→「実行」）
2. 開いた画面のいちばん上で「自動で追加する」を押します
3. OBS を起動します（起動していたら、閉じて起動し直します）
4. LoL の試合を始めます

くわしい説明は、zip の中の `README.txt` にあります。

## 動作環境

Windows 10／11、OBS Studio、League of Legends（サモナーズリフト）。画面は 1920×1080 を前提にしています。

## 新しい版が出たら

コントロールパネルのいちばん上に「新しい版が出ています」と出ます。自動では入れ替わりません。

1. このページの Releases から、新しい zip を落とします
2. 黒いウィンドウを閉じます（BroadCue を止めます）
3. 新しい zip の中身を、いまのフォルダに上書きします（設定の入った `data` フォルダは zip に入っていないので、そのまま残ります）
4. `start.bat` を開き直します。OBS のソースは、そのまま使えます

## 知っておいてほしいこと

- インターネットに出る通信は、チャンピオンとアイテムの画像・値段の取得（Riot の Data Dragon）、書体の取得（Google Fonts）、新しい版があるかの確認（この GitHub のリポジトリ。起動のときと、1日に1回。オフにできます）です。試合のデータは、自分の PC の外には送りません
- 「外の統計」（OP.GG・DEEPLOL の統計のカード）は、初めはオフです。オンにする前に、zip の中の `README.txt` の「知っておいてほしいこと」を読んでください
- 推定ゴールドなどの「推定」と書いてある数字は、スコアボードに見えている情報から出した目安です

## お問い合わせ

不具合や要望は、このリポジトリの Issues に書いてください。

---

BroadCue は Riot Games が承認・提供しているものではありません。League of Legends および Riot Games は、Riot Games, Inc. の商標または登録商標です。

BroadCue isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
