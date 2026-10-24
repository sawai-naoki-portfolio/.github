## 澤井直輝 ポートフォリオ

[![vector Core](https://github.com/sawai-naoki-portfolio/vector/actions/workflows/core.yml/badge.svg)](https://github.com/sawai-naoki-portfolio/vector/actions/workflows/core.yml)
[![LiveDesign test](https://github.com/sawai-naoki-portfolio/LiveDesign/actions/workflows/test.yml/badge.svg)](https://github.com/sawai-naoki-portfolio/LiveDesign/actions/workflows/test.yml)

個人で企画から設計・実装・テストまで手がけた 6 作品です。
スマートフォンアプリ（Flutter）・Web サービス（Node.js）・ゲーム（Unity）と分野は違いますが、どの作品も
**「ロジックを UI から切り離してテストする」「やらないことを決めて理由を残す」「設計を図と文書で説明できるようにする」**
ことを大切にしています。

各リポジトリには、ソースコードのほかに **`Doc/`（要件定義書・画面定義書・設計書・テスト仕様／結果・PlantUML の UML 図・スクリーンショット）** があります。

### 作品一覧

<table>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/vector"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/vector/main/Doc/screenshots/showdown.jpg" alt="VECTOR CASINO RESORT"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/vector">VECTOR CASINO RESORT</a></h3>
10 のオリジナルカジノゲームとカジノ RPG。すべての配当を全列挙・動的計画法で検証し、最善を尽くしてもハウスがわずかに有利になるよう数学で設計。<br>
<b>Unity 6 / C#</b> ・ C# 約 28,000 行 ・ テスト 152 件 ・ CI<br>
<a href="https://github.com/sawai-naoki-portfolio/vector/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/LiveDesign"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/LiveDesign/main/Doc/screenshots/creator-blueprint.png" alt="LiveDesign"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/LiveDesign">LiveDesign</a></h3>
配信画面をデザインし、TikTok LIVE のギフトやコメントで動かす Web サービス。ノードをつなぐだけでゲームを作れる実行環境を一から実装。<br>
<b>Node.js / JavaScript</b> ・ 約 19,600 行 ・ テスト 687 件 ・ CI<br>
<a href="https://github.com/sawai-naoki-portfolio/LiveDesign/blob/main/Doc/README.md">設計ドキュメント</a> ・ <a href="https://github.com/sawai-naoki-portfolio/LiveDesign/blob/main/Doc/api.md">API 仕様書</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/AssetsChecker"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/AssetsChecker/main/Doc/screenshots/01-allocation.png" alt="Privacy Asset Checker" width="60%"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/AssetsChecker">Privacy Asset Checker</a></h3>
サーバーを持たない資産管理アプリ。AES-256 暗号化 DB、暗号化バックアップ、LAN／分割 QR による端末間の引き継ぎ。<br>
<b>Flutter / Dart</b> ・ 約 9,200 行 ・ テスト 81 件<br>
<a href="https://github.com/sawai-naoki-portfolio/AssetsChecker/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/Tech-Tan"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/Tech-Tan/main/Doc/screenshots/03_quiz.png" alt="テク単" width="60%"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/Tech-Tan">テク単</a></h3>
情報処理技術者試験（IP / FE / AP）の単語帳と過去問演習。用語 2,176 語・過去問 9,820 問。表記ゆれに強い検索と大量データの遅延読み込み。<br>
<b>Flutter / Dart</b> ・ 約 10,100 行 ・ テスト 93 件<br>
<a href="https://github.com/sawai-naoki-portfolio/Tech-Tan/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/PromptVault"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/PromptVault/main/Doc/screenshots/04_variable_form.png" alt="PromptVault" width="60%"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/PromptVault">PromptVault</a></h3>
LLM のプロンプトを 1 タップでコピーする管理アプリ。独自の <code>{{変数}}</code> 記法とパーサ、広告でコア体験を壊さない設計。<br>
<b>Flutter / Dart</b> ・ 約 4,300 行 ・ テスト 143 件<br>
<a href="https://github.com/sawai-naoki-portfolio/PromptVault/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/SportsStadium"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/SportsStadium/main/Doc/screenshots/10-basketball.jpg" alt="スポーツスタジアム"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/SportsStadium">スポーツスタジアム</a></h3>
バスケ・テニス・ビーチバレーの 3D スポーツゲーム。自前のボール物理と先読み AI、メッシュ・テクスチャ・音をすべて実行時に生成。<br>
<b>Unity 6 / C#</b> ・ 約 11,000 行 ・ テスト 58 件<br>
<a href="https://github.com/sawai-naoki-portfolio/SportsStadium/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
</tr>
</table>

### 見どころ

| 作品 | 分野 | 主な技術 | 見どころ |
|---|---|---|---|
| [VECTOR CASINO RESORT](https://github.com/sawai-naoki-portfolio/vector) | ゲーム | Unity 6, C#, .NET 8, GitHub Actions | 数学による配当設計（厳密 RTP の検証）、Unity 非依存のルールエンジン、テンプレートメソッドで 10 ゲームを共通化、HMAC によるセーブ保護 |
| [LiveDesign](https://github.com/sawai-naoki-portfolio/LiveDesign) | Web サービス | Node.js 22, Express 5, WebSocket, SQLite, OAuth 2.0, Docker | ノード式プログラミングの実行器、`eval` を使わない式の解釈、Web セキュリティ（CSRF・XSS・総当たり・セッション）、依存の向きをテストで強制 |
| [Privacy Asset Checker](https://github.com/sawai-naoki-portfolio/AssetsChecker) | モバイル | Flutter, Riverpod, SQLCipher, Keychain / Keystore, Kotlin / Swift | 通信しない設計、暗号の検証（既知ベクタ・平文残留）、LAN／分割 QR の引き継ぎプロトコル、課金の取りこぼし対策 |
| [テク単](https://github.com/sawai-naoki-portfolio/Tech-Tan) | モバイル | Flutter, Riverpod, AdMob | 選択肢 3 形式の正規化、表記ゆれの正規化（収録率 32.7% → 46.8%）、19MB の JSON の遅延読み込み、データ整合性テスト、第三者著作物の権利処理 |
| [PromptVault](https://github.com/sawai-naoki-portfolio/PromptVault) | モバイル | Flutter, Riverpod 3, Hive, 課金, AdMob | 独自の変数記法とパーサ、Free / Pro の機能差を 1 か所に集約、確認ダイアログより「元に戻す」、差し替え可能な設計でテスト |
| [スポーツスタジアム](https://github.com/sawai-naoki-portfolio/SportsStadium) | ゲーム | Unity 6, URP, Input System | 解析解で積分する決定論的なボール物理、成否を確率で決めて物理に任せるシュート、3 種目で共通の役割分担、最後まで自動対戦する PlayMode テスト |

### スキル

| 分野 | 技術 | 使った作品 |
|---|---|---|
| モバイル（Flutter / Dart） | Riverpod 2 / 3、SQLite + SQLCipher（AES-256）、Hive、Keychain / Keystore、生体認証・ローカル通知・QR、アプリ内課金・AdMob、MethodChannel（Kotlin / Swift） | Privacy Asset Checker・テク単・PromptVault |
| Web（Node.js / JavaScript） | Express 5、WebSocket、node:sqlite・マイグレーション、scrypt・セッション・OAuth 2.0、CSRF / XSS / CSP 対策、Canvas・Web Audio、ノード式ビジュアルプログラミングの実行器、Docker・Caddy | LiveDesign |
| ゲーム（Unity / C#） | Unity 6・URP・uGUI、Input System、自前のボール物理・先読み AI、手続き的生成（メッシュ・テクスチャ・音）、テンプレートメソッド・SOLID、HMAC によるセーブ改ざん検知 | VECTOR CASINO RESORT・スポーツスタジアム |
| 数理・アルゴリズム | 確率の全列挙・動的計画法、後ろ向き帰納（最善手）、モンテカルロ検証、表記ゆれの正規化、PBKDF2・AES-GCM | VECTOR CASINO RESORT・テク単・Privacy Asset Checker |
| 品質・開発プロセス | 単体・結合・ウィジェット・PlayMode テスト、GitHub Actions（CI）、構造テスト（依存の向き）、静的解析（警告ゼロ）、要件定義・画面定義・UML | 全作品 |

### テストの実行結果（公開版の作成時に再実行したもの）

| 作品 | コマンド | 結果 |
|---|---|---|
| LiveDesign | `npm test`（Node.js 22.22） | 7 ファイル・687 件すべて成功 |
| VECTOR CASINO RESORT | `dotnet test Tools/CoreTests`（.NET 8） | 137 件すべて成功、全ゲームの厳密 RTP が設計値と一致 |
| スポーツスタジアム | `TennisScoreTests`（Unity 非依存の部分を .NET 8 で） | 9 件すべて成功 |

VECTOR CASINO RESORT と LiveDesign は、プッシュごとに GitHub Actions でも同じテストを実行しています（上のバッジ）。
Flutter の 3 作品と Unity のテストは、各作品の開発環境（Flutter 3.44 / Unity 6000.6）で実行しています。結果は各リポジトリの `Doc/test-report.md` を参照してください。

<details>
<summary><b>公開にあたって</b></summary>

それぞれ別のリポジトリで開発していた作品から、**作品を理解・評価するのに必要なものだけ**を移植しています。開発の履歴（コミット）は元のリポジトリにあり、公開版には含めていません。

| 移植していないもの | 理由 |
|---|---|
| ビルド成果物・依存パッケージ・IDE の個人設定 | 再生成できるため |
| AI アシスタント向けの作業メモ | 作品そのものではないため |
| テク単の、収集元サイトが書いた過去問の解説文 | 第三者の著作物のため。自前で書き直した解説（100 問）だけを収録し、スクリーンショットの解説文もぼかしている |
| テク単の、使っていないデスクトップ／Web 向けのプラットフォームフォルダ | 対象は Android / iOS のため |

</details>

### 作者

- **名前:** 澤井直輝
- **連絡先:** naoki.sawai1201@gmail.com

ライセンスは各作品の README を参照してください。
