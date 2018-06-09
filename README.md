# GAS ES6 Template
Google Apps Script ES6+ development environment.  
"clasp" use. clasp is Google made GAS local dev CLI.

## Usage
1. [Download](https://github.com/windChimeYK/gas-es6-template/archive/master.zip) and unzip
2. Package install  
```
npm i
```
3. Setup  
`npm run setup` used "clasp" global install and your google acount authorize.  
if you want "clasp" local install, `npm i -D @google/clasp` and `npm run login` used.
4. Create or Clone  
`npm run create -- projectName` is new GAS project create.  
if GAS project already create, `npm run clone -- projectID` used. `npm run pull` use this GAS project code download.
5. Coding
6. Push  
`npm run push` your GAS project.

## Reference
* [GAS のGoogle謹製CLIツール clasp](https://qiita.com/HeRo/items/4e65dcc82783b2766c03)
* [claspを使い、Google Apps Scriptプロジェクトをgitでバージョン管理する](https://qiita.com/rf_p/items/7492375ddd684ba734f8)
* [【GoogleAppsScript】ES6を使ったGoogle Apps Scriptの開発](https://qiita.com/romukey/items/22eb4ea6d995d5d62f69)