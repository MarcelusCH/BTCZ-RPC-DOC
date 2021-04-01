# BitcoinZ RPC Documentation Generator

This tool extracts and formats the help text for each of the BitcoinZ RPC calls. The output of this script is hosted at [zcash-rpc.github.io](https://zcash-rpc.github.io).

See the `script` directory for the `bitcoinz.go` script that generates the output and template.

### How to use

Ensure that you have Go installed and a working. [more info](https://github.com/golang/go/wiki/Ubuntu)
Also ensure that you running `bitcoinzd` instance and that the `bitcoinz-cli` executable is available in `/usr/bin/bitcoinz-cli` (or update the path to your bitcoinz-cli executable in `bitcoinz.go`). From the `script` directory simply run `go run bitcoinz.go` and the documentation will be produced for all BitcoinZ RPC calls and styled according to the template in `template.html`.

## License

License of the docs is MIT (see https://github.com/zcash/zcash), license of the scripts and webpage is also MIT ((C) 2018 Karel Bilek)
