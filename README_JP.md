# GAS ES6+ Env
これはGoogle Apps Script（以下、GAS）をECMA Script6以上（以下、ES6+）で開発するために作られた環境です。  
Googleの"[clasp](https://github.com/google/clasp)"を使い、ローカルで開発できるようになっています。  
ローカルで作成するため、Gitでバージョン管理することも可能です。

## 使い方
1. [github-download-parts](https://github.com/pspgbhu/github-download-parts)を使ってダウンロードします
```
npm i -g github-download-parts
repo -r "windchime-yk/gas-es6-env" -t local_folder
```

2. パッケージをインストールします  
```
npm i
```

3. claspをインストールします  
claspをローカルインストールしたい場合は`npm run setup:local`、グローバルインストールしたい場合は`npm run setup:global`とコマンドに入れてください。  
このコマンドを叩くとclaspがインストールされ、すぐにGoogleアカウントの認証画面が出現します。

4. プロジェクトを作成ないし複製します  
`npm run create -- projectName`で新しいプロジェクトが作成されます。すでにプロジェクトがある場合は`npm run clone -- projectID`を使ってください。  
なお、プロジェクトと接続済みの状態で`npm run pull`を使えば、既にあるプロジェクトからGASのコードを持ってくることができます。

5. 好きに書いてください  
`npm run dev`を使えば、src内部のJavaScriptを変更監視してbabelで出力します。  
`npm run build`を使うと、変更監視のない出力が使えます。

6. プロジェクトにアップロードします  
`npm run push`でローカルのコードをGASのプロジェクトにアップロードします

## 参考資料
* [GAS のGoogle謹製CLIツール clasp](https://qiita.com/HeRo/items/4e65dcc82783b2766c03)
* [claspを使い、Google Apps Scriptプロジェクトをgitでバージョン管理する](https://qiita.com/rf_p/items/7492375ddd684ba734f8)
* [【GoogleAppsScript】ES6を使ったGoogle Apps Scriptの開発](https://qiita.com/romukey/items/22eb4ea6d995d5d62f69)