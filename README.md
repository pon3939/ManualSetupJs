# jsセットアップ手順書

## nodenv

[参照](https://github.com/nodenv/nodenv#basic-github-checkout)

```bash
git clone https://github.com/nodenv/nodenv.git ~/.nodenv
echo 'export PATH="$HOME/.nodenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(nodenv init -)"' >> ~/.zshrc
git clone https://github.com/nodenv/node-build.git ~/.nodenv/plugins/node-build
git clone https://github.com/nodenv/nodenv-update.git ~/.nodenv/plugins/nodenv-update

# ターミナルを再起動
# 全部OKならOK
curl -fsSL https://github.com/nodenv/nodenv-installer/raw/master/bin/nodenv-doctor | bash
```

## Node.js

グローバルに最新のNode.jsをインストール

```bash
nodenv install -l
nodenv install {最新バージョン}
nodenv rehash
nodenb global {最新バージョン}
```

## yarn

```bash
npm install -g yarn
echo 'export PATH="$(yarn global bin):$PATH"' >> ~/.zshrc
```
