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

## 継続インテグレーション
今回はTravisCIを使用します。

そもそも継続インテグレーションが必要なのかっていう意見は受け付けないよ。
取り合えず私の継続インテグレーションに対する認識ってのは

> テストに失敗するコミットをした人を全自動で吊し上げられる22世紀の秘密道具

ぐらいしかないです。

## git
### フローモデル
git自体はやろうとすればいくらでもトリッキーな運用ができますが、それだとさすがにチームでの開発に支障が出るので今回はgit-flowに従った運用をします。

逆にgithub-flowはラピッドリリースを繰り返す場合には適用可能ですが、どうしてもリリースの粒度が大きくなる今回のプロジェクトの場合は適用が出来なさそうなのでやめます。

### プルリクエスト
メインのリポジトリはOrganizationアカウント上にホストして、各人のアカウントにフォークして変更を行い、Pull-Requestで本体のリポジトリに反映させる方式を取ります。

なので、取り合えず[anomalocarisのリポジトリ](https://github.com/anomalocaris/test_repo)からフォークしてください。

## 練習的な何か
取り合えずテストに失敗するメソッドをプッシュしておくので、練習として

1. 自分のアカウントにフォークする
2. ローカルで変更する
3. 自分のアカウントにプッシュする
4. anomalocarisの本体のリポジトリにPull-Requestを送る

ってのをやってみてください。
