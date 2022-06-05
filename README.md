# precommit-template
gitのprecommit時に何かしら挟みたいときのテンプレートプロジェクト

## 導入手順

```shell
$ mkdir project
$ cd project
$ pnpm init
$ pnpm dlx husky-init && pnpm install
$ pnpm run test
$ npx husky add .husky/pre-commit "npm test"
$ git add .husky/pre-commit
# ここで失敗する
$ git commit -m "Keep calm and commit"
```
