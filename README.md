# [:] Example GO project using Glide.

An example Go project using Glide package manager to demonstrate [SourceClear](https://www.sourceclear.com) scans.

## Scan this project
There are 2 ways to scan this project.

### 1. Using url option
`SRCCLR_FORCE_GO_INSTALL=true srcclr scan --url https://github.com/srcclr/example-go-glide`

### 2. On local path
```
1. git clone https://github.com/srcclr/example-go-glide/ $GOPATH/src/github.com/srcclr/example-go-glide/
2. srcclr scan $GOPATH/src/github.com/srcclr/example-go-glide/
```
