## 自作プログラム

### [rifff《ﾘｭﾌﾌ》](https://tools.nakaix.com/rifff/)

リッチテキスト対応の差分表示ツール。テキストの差分だけでなく、太字・斜体・下線・上付き・下付きといった書式の変化もオレンジ色でハイライトして検出します。Word 等からコピー＆ペーストで書式を保ったまま貼り付けられ、インストール不要、ブラウザだけで動作します。完全ローカル処理でデータはどこにも送信されません。

### [fuseji《ふせじ》](https://fuseji.jp)

AIサービスへのテキスト入力前に個人情報を伏せ字に置き換えるプライバシー保護ツール。登場人物ごとに {氏名1}・{氏名2} と番号付きラベルを自動で割り当てるため、複数人が登場しても文脈が維持されます。氏名・メールアドレス・電話番号・住所・組織名などを一括検出し、AIの出力をラベルから元の語句に逆変換する機能も備えています。インストール不要、ブラウザだけで動作します。完全ローカル処理でデータはどこにも送信されません。

### [GIFT Checker](https://tools.nakaix.com/gift-checker/)

MoodleのGIFT形式で記述した問題ファイルを、ブラウザだけで文法チェック・プレビュー・動作確認できるシングルファイルHTMLツールです。式中の"="が正解選択肢として誤登録されるといった、気づきにくいミスも取り込み前に検出します。インストール不要、ブラウザだけで動作し、完全ローカル処理でデータはどこにも送信されません。

### [mwcalc](https://tools.nakaix.com/mwcalc/)

分子量計算ツール。1995年に作成したMS-DOS版をブラウザ向けに移植したものです。化学式からのリアルタイム計算に加え、全118元素の周期表をクリックして式を組み立てる機能や、計算の途中式を段階的に表示する機能を備えており、化学初学者の学習にも役立ちます。インストール不要、ブラウザだけで動作します。完全ローカル処理でデータはどこにも送信されません。

### [dnacnv](https://tools.nakaix.com/dnacnv/)

DNA配列をアミノ酸配列に変換し、コドン使用頻度を表示するWebツール。2000年にPerlで作成したCGIプログラムをHTML+JavaScriptに移植したもので、インストール不要、ブラウザだけで動作します。完全ローカル処理でデータはどこにも送信されません。

## 移植プログラム

### [difff《ﾃﾞｭﾌﾌ》JS版](https://tools.nakaix.com/difff-js/)

Webベースのテキスト比較ツール [difff《ﾃﾞｭﾌﾌ》](https://difff.jp/) のJavaScript移植版。オリジナルのdifffの中で呼び出されているUnix diffプログラムもJavaScriptに移植することで動作を忠実に再現しました。完全ローカル処理でデータはどこにも送信されません。

## 開発者について

### プロフィール：Tadashi NAKAI, Ph.D., Professor

大学でライフサイエンス分野の研究を行う傍ら、生成AIを活用したプログラミング（vibecoding）による業務効率化やツール開発を行っています。個人の活動をまとめた総合トップページは [www.nakaix.com](https://www.nakaix.com) です。自作ツール群は [Tools](https://tools.nakaix.com) にまとめています。また、学術的な資料やアーカイブは [Repository](https://repository.nakaix.com) に、日常の話題や雑記は [Blog](https://blog.nakaix.com) に掲載しています。日々の開発状況は [X (Twitter)](https://x.com/TadashiNakai) でも発信中です。

### 開発ノート・関連記事

* [2026年07月05日: Moodleに取り込む前に。GIFT問題をブラウザで確認・演習・印刷できる「GIFT Checker」を作りました](https://nakaix.hatenablog.com/entry/20260705)
* [2026年07月04日: rifff《ﾘｭﾌﾌ》をv1.15に更新——戻ってきたFable 5は「こんにちは」すら返してくれなかった](https://nakaix.hatenablog.com/entry/20260704)
* [2026年06月14日: rifff《ﾘｭﾌﾌ》をv1.14に更新——不便だと思っていなかった。AIにそう言われるまでは。](https://nakaix.hatenablog.com/entry/20260613)
* [2026年06月12日: rifff《ﾘｭﾌﾌ》をv1.13に更新——公開しているツールに、自分の知らない行があった](https://nakaix.hatenablog.com/entry/20260612)
* [2026年06月07日: rifff《ﾘｭﾌﾌ》をv1.12に更新——差分エンジンを GNU diff（Myers法）に置き換え、長い行で崩れる問題を解消しました](https://nakaix.hatenablog.com/entry/260607)
* [2026年05月31日: 残り24時間のClaudeトークンから始まった、rifff作者のdifff移植記](https://nakaix.hatenablog.com/entry/2026/05/31/000000)
* [2026年04月26日: 1995年に書いた分子量計算プログラムを、AIと一緒にWebアプリに移植してみた——化学を学ぶ高校生・大学生にも使ってほしい](https://nakaix.hatenablog.com/entry/2026/04/26/020917)
* [2026年04月26日: rifff v1.9 リリース：論文PDFの改行を自動吸収する差分ツール — 査読現場で生まれた機能](https://nakaix.hatenablog.com/entry/2026/04/26/000000)
* [2026年04月11日: Xの利用規約、また変わっていたのをご存知だろうか ― 新旧対照表がないなら、自分で作ればいい](https://nakaix.hatenablog.com/entry/x-tos-updated-2026)
* [2026年03月29日: ChatGPTに貼る前に個人情報を安全に除去できるツール fuseji《ふせじ》を作りました](https://nakaix.hatenablog.com/entry/2026/03/29/165437)
* [2026年03月29日: difff《ﾘｭﾌﾌ》をずっと使ってきた人へ——書式の差分も見える rifff《リュフフ》を作りました](https://nakaix.hatenablog.com/entry/2026/03/29/123106)
