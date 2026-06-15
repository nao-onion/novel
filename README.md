# Novel Workspace

GitHub Pages + Jekyllで小説本文と企画資料を表示するためのリポジトリです。

## Pages

`main` ブランチへpushすると、`.github/workflows/pages.yml` がJekyllサイトをビルドしてGitHub Pagesへデプロイします。

公開後はトップページから `Documents` を開くと、既存の `specs/` `plot/` `bible/` の内容を読めます。

## Local preview

Ruby/Bundlerが入っている環境では以下で確認できます。

```powershell
bundle install
bundle exec jekyll serve
```
