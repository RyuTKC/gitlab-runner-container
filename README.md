## 使い方

### 1. 起動後、shellにログイン
  ```sh
  docker exec -it gitlab-runner /bin/bash
  ```

### 2. ログイン後、下記のコマンドを入力
  ```sh
  gitlab-runner register
  ```

### 3. 指示に従って項目を入力する
  1. gitlabホストurl
  2. token
  3. docker実行