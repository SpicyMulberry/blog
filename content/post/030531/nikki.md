+++
author = "スパイシーな桑の木"
title = "hugoを使ってブログを公開するまでの手順"
date = "2022-06-19"
description = "hugoの環境導入からブログ公開までの手順メモ"
tags = [
    "hugo",
    "homebrew"
]
categories = [
    "メモ",
]
series = [""]
aliases = ["migrate-from-jekyl"]
+++
<!--more-->

## hugoを使ったブログ導入手順

1. wsl2を有効化してubuntuとwindows terminal入れる（wtは任意）。
1. homebrewを入れる（aptでインストールされたhugoはバージョンが古くて使いたいブログのテーマが使えない！かといって自分でビルドするのはめんどい！）。
1. [このサイト様](https://miiitomi.github.io/p/hugo/)を参考に設定、公開する。

## 注意点
- config.yamlのbaseurlは<strong>正確</strong>なurlを記入すること！！
- config.yamlに"canonifyurls: true"を追加しないと何故か上手くサイトが遷移しないぞ！

## 思ったこと
homebrewってlinuxで使えるんだね…