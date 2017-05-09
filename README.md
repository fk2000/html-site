# html-site

[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://fk2000.github.io/html-site/)
[![wercker status](https://app.wercker.com/status/c8ace35b47bfe55812a369ac960a6ab0/s/master "wercker status")](https://app.wercker.com/project/byKey/c8ace35b47bfe55812a369ac960a6ab0)
[![wercker status](https://app.wercker.com/status/c8ace35b47bfe55812a369ac960a6ab0/m/master "wercker status")](https://app.wercker.com/project/byKey/c8ace35b47bfe55812a369ac960a6ab0)

## Description

bitbucketにpushするとwerckerでビルドが走り、テストでOKの場合にgithub pagesにデプロイする。
サンプルドキュメントとして、静的Webページを使用している。

##Usage
+ ローカルのmasterブランチの作業ディレクトリのルートにwercker.ymlを作成。
+ git push origin masterを実行
+ githubのリポジトリのページに行き、SettingsタブのGitHub PagesセクションのSourceがbranch gh-pagesになっていること。
+ https://[user].github.io/[branch]に公開される。

