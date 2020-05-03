# GAS TS Env
This is the environment created for developing Google Apps Script (GAS) with TypeScript.  
You can use Google's "[clasp](https://github.com/google/clasp)" to develop it locally.  
Because it's created locally, it can also be versioned in Git.

## Usage
1. Duplicate the repository by pressing `Use this template` and download it locally.

2. Install the package  
``` bash
$ yarn
```

3. Authenticate clasp with your Google account  
``` bash
$ yarn login
```

4. Create or connect the project  
``` bash
# If there is no project locally
$ yarn make <project-name> # Create a new project
# or
$ yarn clone <project-id> # Connect to an existing project

# If you are already connected to the project
$ yarn pull # Get code from a connected project
```

5. Write whatever you want!

6. Upload to the project  
``` bash
$ yarn push
```

## Reference
* [GAS のGoogle謹製CLIツール clasp](https://qiita.com/HeRo/items/4e65dcc82783b2766c03)
* [claspを使い、Google Apps Scriptプロジェクトをgitでバージョン管理する](https://qiita.com/rf_p/items/7492375ddd684ba734f8)
* [【GoogleAppsScript】ES6を使ったGoogle Apps Scriptの開発](https://qiita.com/romukey/items/22eb4ea6d995d5d62f69)