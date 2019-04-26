# QpesaCoin-Blockchain-Explorer
Block explorer for QpesaCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon QpesaCoind. It should be accessible from the Internet. Run QpesaCoind with open port as follows:
```bash
./QpesaCoind --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=21896
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
