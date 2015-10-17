# test_repo
[![Build Status](https://travis-ci.org/opabinia/test_repo.svg?branch=master)](https://travis-ci.org/opabinia/test_repo)
[![Build Status](https://travis-ci.org/opabinia/test_repo.svg?branch=develop)](https://travis-ci.org/opabinia/test_repo)

## 概要
テスト用のリポジトリです。

- Gradleによるプロジェクト管理
- gitでの複数人での開発の手法
- TravisCIを用いた継続インテグレーション
- IntelliJ IDEAの使い方

とかのノウハウの獲得を目的としています。

## ビルドツール
ビルドツールにはGradle2.7を使用しています。

自動生成された設定ファイルをそのまま流用しているから特に言うことはないよ。

## TravisCI
今回はTravisCIを使用します。

そもそも継続インテグレーションが必要なのかっていう意見は受け付けないよ。
取り合えず私の継続インテグレーションに対する認識ってのは

> テストに失敗するコミットをした人を全自動で吊し上げられる22世紀の秘密道具

ぐらいしかないです。

## git-flow
git自体はやろうとすればいくらでもトリッキーな運用ができますが、それだとさすがにチームでの開発に支障が出るので今回はgit-flowに従った運用をします。

## プルリクエスト
ってどうでしょう。正直`master`ブランチにダイレクトにコミットされなければ正直プルリクまではする必要が無いんじゃないかなーと思うのですが、意見下さい。
