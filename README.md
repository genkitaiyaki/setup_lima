# setup_lima

私用のmacbookにlimaを導入したときのメモ

## limaとは？

macOS上で動くLinuxの仮想マシン。
Windowsで言うWSLみたいなもの。多分。
詳しくは公式のリポジトリ参照。

> <https://github.com/lima-vm/lima>

## なぜlimaが必要？

今までコンテナ環境使って開発するときは、Docker for Desktopを使っていたが、
ある日一部の利用者はお金がかかるようになってしまった。

> <https://www.docker.com/legal/docker-subscription-service-agreement>

お金かかる条件は妥当だと思うし、自分の使い方だとお金払わなくてもいいんだけど、
代替手段は知ってた方がいい気がしたんで、limaを入れてdockerを動かすことにした。
