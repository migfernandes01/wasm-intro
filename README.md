# Description

This repo contains a very basic web server that uses wasm to send an HTML snippet an inject it in the DOM.

## Commands

- Build wasm binary from go: `GOOS=js GOARCH=wasm go build -o ../../assets/main.wasm` - run from /cmd/wasm
- Run web server: `go run main.go` - from /cmd/server
