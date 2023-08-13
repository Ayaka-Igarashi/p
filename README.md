# bookApp web frontend

## 実行方法
BookAppディレクトリ直下で
`docker compose up`
コマンドを使用

もしエラーが出た際は、docker-compose.ymlファイル内の

(-)    command: >

(-)      sh -c "npm i && npm start"

(+)    command: >

(+)      sh -c "npm install -g npm && npm i && npm start"

を書き換えて再度実行

実行後、

`book_co_web  | webpack 5.88.2 compiled successfully in 2512 ms`

と出たら成功。
localhost:3000にアクセスすればページを表示できる
