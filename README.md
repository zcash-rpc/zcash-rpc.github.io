# Zcash RPC Documentation Generator

This tool extracts and formats the help text for each of the Zcash RPC calls. The output of this script is hosted at [zcash-rpc.github.io](https://zcash-rpc.github.io). 

See the `script` directory for the `zcash.go` script that generates the output and template.

### How to use

Ensure that you have Go installed and a working and running `zcashd` instance and that the `zcash-cli` executable is available in `/usr/bin/zcash-cli` (or update the path to your zcash-cli executable in `zcash.go`). From the `script` directory simply run `go run zcash.go` and the documentation will be produced for all Zcash RPC calls and styled according to the template in `template.html`.

## License

License of the docs is MIT (see https://github.com/zcash/zcash), license of the scripts and webpage is also MIT ((C) 2018 Karel Bilek)
