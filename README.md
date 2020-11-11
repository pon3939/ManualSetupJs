# Node.jsセットアップ手順書

## インストール

[参照](https://github.com/nodenv/nodenv#basic-github-checkout)

```bash
git clone https://github.com/nodenv/nodenv.git ~/.nodenv
echo 'export PATH="$HOME/.nodenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(nodenv init -)"' >> ~/.bashrc
git clone https://github.com/nodenv/node-build.git ~/.nodenv/plugins/node-build
git clone https://github.com/nodenv/nodenv-update.git ~/.nodenv/plugins/nodenv-update

# ターミナルを再起動
# 全部OKならOK
curl -fsSL https://github.com/nodenv/nodenv-installer/raw/master/bin/nodenv-doctor | bash
```
