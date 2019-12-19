---
marp: true
---

# 僕の自慢のターミナルができることを教える

---

# みんなのターミナルダサすぎない...？

![](https://qiita-user-profile-images.imgix.net/https%3A%2F%2Favatars0.githubusercontent.com%2Fu%2F43776161%3Fv%3D4?ixlib=rb-1.2.2&auto=compress%2Cformat&lossless=0&w=300&s=be1cd982b38b91f9ab59539e51d21efa)
yasudanaoya

twitter: @708yasuda
Qiita, GitHub : yasudanaoya

---

# ちょっと FIXME レベルのものが多すぎるけど。
# 自慢します。

---

# 自己紹介

## 名前
やすだ なおや
## 趣味
- お笑い
- zsh 環境設定
- QIita 芸人
- スノボ
- 邦ロック

---

# 最強ではないけど、色々できるよ

---

# 使っている shell

![](https://www.iconninja.com/files/602/344/903/zsh-icon.png)

---

# 🤔 zsh (z shell) とは？
- unix の command shell の1つ
  - 他には、 bash, fish, csh ...
- Catalina からはデフォルトが bash → zsh に
- 補完機能が bash に比べて強い（らしい）
- 「zsh にできないことがあればバグだ」と言っている人もいる（らしい）

---

# 🤔「zsh がすごいのはわかった、
# が、お前の zsh は何がすごいんだ？」

---

# 僕の zsh ができること

- cd を省略
- cd 後に ls を自動入力
- 常にタイムスタンプを押す
- カレントブランチを常に表示
  - `git branch` の回数を減らす
- カレントディレクトリを常に表示
  - `pwd` がいらなくなる
- ls で表示する情報を、ディレクトリとファイルで色分け
- brew install/uninstall すると自動で Brewfile の更新がかかる
- 履歴検索でワイルドカードが使える

---

# 🤔「何が物足りないの？」

zsh にはプラグインがたくさん用意されています。
有名なものでは、
- ターミナルの見た目を簡単に整える、 `oh-my-zsh`
- ディレクトリの曖昧検索ができる、 `enhancd`
などなど、

しかしそのどれもを使っていません。
なので、それらを使ってもっと強くしたい

---

# alias

docker は長い
- `alias d='docker'`
- `alias dc='docker-compose'`

実行前に「本当に？」って聞いてくれる
- `alias rm='rm -i'`
- `alias cp='cp -i'`
- `alias mv='mv -i'`


---

# 余談 git alias


- `alias.b=branch`
- `alias.s=status`
- `alias.co=checkout`


よく使うものだけ、省略している

---

# 基本的な考え方

- エンジニアは忙しい
- 8時間仕事はできない

---

エンジニアは忙しいのである。
忙しいエンジニアは、仕事を効率的に行えるようにすることで、
時間を確保し、浮いた時間で、ネットサーフィンをする。
そして学習をして、さらなる自己強化を行う

---

僕はこれが、エンジニアのあるべき姿だと思います。

なぜ、仕事を効率的に行うことがえらいのか、
それは、次の仕事をより早く行う為の準備に時間を裂けるから。

それの繰り返しを行えば、単純解明

### 最強のエンジニアになることができる

っちゅー寸法でございます。

---

# 配布してます。

docker image で配布しているので、
image を pull してくれば、簡単に僕のターミナルは手に入れられます。

[Docker Hub Link](https://hub.docker.com/repository/docker/yasudanaoya/initial)

`docker push yasudanaoya/initial:latest`


---

時間があれば、簡単にターミナルを動かす
