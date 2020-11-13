# CryptoWallet
---
- Create a wallet repo and clone hd-wallet-derive into it.
-Create wallet.py and keep it in same repo
- Create constants.py to store variables and call the file from wallet.py
- Generate mnemonic with this tool https://iancoleman.io/bip39/ I used a 12 word mnemonic, change Coin to BTC- Bitcon Testnet and select BIP32
- Store mnemonic in .env and call it in
- Derive the wallet using subprocess
- Create flags in command for mnemonic, coin, and numdrive, then output in json
- Link accounts and send transactions
