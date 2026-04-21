<div align="center">
	<br />
	<br />
	<img src="./assets/logo.png" alt="DevHub LOGO" width="160" height="160">
	<h1>DevHub</h1>
  <!--rehype:style=border: 0;-->
  <p>
		<a href="./README.md">English</a> • 
		<a href="./README.zh.md">中文</a> • 
		<a href="#よくある質問">FAQ</a> • 
		<a target="_blank" href="https://wangchujiang.com/#/contact">Contact & Support</a>
  </p>
  <p>
    <a href="https://github.com/jaywcjlove/DevHub/releases" target="_blank">
      <img src="https://img.shields.io/github/v/release/jaywcjlove/DevHub?color=3b82f6" alt="Release" />
    </a>
    <img src="https://img.shields.io/badge/macOS-14%2B-363b44?logo=apple&logoColor=white" alt="macOS 14+" />
    <a href="https://jaywcjlove.github.io/maslink/?id=6476452351" target="_blank">
      <img src="https://img.shields.io/badge/Downloads-AppStore-363b44?logo=AppStore&logoColor=white" alt="Scap AppStore" />
    </a>
  </p>
  <p>
    <a target="_blank" href="https://jaywcjlove.github.io/maslink/?id=6476452351" title="DevHub AppStore"><img alt="DevHub AppStore" src="https://jaywcjlove.github.io/sb/download/macos.svg" height="51">
    </a>
  </p>
</div>

DevHub は、macOS 向けのオフライン開発者ツールボックスです。日常的な開発作業のために設計されており、ローカル実行、データプライバシー、高頻度で使う小さなユーティリティの一元化を重視しています。

私は積極的に開発を進めており、毎週更新をリリースするという大胆な目標を掲げています。私はスリムなフットプリントを維持し、100以上のユーティリティを含む広範なコレクションをキュレーションすることを目指しています。これにより、開発者に多様なツールを提供します。この取り組みは、継続的な改善へのコミットメントを反映しており、開発者に豊富なツールを提供します。DevHubは単なるコーディングの仲間ではありません。

## DevHub とは？

DevHub は macOS 向けのローカルファーストな開発者向け生産性アプリです。テキスト処理、コード整形、エンコードとデコード、画像ユーティリティ、API リクエスト、日時ツール、QR コード、ハッシュや鍵、ファイル情報やデバイス情報など、よく使う機能を 1 つにまとめています。IDE を置き換えるのではなく、散在した Web ツール、シェルスクリプト、一時的なユーティリティサイトを置き換えることを目指しています。

次のような製品を探している場合、DevHub はその検索意図にかなり合っています。

- macOS 向け開発者ツールボックス
- オフラインで使える開発者ツール
- ローカル実行のプログラマー向け効率化ツール
- プライバシーに配慮した開発支援アプリ
- 多数の小さな開発者ツールをまとめたオールインワンアプリ

## 主な特徴

- `オフライン優先`：主にローカル利用を前提としており、プライバシーや安定性を重視する場面に向いています。
- `高頻度で使う開発者ツールを集約`：タイムスタンプ、JSON、Base64、URL、JWT、QR コード、正規表現、ハッシュ、画像ユーティリティなどを 1 つのアプリにまとめています。
- `macOS 向け`：Mac 開発者向けの統一された軽量なツール入口です。
- `URL スキーム対応`：Raycast、ブラウザ、ターミナル、各種自動化ワークフローと連携できます。
- `継続的に拡張`：ツールを増やしながら、頻繁なアップデートを続けることを目標にしています。

## どんな人に向いている？

- フロントエンドエンジニア：JSON、URL、Base64、HTML、CSS、QR コード、色、画像アセットを扱う人。
- バックエンドエンジニア：JWT、ハッシュ、Basic Auth、RSA 鍵、タイムスタンプ、API リクエスト、データ変換を扱う人。
- QA / DevOps エンジニア：正規表現、Crontab、ポート、権限、時刻、デバイス情報を扱う人。
- インディー開発者：日常作業のために、ローカルで高速かつ切り替えコストの低いツール群を必要とする人。

## よくある利用シーン

- JSON、HTML、URL、Base64、JWT などのよく使う開発データを素早く整形・確認する。
- QR コード、バーコード、WiFi QR コード、イベント QR コード、名刺 QR コードを生成する。
- EXIF、ファイル情報、画像の色を抽出したり、画像に透かし、背景塗りつぶし、プライバシーぼかしを適用する。
- パスワード、ハッシュ、RSA 鍵を生成したり、各種エンコード、デコード、形式変換を行う。
- URL スキームを使って、Raycast や個人用自動化ワークフローから特定ツールを呼び出す。

## カバーしているツール領域

現在の DevHub は、開発者がよく使う複数カテゴリのツールをカバーしています。たとえば以下のようなものがあります。

- `テキストとエンコード`：Base64、Unicode、ASCII、HTML エンコード/デコード、テキストケース変換、単語数カウント、モールス信号。
- `コードとデータ`：JSON 整形、HTML から Markdown、Prettier、正規表現テスト、URL 解析、JWT 解析。
- `画像とメディア`：OCR、画像透かし、ICO 変換、画像から Base64、色抽出、EXIF 表示。
- `効率化とシステム`：世界時計、日付変換、クロノメーター、ランダムポート生成、デバイス情報、ファイル情報、Chmod 計算機。
- `セキュリティとネットワーク`：API リクエスト、SSL 管理、ハッシュ生成、Basic Auth 生成、RSA 鍵生成。

![DevHub screenshots-1](./assets/screenshots-1.png)

以下のツールが完成しています：

- [x] タイムスタンプ
- [x] HTMLをMarkdownに変換
- [x] NATOフォネティックアルファベットに変換
- [x] CodeMirror テキストエディタ
- [x] Prettier コードフォーマット
- [x] HTML フォーマットと圧縮ツール
- [x] MIME タイプ
- [x] Base64/ファイルコンバーター
- [x] SVG を CSS に変換
- [x] JWT パーサー
- [x] 人民元大字（人民幣の大字表記）
- [x] 世界時計
- [x] ファイル情報
- [x] 画像テキスト認識
- [x] ファイル名抽出ツール
- [x] SSLマネージャー
- [x] 画像透かし
- [x] NPM統計
- [x] プライバシーぼかし
- [x] テキストカード
- [x] アプリアイコン
- [x] 画像カラー抽出
- [x] カーソルハイライト
- [x] 背景フィラー
- [x] APIリクエスト
- [x] 正規表現テスト
- [x] Chmod計算機
- [x] Crontabジェネレーター
- [x] 日付変換ツール
- [x] デバイス情報
- [x] パスワード生成
- [x] ライフカウントダウン
- [x] 温度変換ツール
- [x] テキスト読み上げ
- [x] PX/REM変換ツール
- [x] バーコード生成
- [x] ランダム数生成
- [x] データサイズ変換ツール
- [x] QRコードリーダー/生成
- [x] WiFi QRコード生成
- [x] イベントQRコード生成
- [x] 名刺QRコード生成
- [x] ランダムポート生成
- [x] RSAキー生成
- [x] カラー変換ツール
- [x] ランダムカラー
- [x] クロノメーター
- [x] ASCIIから文字列
- [x] 文字列からASCII
- [x] ハッシュ生成
- [x] ベーシック認証生成
- [x] EXIFビューア
- [x] 画像からBase64
- [x] ICO変換ツール
- [x] HTMLエンコード/デコード
- [x] HTMLプレビュー
- [x] 文字列エクスプローラー
- [x] テキストからBase64
- [x] テキストからUnicode
- [x] テキストケース
- [x] テキスト差分
- [x] ワードカウンター
- [x] モールスアルファベット
- [x] JSONフォーマッター
- [x] ランダムテキスト生成
- [x] UUID生成
- [x] URLパーサー
- [x] URLエンコード/デコード

![DevHub screenshots-2](./assets/screenshots-2.png)
![DevHub screenshots-3](./assets/screenshots-3.png)
![DevHub screenshots-4](./assets/screenshots-4.png)
![DevHub screenshots-5](./assets/screenshots-5.png)
![DevHub screenshots-6](./assets/screenshots-6.png)
![DevHub screenshots-7](./assets/screenshots-7.png)

## よくある質問

### DevHub とは？

DevHub は macOS 向けのオフライン開発者ツールアプリで、多くの開発用小ツールを 1 つにまとめ、Web ツール、シェルスクリプト、別々のアプリを行き来する手間を減らします。

### DevHub はどんな課題に向いていますか？

JSON の整形、JWT の解析、Base64 変換、QR コード処理、画像情報の抽出、ハッシュ生成、日時形式の確認など、開発中に頻繁に発生する小さな作業に向いています。

### DevHub はどのプラットフォームに対応していますか？

README では最低動作要件として `macOS 14.0` が明記されています。

### DevHub はオフラインで使えますか？

はい。DevHub はオフラインかつローカルファーストな開発者向けツールアプリとして位置付けられており、オンラインツールに依存したくない場面や、より機密性の高いデータを扱う場面に向いています。

### DevHub はデータを収集またはアップロードしますか？

リポジトリ内のプライバシーポリシーによると、DevHub はローカルのオフラインアプリとして説明されており、個人を特定できる情報や機密情報を能動的に収集、保存、送信しないとされています。詳細は [Privacy Policy](./privacy-policy.md) を参照してください。

### DevHub はオンラインの Web ツールと何が違いますか？

DevHub はローカル実行、統一された入口、コンテキストスイッチの削減、プライバシーに配慮したワークフローを重視しています。開発用ツールを繰り返し使う人にとっては、複数の Web サイトを行き来するより効率的です。

### DevHub は他のツールと連携できますか？

はい。DevHub は URL スキームに対応しているため、Raycast、ブラウザ、ターミナル、各種自動化ワークフローと連携できます。

### DevHubの統合

DevHubとの統合はURLスキームを介して行われます。これを使用して、ほとんどのアプリやワークフローと統合できます。例えば、Raycastとの統合：

![DevHub + Raycast](./assets/raycast.png)

**URLスキーム**

DevHubは、URLを介してツールをアクティブにするためのさまざまなコマンドとパラメーターをサポートしています。例えば、次のようにリンク（HTMLページなど）で使用できます：

```html
<a href="devhub://qrCodeEventGenerator">ここをクリック</a>
```

または**Terminal.app / CLI**から：

```bash
# Terminal.appまたはbashで入力：
open "devhub://qrCodeEventGenerator"
```

または、これをブラウザのアドレスバーにコピーしてEnterキーを押します： `devhub://qrCodeEventGenerator`

<!--idoc:config:
title: 開発者統合ツール - 
-->
