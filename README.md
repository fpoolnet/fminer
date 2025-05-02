<div align="center">
  <img src="/logo.svg" alt="logo" width="250" />
</div>



## Download - CPU only

| Platform | Architecture | File |
|----------|--------------|------|
| Windows  | 64-bit (amd64) | [fminer-windows-amd64-v0.1.2-alpha.zip](https://github.com/fpoolnet/fminer/releases/download/v0.1.2-alpha/fminer-windows-amd64-v0.1.2-alpha.zip) |
| Windows  | 32-bit (386)   | [fminer-windows-386-v0.1.2-alpha.zip](https://github.com/fpoolnet/fminer/releases/download/v0.1.2-alpha/fminer-windows-386-v0.1.2-alpha.zip) |
| Linux    | 64-bit (amd64) | [fminer-linux-amd64-v0.1.2-alpha.tar.gz](https://github.com/fpoolnet/fminer/releases/download/v0.1.2-alpha/fminer-linux-amd64-v0.1.2-alpha.tar.gz) |
| Linux    | ARM64          | [fminer-linux-arm64-v0.1.2-alpha.tar.gz](https://github.com/fpoolnet/fminer/releases/download/v0.1.2-alpha/fminer-linux-arm64-v0.1.2-alpha.tar.gz) |
| macOS    | Apple Silicon (arm64) | [fminer-darwin-arm64-v0.1.2-alpha.tar.gz](https://github.com/fpoolnet/fminer/releases/download/v0.1.2-alpha/fminer-darwin-arm64-v0.1.2-alpha.tar.gz) |
| macOS    | Intel (amd64)  | [fminer-darwin-amd64-v0.1.2-alpha.tar.gz](https://github.com/fpoolnet/fminer/releases/download/v0.1.2-alpha/fminer-darwin-amd64-v0.1.2-alpha.tar.gz) |

- Download older versions from [github releases](https://github.com/fpoolnet/fminer/releases)

## Sample configuration

```conf
# Network: main, test, regtest, simnet
# network=main

# Log output directory (default: $APP_DATA/.fminer/log)
# logdir=./logs

# CPU threads (0 = use all)
# threads=0

# Log level: trace, debug, info, warn, error, critical
debuglevel=trace

# Mining pool address (host:port)
pool=pool.example.com:1212

# Payout address
address=YOUR_ADDRESS

# tag shown in coinbase tx
user=YOUR_POOL_USERNAME

```

## Usage

```sh
./fminer --conf /path/fminer.conf
```

## CMD options：

```conf
Application Options:
      --conf=       Path to configuration file. (default: $APP_DATA/.fminer/fminer.conf)
      --network=    The network being mined on. {simnet, regtest, test, main} (default:
                    main)
      --user=       The username of the mining account.
      --address=    The address of the mining account.
      --pool=       The stratum domain and port of the mining pool to connect to. eg.
                    example.com:1212.
      --debuglevel= Logging level for all subsystems {trace, debug, info, warn, error,
                    critical} (default: debug)
      --logdir=     The log output directory. (default: $APP_DATA/.fminer/log)
      --threads=    Number of CPU cores to use. Default is all cores.
      --appdata=    Path to application home directory. (default: $APP_DATA/.fminer)

Help Options:
  -h, --help        Show this help message
```



## Contact Us

[Flokicoin Discord #mining](https://flokicoin.org/discord)