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
1. [このサイト様](https://miiitomi.github.io/p/hugo/)を参考に設定。
1. 公開に関しては[このサイト様](https://qiita.com/ysdyt/items/a581277dd1312a0e83c3#%E3%83%AD%E3%83%BC%E3%82%AB%E3%83%AB%E3%81%A7%E3%82%B5%E3%82%A4%E3%83%88%E8%A1%A8%E7%A4%BA)を参考にする。

## 注意点
- config.yamlのbaseurlは<strong>正確</strong>なurlを記入すること！！
- config.yamlに"canonifyurls: true"を追加しないと何故か上手くサイトが遷移しないぞ！

## 思ったこと
homebrewってlinuxで使えるんだね…