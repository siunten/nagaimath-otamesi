# Math Lab prototype 0.1

生徒がブラウザで触って学べる数学教材の試作品です。

## 内容

- `index.html` : トップページ
- `trig.html` : 数学II「三角関数の平行移動・周期・振幅」
- `solid.html` : 数学III「回転体ができる様子」
- `style.css` : 共通デザイン

すべてHTML/CSS/JavaScriptだけで動く静的サイトです。APIキーやサーバー処理はありません。

## PCで試す

`index.html` をダブルクリックしてブラウザで開いてください。

## GitHub Pagesで公開する手順

1. GitHubで新しいRepositoryを作成します（例: `math-lab`）。
2. このフォルダ内の4ファイル `index.html`, `trig.html`, `solid.html`, `style.css` をRepositoryの一番上にアップロードします。
3. Repositoryの `Settings` → `Pages` を開きます。
4. `Build and deployment` の Source を `Deploy from a branch` にします。
5. Branch を `main`、Folder を `/(root)` にして保存します。
6. 数分後、Pages画面に公開URLが表示されます。

例: `https://ユーザー名.github.io/math-lab/`

## 今後追加できるもの

- cos / tan の切り替え
- y = a sin b(x-c)+d の係数入力
- 課題モード（「周期をπにせよ」など）
- 回転軸をy軸に変更
- 区間を自由指定
- 円盤・薄い断面を表示して回転体の体積公式につなぐ
- 正誤判定、学習履歴、問題演習
