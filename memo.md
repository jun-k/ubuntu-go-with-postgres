## ＜ステップ１＞ Go の開発環境準備

<参考> [VSCodeとDockerでMacにGolangの開発環境を作成する](https://dev.classmethod.jp/articles/vscode-remote-containers-golang/)

1. 適当なフォルダを作成する。
2. 作成したフォルダを vscode で開く。
3. 左下の緑のボタンをクリックして、 `Add Dev Container Configuration files...` を選択する。
4. Select a container configuration template から [Ubuntu] を選択する。
5. Select additional features to install で [Go devcontainers] の チェックボックスをオンにして `OK`

## ＜ステップ２＞ Dockerfile を使用

<参考> [Using a Dockerfile](https://containers.dev/guide/dockerfile#dockerfile)

## ＜ステップ３＞ Docker Compose でイメージを使用

<参考> [Using an image with Docker Compose](https://containers.dev/guide/dockerfile#docker-compose-image)

## ＜ステップ４＞ Docker Compose で Dockerfile を使用

<参考> [Using a Dockerfile with Docker Compose](https://containers.dev/guide/dockerfile#docker-compose-dockerfile)