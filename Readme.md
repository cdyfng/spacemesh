wget https://github.com/spacemeshos/CLIWallet/releases/download/v0.0.1/cli_wallet_linux_amd64
wget https://storage.googleapis.com/smapp/0.0.7/go-spacemesh-0.1.9-linux
./go-spacemesh-0.1.9-linux  --grpc-server --json-server --tcp-port 7152 --config ./tn01.toml -d ./sm_data/
./go-spacemesh-0.1.9-linux --grpc-server --json-server --tcp-port 7152 --config ./tn1.toml -d ./sm_data --coinbase 0xb3139ba23cfc04a895ec2bcc4cc64af275daa1cd --start-mining --post-datadir ./post_data

