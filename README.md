# Node.jsセットアップ手順書

## インストール

aptだと古いバージョンがインストールされるので、バージョン管理パッケージの`n`からインストールする

```bash
sudo apt install nodejs npm
sudo npm install -g n
sudo n stable
sudo apt remove nodejs npm #aptでインストールしたのは削除
```

↓は`n`でインストールしたNode.jsを使うため、ログインしなおしてから

```bash
sudo npm install -g yarn
```
