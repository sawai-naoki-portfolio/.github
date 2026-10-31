## 澤井直輝 ポートフォリオ

[![vector Core](https://github.com/sawai-naoki-portfolio/vector/actions/workflows/core.yml/badge.svg)](https://github.com/sawai-naoki-portfolio/vector/actions/workflows/core.yml)
[![LiveDesign test](https://github.com/sawai-naoki-portfolio/LiveDesign/actions/workflows/test.yml/badge.svg)](https://github.com/sawai-naoki-portfolio/LiveDesign/actions/workflows/test.yml)
[![SWING-LLM CI](https://github.com/sawai-naoki-portfolio/SWING-LLM/actions/workflows/ci.yml/badge.svg)](https://github.com/sawai-naoki-portfolio/SWING-LLM/actions/workflows/ci.yml)
[![bokitan-app test](https://github.com/sawai-naoki-portfolio/bokitan-app/actions/workflows/test.yml/badge.svg)](https://github.com/sawai-naoki-portfolio/bokitan-app/actions/workflows/test.yml)

個人で企画し、生成 AI（Claude Code）を使って開発した 8 作品です。
スマートフォンアプリ（Flutter）・Web サービス（Node.js）・ゲーム（Unity）・AI（Python / PyTorch）と分野は違いますが、どの作品も
**「ロジックを UI から切り離してテストする」「やらないことを決めて理由を残す」「設計を図と文書で説明できるようにする」**
ことを大切にしています。

**このページの見方**

1. 下の作品一覧で、作品ごとの概要・技術・規模・開発時期をつかむ
2. 気になった作品の「設計ドキュメント」（`Doc/README.md`）で、伝えたいことと技術的な課題・解決を読む（3 分ほど）
3. さらに詳しく見るときは、各作品の `Doc/design.md`（設計書・UML 図）と `Doc/test-report.md`（テスト仕様・結果）へ

### 作品一覧

<table>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/vector"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/vector/main/Doc/screenshots/showdown.jpg" alt="VECTOR CASINO RESORT"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/vector">VECTOR CASINO RESORT</a></h3>
10 のオリジナルカジノゲームとカジノ RPG。配当を全列挙・動的計画法（厳密に解けないものはシミュレーション）で検証し、最善に近い打ち方でもハウスがわずかに有利になるよう数学で設計。<br>
<b>Unity 6 / C#</b> ・ C# 約 28,000 行 ・ テスト 152 件 ・ CI<br>
2025 年 4 月に原型、2026 年 10 月に作り直し ・ 未公開<br>
<a href="https://github.com/sawai-naoki-portfolio/vector/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/LiveDesign"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/LiveDesign/main/Doc/screenshots/creator-blueprint.png" alt="LiveDesign"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/LiveDesign">LiveDesign</a></h3>
配信画面をデザインし、TikTok LIVE のギフトやコメントで動かす Web サービス。ノードをつなぐだけでゲームを作れる実行環境を一から実装。<br>
<b>Node.js / JavaScript</b> ・ 約 19,600 行 ・ テスト 687 件 ・ CI<br>
2026 年 8 月〜10 月 ・ 未公開（手元や Docker で起動可）<br>
<a href="https://github.com/sawai-naoki-portfolio/LiveDesign/blob/main/Doc/README.md">設計ドキュメント</a> ・ <a href="https://github.com/sawai-naoki-portfolio/LiveDesign/blob/main/Doc/api.md">API 仕様書</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/AssetsChecker"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/AssetsChecker/main/Doc/screenshots/01-allocation.png" alt="Privacy Asset Checker" width="60%"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/AssetsChecker">Privacy Asset Checker</a></h3>
サーバーを持たない資産管理アプリ。AES-256 暗号化 DB、暗号化バックアップ、LAN／分割 QR による端末間の引き継ぎ。<br>
<b>Flutter / Dart</b> ・ 約 9,200 行 ・ テスト 81 件<br>
2026 年 7 月 ・ 未公開（Google Play 公開準備中）<br>
<a href="https://github.com/sawai-naoki-portfolio/AssetsChecker/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/Tech-Tan"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/Tech-Tan/main/Doc/screenshots/03_quiz.png" alt="テク単" width="60%"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/Tech-Tan">テク単</a></h3>
情報処理技術者試験（IP / FE / AP）の単語帳と過去問演習。用語 2,176 語・過去問 9,820 問。表記ゆれに強い検索と大量データの遅延読み込み。<br>
<b>Flutter / Dart</b> ・ 約 10,100 行 ・ テスト 93 件<br>
2026 年 7 月 ・ 未公開<br>
<a href="https://github.com/sawai-naoki-portfolio/Tech-Tan/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/PromptVault"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/PromptVault/main/Doc/screenshots/04_variable_form.png" alt="PromptVault" width="60%"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/PromptVault">PromptVault</a></h3>
LLM のプロンプトを 1 タップでコピーする管理アプリ。独自の <code>{{変数}}</code> 記法とパーサ、広告でコア体験を壊さない設計。<br>
<b>Flutter / Dart</b> ・ 約 4,300 行 ・ テスト 143 件<br>
2026 年 7 月 ・ 未公開<br>
<a href="https://github.com/sawai-naoki-portfolio/PromptVault/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/SportsStadium"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/SportsStadium/main/Doc/screenshots/10-basketball.jpg" alt="スポーツスタジアム"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/SportsStadium">スポーツスタジアム</a></h3>
バスケ・テニス・ビーチバレーの 3D スポーツゲーム。自前のボール物理と先読み AI、メッシュ・テクスチャ・音をすべて実行時に生成。<br>
<b>Unity 6 / C#</b> ・ 約 11,000 行 ・ テスト 58 件<br>
2026 年 10 月 ・ 未公開<br>
<a href="https://github.com/sawai-naoki-portfolio/SportsStadium/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/SWING-LLM"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/SWING-LLM/main/Doc/screenshots/03-tool-calc.png" alt="SWING-LLM"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/SWING-LLM">SWING-LLM</a></h3>
LLM・音声合成・画像生成の 3 つの AI を、既製のモデルを使わずゼロから自作。MLA＋MoE の LLM、止まっても壊れない学習パイプラインと評価ゲート、同意が必須の声のクローンと電子透かし。<br>
<b>Python / PyTorch / FastAPI</b> ・ 約 29,600 行 ・ テスト 762 件 ・ CI<br>
2026 年 6 月〜10 月 ・ 未公開（学習済みの重みは含まない）<br>
<a href="https://github.com/sawai-naoki-portfolio/SWING-LLM/blob/main/Doc/README.md">設計ドキュメント</a> ・ <a href="https://github.com/sawai-naoki-portfolio/SWING-LLM/blob/main/Doc/api.md">API 仕様書</a>
</td>
<td width="33%" valign="top">
<a href="https://github.com/sawai-naoki-portfolio/bokitan-app"><img src="https://raw.githubusercontent.com/sawai-naoki-portfolio/bokitan-app/main/Doc/screenshots/01_search.png" alt="簿記単" width="60%"></a>
<h3><a href="https://github.com/sawai-naoki-portfolio/bokitan-app">簿記単</a></h3>
簿記用語 1,373 語と仕訳問題 270 問の単語帳アプリ。同梱データを貸借一致などで検証するテスト、消去法で解けない勘定科目の選択肢、起動直後の操作で保存データを失わない読み込み待ち。<br>
<b>Flutter / Dart</b> ・ 約 8,300 行 ・ テスト 34 件 ・ CI<br>
2025 年 5〜7 月に初期開発、2026 年 7 月・10 月に改修<br>
<a href="https://github.com/sawai-naoki-portfolio/bokitan-app/blob/main/Doc/README.md">設計ドキュメント</a>
</td>
<td width="33%" valign="top"></td>
</tr>
</table>

簿記単以外の 7 作品は、ストアや Web ではまだ公開していません。各リポジトリの README に、手元で動かす手順があります。

### 開発の進め方（生成 AI の活用）

8 作品とも、生成 AI のコーディングアシスタント **Claude Code** を使って開発しました。

| | 内容 |
|---|---|
| 自分で行ったこと | 企画（何を・誰のために作るか）、仕様決め、設計の判断（何を作らないかを含む）、AI が書いたコードのレビュー、テストでの検証 |
| AI を活用したこと | 実装と、README・設計資料（`Doc/`）などのドキュメント作成 |
| 動作を確かめる仕組み | ロジックを UI から切り離した単体テスト、GitHub Actions の CI（VECTOR・LiveDesign・SWING-LLM・簿記単）、配当の全列挙とシミュレーションによる裏付け（VECTOR）、依存の向きを強制する構造テスト（LiveDesign）、学習パイプラインに組み込んだ評価ゲート（SWING-LLM） |

| 作品 | 開発時期（コミットの記録） |
|---|---|
| VECTOR CASINO RESORT | 2025 年 4 月に Unity・C# に初めて挑戦して原型を制作（14 日間）、2026 年 10 月 21〜22 日に設計から作り直し |
| LiveDesign | 2026 年 8 月 11 日〜10 月 18 日 |
| Privacy Asset Checker | 2026 年 7 月 28〜30 日 |
| テク単 | 2026 年 7 月 28〜29 日 |
| PromptVault | 2026 年 7 月 28 日 |
| スポーツスタジアム | 2026 年 10 月 20〜21 日 |
| SWING-LLM | 2026 年 6 月 23 日〜7 月 17 日、10 月 25 日 |
| 簿記単 | 2025 年 5〜7 月（初期開発）、2026 年 7 月・10 月（改修・リリース準備・ドキュメント整備） |

### 見どころ

| 作品 | 分野 | 主な技術 | 見どころ |
|---|---|---|---|
| [VECTOR CASINO RESORT](https://github.com/sawai-naoki-portfolio/vector) | ゲーム | Unity 6, C#, .NET 8, GitHub Actions | 数学による配当設計（厳密 RTP の検証）、Unity 非依存のルールエンジン、テンプレートメソッドで 10 ゲームを共通化、HMAC によるセーブ保護 |
| [LiveDesign](https://github.com/sawai-naoki-portfolio/LiveDesign) | Web サービス | Node.js 22, Express 5, WebSocket, SQLite, OAuth 2.0, Docker | ノード式プログラミングの実行器、`eval` を使わない式の解釈、Web セキュリティ（CSRF・XSS・総当たり・セッション）、依存の向きをテストで強制 |
| [Privacy Asset Checker](https://github.com/sawai-naoki-portfolio/AssetsChecker) | モバイル | Flutter, Riverpod, SQLCipher, Keychain / Keystore, Kotlin / Swift | サーバーを持たない設計（通信は課金と LAN 引き継ぎだけ）、暗号の検証（既知ベクタ・平文残留）、LAN／分割 QR の引き継ぎプロトコル、課金の取りこぼし対策 |
| [テク単](https://github.com/sawai-naoki-portfolio/Tech-Tan) | モバイル | Flutter, Riverpod, AdMob | 選択肢 3 形式の正規化、表記ゆれの正規化（収録率 32.7% → 46.8%）、大容量の過去問 JSON（解説込みで約 19MB）の遅延読み込み、データ整合性テスト、第三者著作物の権利処理 |
| [PromptVault](https://github.com/sawai-naoki-portfolio/PromptVault) | モバイル | Flutter, Riverpod 3, Hive, 課金, AdMob | 独自の変数記法とパーサ、Free / Pro の機能差を 1 か所に集約、確認ダイアログより「元に戻す」、差し替え可能な設計でテスト |
| [スポーツスタジアム](https://github.com/sawai-naoki-portfolio/SportsStadium) | ゲーム | Unity 6, URP, Input System | 解析解で積分する決定論的なボール物理、成否を確率で決めて物理に任せるシュート、3 種目で共通の役割分担、最後まで自動対戦する PlayMode テスト |
| [SWING-LLM](https://github.com/sawai-naoki-portfolio/SWING-LLM) | AI | Python 3.12, PyTorch, FastAPI, WebSocket, SentencePiece, FAISS, GitHub Actions | MLA・MoE・MTP の LLM を部品から自作、止まっても壊れない学習パイプライン（アトミックな保存・中断できるコーパス作成）、評価ゲートで弱点も数値で記録、声のクローンの同意ゲートと電子透かし、サンドボックスと Web の境界防御 |
| [簿記単](https://github.com/sawai-naoki-portfolio/bokitan-app) | モバイル | Flutter, Riverpod, shared_preferences, AdMob, GitHub Actions | 起動直後の操作で保存データが巻き戻らない読み込み待ち、同梱データを直接検証するテスト（貸借一致・ID 重複）で見つけた問題データの誤りを修正、誤答候補を混ぜた最低 10 択の勘定科目で消去法を防止、JSON のパースを別 isolate へ、広告 ID をソースに置かない注入 |

### スキル

| 分野 | 技術 | 使った作品 |
|---|---|---|
| モバイル（Flutter / Dart） | Riverpod 2 / 3、SQLite + SQLCipher（AES-256）、Hive、Keychain / Keystore、生体認証・ローカル通知・QR、アプリ内課金・AdMob、MethodChannel（Kotlin / Swift） | Privacy Asset Checker・テク単・PromptVault・簿記単 |
| Web（Node.js / JavaScript） | Express 5、WebSocket、node:sqlite・マイグレーション、scrypt・セッション・OAuth 2.0、CSRF / XSS / CSP 対策、Canvas・Web Audio、ノード式ビジュアルプログラミングの実行器、Docker・Caddy | LiveDesign |
| ゲーム（Unity / C#） | Unity 6・URP・uGUI、Input System、自前のボール物理・先読み AI、手続き的生成（メッシュ・テクスチャ・音）、テンプレートメソッド・SOLID、HMAC によるセーブ改ざん検知 | VECTOR CASINO RESORT・スポーツスタジアム |
| AI・機械学習（Python / PyTorch） | Transformer（Multi-Head Latent Attention・Sparse MoE・RoPE・KV キャッシュ・投機的デコード）、事前学習・SFT・DPO・GRPO・LoRA、RAG（BM25・FAISS・RRF・Self-RAG）、TTS（ニューラル音声コーデック・Flow Matching）、画像生成（VAE・DiT・Rectified Flow）、評価設計、FastAPI・WebSocket | SWING-LLM |
| 数理・アルゴリズム | 確率の全列挙・動的計画法、後ろ向き帰納（最善手）、モンテカルロ検証、表記ゆれの正規化、PBKDF2・AES-GCM | VECTOR CASINO RESORT・テク単・Privacy Asset Checker |
| 品質・開発プロセス | 単体・結合・ウィジェット・PlayMode テスト、GitHub Actions（CI）、構造テスト（依存の向き）、静的解析、要件定義・画面定義・UML、生成 AI を使った開発 | 全作品（CI は VECTOR・LiveDesign・SWING-LLM・簿記単、PlayMode テストはスポーツスタジアム、構造テストは LiveDesign） |

### テストの実行結果（公開版の作成時に再実行したもの）

| 作品 | コマンド | 結果 |
|---|---|---|
| LiveDesign | `npm test`（Node.js 22.22） | 7 ファイル・687 件すべて成功 |
| VECTOR CASINO RESORT | `dotnet test Tools/CoreTests` と `Tools/Simulator`（.NET 8） | テスト 137 件すべて成功。厳密に計算できるゲームの RTP が設計値と一致 |
| スポーツスタジアム | `TennisScoreTests`（Unity 非依存の部分を .NET 8 で） | 9 件すべて成功 |
| SWING-LLM | `python -m tests.run_unit_tests`・ruff・mypy（Python 3.12、CPU） | 80 ファイル・762 件で失敗 0（学習済みの重み・外部 API が必要な 7 件はスキップ）。静的解析も問題なし |
| 簿記単 | `flutter test`・`flutter analyze`（Flutter 3.47.8） | 34 件すべて成功。静的解析の指摘なし |

VECTOR CASINO RESORT・LiveDesign・SWING-LLM・簿記単は、プッシュごとに GitHub Actions でも同じテストを実行しています（上のバッジ）。
簿記単以外の Flutter の 3 作品と Unity のテストは、公開版の作成時には再実行していません（作業環境に Flutter・Unity がないため）。テストの内容と件数は、各リポジトリの `Doc/test-report.md` にあります。

<details>
<summary><b>公開にあたって</b></summary>

それぞれ別のリポジトリで開発していた作品から、**作品を理解・評価するのに必要なものだけ**を移植しています。開発の履歴（コミット）は元のリポジトリにあり、公開版には含めていません。

| 移植していないもの | 理由 |
|---|---|
| ビルド成果物・依存パッケージ・IDE の個人設定 | 再生成できるため |
| AI アシスタント向けの作業メモ | 作品そのものではないため |
| テク単の、収集元サイトが書いた過去問の解説文 | 第三者の著作物のため。自前で書き直した解説（100 問）だけを収録し、スクリーンショットの解説文もぼかしている |
| テク単の、使っていないデスクトップ／Web 向けのプラットフォームフォルダ | 対象は Android / iOS のため |
| SWING-LLM の学習済みの重み | 学習で生成するため |
| SWING-LLM の学習用に集めた論文の本文と Wikipedia のコーパス | 第三者の著作物のため。パイプラインが取得し直す |

VECTOR CASINO RESORT のパッケージ名（`com.dorachan121.vector`）やストア用の資料に出てくる「dorachan121」は、開発に使っている個人アカウントの名前です。

</details>

### 作者

- **名前:** 澤井直輝
- **連絡先:** naoki.sawai1201@gmail.com
