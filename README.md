# Take設計 Web

`Take設計` の公開用1ページサイトです。

## ローカルで見る

`index.html` をブラウザで開きます。

## 現在の公開URL

新しい画像付きサイト:

```text
https://site-jet-nine-92.vercel.app
```

旧版サイト:

```text
https://take-design-old.vercel.app
```

GitHubでは、旧版を `main` ブランチに残し、新版を `take-sekkei-v2` ブランチで管理します。

## GitHub Pagesで公開する

この `site` フォルダーをリポジトリのルートとしてGitHubへアップします。

1. GitHubで新規リポジトリを作成する
2. このフォルダーをpushする
3. GitHubのリポジトリで `Settings` -> `Pages` を開く
4. `Source` を `Deploy from a branch` にする
5. Branchを `main`、Folderを `/(root)` にして保存する

公開URLは通常、次の形になります。

```text
https://<GitHubユーザー名>.github.io/<リポジトリ名>/
```

## Vercelで公開する

1. GitHubにこのリポジトリをpushする
2. Vercelで `New Project` を選ぶ
3. GitHubリポジトリを選ぶ
4. Framework Presetは `Other` または自動判定のまま
5. Build Commandは空欄
6. Output Directoryも空欄
7. Deployする

`main` ブランチへpushすると、本番ページが自動更新されます。

## 独自ドメイン

名刺QRコードを作る前に、独自ドメインを決めます。

第一候補:

```text
https://www.take-sekkei.jp/
```

ドメイン取得後、GitHub PagesまたはVercel側で独自ドメインを接続します。
