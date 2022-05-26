# abigen-golang

ABIGEN is a Golang Proxy generator for Ethereum Virtual Machine Smart Contracts

As it depends of Go-Ethereum and it has several OS dependencies it is recommended you clone this project and compile it within the machine it is going to use it:

```bash
$ go build
```

Then you move the abigen-golang to your PATH.

If your GOPATH/bin is at your machine's PATH you can execute:

```bash
$ go install
```

Some binaries were left for download purposes for who cannot compile it directly from Go source.

[abigen-golang-linux](abigen-golang-linux)
[abigen-golang-mac](abigen-golang-mac)

Platforms tested were Mac OS 11.x and Linux. Windows version were not tested or compiled.
