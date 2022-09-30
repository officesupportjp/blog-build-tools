# blog-build-tools
1. Dockerとdocker-compose をインストールします。

2. このリポジトリをclone します。

3. .env ファイルにgithubを管理しているユーザー名とメールアドレスを入力してください。

4. 以下のコマンドを入力し、コンテナをビルドください。
    ```
    docker-compose build
    ```

5. 以下のコマンドを入力し、コンテナを立ち上げてください。
    ```
    docker-compose up -d 
    ```

6．VScodeのDockerの拡張機能をインストールすることで簡単にコンテナにアクセスできます。
  ![image](https://user-images.githubusercontent.com/72003492/193189439-777add3c-dcd9-4451-944d-35ef03a87e87.png)
  ![image](https://user-images.githubusercontent.com/72003492/193189469-a23ef787-1a90-4c5d-b3a2-ecb0718c32ba.png)

※一度ビルドができていれば、二回目以降は手順4までは必要ありません。



