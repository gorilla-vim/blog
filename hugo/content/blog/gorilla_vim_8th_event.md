---
title: "ゴリラ.vimの勉強会#8を開催しました"
date: 2019-09-20
draft: false
author: hoda
image: images/blog/blog-post-2.jpg
description: "ゴリラ.vimの勉強会（8回目）を開催しました。入力補完のプラグイン、ライブコーディング、オレオレvimrcの公開、vimでdockerのコマンドやモニタリングができるプラグイン、vimに出会った話など、実用的なものからエモい話まで、濃い情報がシェアされました。"
categories:
  - "blog"
tags:
  - "勉強会"
---

2019年9月26日(木)、8回目の勉強会を開催、CCC マーケティング株式会社様が会場を提供してくださいました。

## 内容

|発表内容                                           |登壇者       |
|---------------------------------------------------|-------------|
|coc.nvim使ってみたらとても良かった話               |Takumi Kawase|
|Flutter + Vim ライブコーディング                   |yasukotelin  |
|自分のvimrcについて                                |pocke        |
|docker.vimの話                                     |ゴリラ       |
|スポンサードセッション〜2019年、vimに出会ったsummer|Miura_Ryoichi|
|スポンサードセッション                             |forkwell様   |

入力補完のプラグイン、ライブコーディング、オレオレvimrcの公開、vimでdockerのコマンドやモニタリングができるプラグイン、vimに出会った話など、実用的なものからエモい話まで、濃い情報がシェアされました。登壇者のみなさま、情報の共有をありがとうございます！

## coc.nvim使ってみたらとても良かった話
Takumi Kawase

vimで補完

coc.nvimはこれ一つ入れればlspも入るので、導入が楽チン

coc.jsonで設定を全部つっこむスタイル

確かnode.jsが必要だったはず。

coc.list拡張機能
deniteっぽいファインダー機能？

lspは補完だけじゃない

## Flutter + Vim ライブコーディング
yasukotelin

ダートプラグイン syntax highlight

Flutterは便利

Androidの開発もFlutterで。

## 自分のvimrcについて

pocke

vimからコマンドを実行するプラグイン

NeoVundleという死んだプラグイン

goのif err, nilのあれはそこにあるということがわかればいいので、グレー文字にして目立たなくさせる。

## docker.vimの話
ゴリラ

dockerでよく使う機能をvimで操作できるプラグイン

コンテナのログ、使用率のモニタリング

dockerデーモンがあって、裏ではRestAPIが動いている。
裏でcurlとかcuiを使ってdockerのAPIを叩くスクリプトをvim scriptで書いている。

docker.vimを使えば、コーディングしながらdockerの操作が行えて便利

## vimに会ったsummer

慣れると編集スピードが速いし、技が決まると楽しい。

vimチューター
vim adventures
vim
