# Lambda Layer 作成くん for joe

nodejs 用の Lambda Layer を作成して管理するための repo です。

## Synopsis

1. `nodejs` ディレクトリ内で必要なパッケージをインストール( `npm install xxx`)する

   ```
   cd nodejs
   npm install xxxx
   ```

   ちなみにインストール済のパッケージは同ディレクトリ内の `package.json` を参照してください。

2. `nodejs` ディレクトリを zip する

   ```
   # 当レポジトリのトップディレクトリにいるものとします
   zip -r layer.zip nodejs
   ```

3. Lambda Layer としてアップロードする

   AWS コンソールで Go!
