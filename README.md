# バトスピ コアヘルパー

バトルスピリッツの一人回しで、2つのデッキのコアを管理する非公式の補助ツールです。Androidアプリ版と、ブラウザーで使うHTML版があります。

## ブラウザーですぐ使う

**[バトスピ コアヘルパーを開く](https://tsmskwri-gif.github.io/battlespirits-core-helper/)**

インストール不要です。スマートフォンやPCのブラウザーで開いて使えます。開くときはインターネット接続が必要です。オフラインで使う場合は、下のAPK版またはHTML版をダウンロードしてください。

## ダウンロード

- **[Android版 APKをダウンロード](https://github.com/tsmskwri-gif/battlespirits-core-helper/releases/latest/download/BattleSpiritsCoreHelper.apk)**
- **[HTML版をダウンロード](https://github.com/tsmskwri-gif/battlespirits-core-helper/releases/latest/download/battlespirits_core_helper.html)**

[最新版の配布ページ](https://github.com/tsmskwri-gif/battlespirits-core-helper/releases/latest)からもダウンロードできます。ページ下部の **Assets** で必要なファイルを選んでください。

| ファイル | 用途 |
| --- | --- |
| `BattleSpiritsCoreHelper.apk` | Androidにインストールして使う |
| `battlespirits_core_helper.html` | ダウンロードしてブラウザーで開く |

`Source code (zip)` と `Source code (tar.gz)` はGitHubが自動で付けるソースの圧縮ファイルです。アプリのインストールにはAPKを選んでください。

## できること

- 2つのデッキのリザーブ・トラッシュ・場・ライフを管理
- ソウルコアの場所を管理
- よく使うコア移動をボタンで操作
- ターン開始時の処理と操作ログを表示
- デッキ名を自由に入力（初期値は空欄）
- 操作後の状態を端末内に自動保存

Android版は全画面表示に対応し、端末の回転設定に合わせて縦・横で使えます。戻る操作では終了確認を表示します。表示中は画面が自動消灯しません。

## Android版の使い方

Android 6.0以上が対象です。Pixelで起動・操作・再起動後の保存状態を確認しています。

1. Releasesから `BattleSpiritsCoreHelper.apk` をダウンロードします。
2. AndroidのファイルアプリでAPKを開きます。
3. インストール許可が必要と表示された場合は、APKを開いたアプリに対して許可します。
4. インストール後、アプリ一覧の「バトスピ コアヘルパー」から起動します。

利用時のインターネット接続は不要です。アプリはインターネット・ストレージの権限を要求しません。

## HTML版の使い方

`battlespirits_core_helper.html` をダウンロードして、JavaScriptとlocalStorageを利用できるブラウザーで開いてください。HTML・CSS・JavaScriptは1ファイルにまとまっています。

## 保存データについて

保存先は端末内です。Web版・Android版・ダウンロードしたHTML版、異なる端末・ブラウザーの間でデータは共有されません。

アプリのアンインストールやデータ消去、ブラウザーの保存データ消去をすると、保存していた状態も失われます。

## このツールについて

通常コアはエリアごとの数、ソウルコアは場所を管理します。個々のカード上のコア配分は、実物のコアやダイスと併用してください。カードのドローや回復、対戦ルールの判断は自動では行いません。

本ツールは個人制作の非公式ツールです。
