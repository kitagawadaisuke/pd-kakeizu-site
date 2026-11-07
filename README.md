# つながる家系図 公開サイト

家系図アプリのサポート・プライバシーポリシー・広告確認ファイルを管理します。

- 公開先: https://pd-kakeizu-site.pages.dev/
- プライバシーポリシー: https://pd-kakeizu-site.pages.dev/privacy-policy.html
- 広告確認: https://pd-kakeizu-site.pages.dev/app-ads.txt
- アプリ本体: https://github.com/kitagawadaisuke/pd-kakeizu

## 公開方法

Cloudflare Pages の `pd-kakeizu-site` プロジェクトへ静的ファイルを直接アップロードしています。GitHubへpushするだけでは公開内容は更新されません。

HTMLファイル、`app-ads.txt`、`_headers`、`kakeizu-support/` と `pd-kakeizu-support/` をZIPにまとめ、Cloudflareの新規デプロイからアップロードします。Git管理情報やREADMEはアップロード不要です。

`app-ads.txt` はドメイン直下に置き、認証なしで取得できる状態を保ちます。

App Store ConnectのサポートURL・プライバシーポリシーURL・マーケティングURLは、リポジトリの変更だけでは更新されません。公開中・審査中のアプリは、旧公開先を終了する前に掲載情報と配布済みアプリ内のリンクを確認してください。
