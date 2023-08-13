# bookApp web frontend

## 実行方法
BookAppディレクトリ直下で
> docker compose up
コマンドを使用

もしエラーが出た際は、docker-compose.ymlファイル内の

-    command: >
-      sh -c "npm i && npm start"
+    command: >
+      sh -c "npm install -g npm && npm i && npm start"

を書き換えて再度実行

