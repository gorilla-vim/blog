# ゴリラ.vimのブログ

ゴリラ.vimのブログの雛形です！

# 起動条件

ローカルで確認する場合は`docker`と`docker compose`、または`HUGO`が必要です。

- Docker
- Docker Compose
- HUGO

# ローカルでの起動方法

ローカルで起動するにはリポジトリをクローンする必要がありますが、  
gitのsubmoduleが含まれているので、下記のコマンドでクローンします。

```
git clone --recursive git@github.com:gorilla-vim/gorilla.vim-blog.git
```

すでに通常のコマンドでクローンしてしまった場合は下記のコマンドでsubmoduleを更新します。

```
git submodule init
git submodule update
```

## docker composeで起動する場合

クローンしたリポジトリのディレクトリへ移動し、`docker compose up`します。

```
cd gorilla.vim-blog
docker-compose up -d
```

コンテナ起動後、`localhost:1313`へアクセスすることでブログを閲覧できます。

# 記事の書き方

整理中

# ランディングページの作成方法

`hugo/content/`ディレクトリ配下に.mdファイルを置く。ルートも自動で設定される。

```
# 例：下記の場合、about、contact、next-eventのページが設定される。
# posts/ディレクトリにはブログ記事を置く。

content
├── about.md
├── contact.md
├── next-event.md
└── posts
    └── 1st-post.md
```

# 本番へのデプロイ

Netlifyで公開します。

developブランチまたはfeatureブランチを切って記事を書き、masterへのプルリク時にNetlify側でCIが走ります。

エラーがでなければ、マージ後に自動でデプロイされます。

Netlifyのビルド時のコマンドと公開ディレクトリは`netlify.toml`にて設定。

# Author

[Hoda](https://hodalog.com)
