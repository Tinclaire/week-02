# week-02
## 110306065-王亭宇-資管四
- **安裝的 node.js 版本**
    - v20.10.0
    - 是之前寫 node.js 時載的，當時安裝的也是官方推薦的 long-term support
- **Different between nvm and npm**
    - nvm:
        - node version manager
        - 可以透過 nvm 來切換 node 的版本
        - 常用指令:
            - `nvm install <version>`: 安裝特定版本的 node
            - `nvm ls`: 列出目前電腦上有的版本
            - `nvm alias default node`: 設定 command line default 開啟的 node 版本
            - `nvm use`: 目前 command line 在使用的 node 版本
    - npm:
        - node package manager
        - 可以透過 npm 管理專案中用到的套件
        - 常用指令:
            - `npm init`: 建立專案，產生 `package.json` 紀錄專案使用的 package 等等
            - `npm install`: 會安裝 `package.json` 下的所有 module
            - `npm install <package> --save`: 會安裝這個 package 並寫進 `package.json`
            - `npm start`: 會執行在 `package.json` 中 `scripts` 底下的 `start` (通常是 `node index.js`)

- **Reference**
    - [安裝 nvm 環境，Node.js 開發者必學（Windows、Mac 均適用）](https://www.casper.tw/development/2022/01/10/install-nvm/)
