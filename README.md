# NBApps developer website

NBAppsのアプリ一覧と、SmartCreCaのAdMob所有者確認に使用する`app-ads.txt`を公開するGitHub Pagesサイトです。

- Webサイト：https://nbashohei.github.io/
- 確認ファイル：https://nbashohei.github.io/app-ads.txt
- SmartCreCa：https://nbashohei.github.io/smartcreca-info/ （App Store ID `992369701`）
- QuickCut：https://quickcut.app/
- 公開元：`main`ブランチのルート

`app-ads.txt`はAdMobの確認画面に表示されたアカウント所有のパブリッシャーIDを使用しています。アプリのソースコード、ユーザーデータ、認証情報は含みません。

AdMobはストアに掲載されたマーケティングURLのホスト名からルートの`app-ads.txt`を取得します。プロジェクトサイトの`/smartcreca-info/app-ads.txt`だけではルートの確認ファイルにならないため、ユーザーサイトのルートで公開します。
