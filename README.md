# Create BTC Wallet
## Wallets kind
 - Nao determinística
 - Determinísticas
 - HD - Hierarchical Deternistic
 - Mnemonic - BIB 39

## Steps
 - Download and install [nodejs](https://nodejs.org)
 - Verify version
~~~bash
node -v
~~~

 - Verify npm version
~~~bash
npm -v
~~~

 - In project folder execute this to iniciate 
~~~bash
npm init -y
~~~

 - To install dependencies
~~~bash
npm install bip39 bip32@2.0.6 bitcoinjs-lib --save
~~~

 - To execute program
~~~bash
cd src 
\btcwallet\src> node .\createWallet.js
~~~

## Other interesting testing sites
 - [Electrum Wallet](https://electrum.org/#download)
 - [FreeBTC to test](https://freebitco.in/)
 - [Blockchain](https://www.blockchain.com/explorer)
 - [Mempool](https://mempool.space/pt/)
 - [Coinfaucet](https://coinfaucet.eu/en/btc-testnet/)
