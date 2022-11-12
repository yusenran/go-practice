
# きほんのき

`go.mod`作成

```bash
go mod init
```

必要なモジュール取得  
`go.sum`が作成される

```bash
go mod tidy
```

`go.mod`だけでも基本的にはビルド再現性は担保されているが、
悪意のある改変などから守る目的で`go.sum`も基本リポジトリにpushする

https://zenn.dev/ryo_yamaoka/articles/595cf9e69229f9
