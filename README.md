# ポートフォリオ

## 概要

Vue.js練習のために制作する。

## 技術・ツールなど

- Vue.js/vue-cli
- yarn
- Github/Git-flow
- Docker/docker-compose

## 動作方法

プロジェクトをクローン

```
$ git clone [URL]
```

プロジェクトのディレクトリに移動

```
$ cd [DIR]
```

dockerコンテナを起動

```
$ docker-compose up -d
```

必要なパッケージをインストール

```
$ docker-compose exec workspace yarn install
```

サーバの起動

```
$ docker-compose exec workspace yarn serve
```
