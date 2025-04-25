# green-heart-5397
MCP / Go

# Thanks

https://tech-blog.rakus.co.jp/entry/20250424/mcp-go

# Development

## Enviroment

```console
$ go version
go version go1.24.1 linux/amd64
```

## Initialize

```console
go mod init mcp-time-server
touch main.go
mkdir bin
```

## Build

```console
go mod tidy
go build -o bin/current-time-server
```

# Usage

## VSCode

```json
// .vscode/mcp.json
{
    "servers": {
        "current-time-server": {
            "type": "stdio",
            "command": "/workspaces/green-heart-5397/bin/current-time-server",
            "args": []
        }
    }
}
```
