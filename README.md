TypeScript + Node.js のサンプルプロジェクト
==========

本プロジェクトを使用すると TypeScript + Node.js のプログラミングをすぐに開始できます。


### 手順

1. ```git clone``` を実行 
    ```
    $ git clone https://github.com/seabat/typescript-node-starter.git
    ```
2. typescript-node-starter/ に移動
3. ```npm install``` を実行
4. src/index.ts を編集
5. ```npx tsc``` を実行
6. ```node dist/index.js``` を実行するとプログラムが動作する

### lint

本プロジェクトでは、 [Eslint](https://eslint.org/) によるコードスタイルチェックと、 [Prettier](https://prettier.io/) によるコードフォーマットを実行することができます。

* lint の実行
  ```
  npm run lint
  ```
* コードフォーマットの実行
  ```
  npm run lint:fix
  ```