## redis-nodejs-client
redis-nodejs-clientは、node.jsで動作する(マイクロサービス)ランタイムにおいて、redis を使用する際に用いる、メタライブラリです。  
本ライブラリのインストールは、各システム環境やエッジコンピューティングデバイス内におけるランタイムの特性に応じて、必要に応じて行ってください。  

## 動作環境

* OS: Linux  
* CPU: ARM/AMD/Intel  
* Node js Runtime  

## 導入方法

本リポジトリを npm、またはyarn でインストールしてください。
```
npm install git+ssh://github.com/latonaio/redis-nodejs-client
```
本リポジトリに格納されている package.jsonで、ライブラリの構築を行ってください。

```json
{
  "name": "redis-nodejs-client",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+ssh://git@bitbucket.org/latonaio/redis-nodejs-client.git"
  },
  "author": "",
  "license": "MIT",
  "bugs": {
    "url": "https://bitbucket.org/latonaio/redis-nodejs-client/issues"
  },
  "homepage": "https://bitbucket.org/latonaio/redis-nodejs-client#readme",
  "dependencies": {
    "ioredis": "^4.17.3" // この箇所に適切なバージョンに変更してください
  }
}

```