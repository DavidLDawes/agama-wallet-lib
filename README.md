# agama-wallet-lib

### How to build Agama lib for client side

install browserify

browserify index.js --standalone agama > agamalib.js

### How to add btc compatible pow coin
- add coin network params in src/bitcoinjs-networks.js
- add electrum servers list and tx fee in src/electrum-servers.js

### How to add kmd asset chain
- add electrum servers list and tx fee in src/electrum-servers.js
- add asset chain ticker and an explorer link in src/coin-helpers.js