# my_nft_market_place
# NFT Marketplace Projesi

This project includes the commands and steps used to create an NFT (Non-Fungible Token) marketplace. Below are basic instructions on how to set up and run the project.

## Requirements

- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Sugar-v3](https://github.com/metaplex-foundation/sugar/releases)
- [Phantom Cüzdan](https://phantom.app/)

## Installation

1. Install Solana CLI:

   ```bash
   sh -c "$(curl -sSfL https://release.solana.com/v1.14.11/install)"

    Download Sugar-v3:

    bash

wget https://github.com/metaplex-foundation/sugar/releases/download/sugar-cmv3-alpha.3/sugar-ubuntu-latest
mv sugar-ubuntu-latest sugar
chmod +x sugar

## Create Wallets:  


''' shell
solana-keygen new --outfile ./owner.json
solana-keygen new --outfile ./creator.json
''''

## Configure Solana:



solana config set --keypair $PWD/owner.json

solana config set --url https://rpc.ankr.com/solana_devnet

## Airdrop SOL Tokens:


    solana airdrop 2 <owner_pub_key>
    solana airdrop 2 <creator_pub_key>
    
### Add Wallets to Phantom.

### Download and extract Asset files.

### Create a configuration file for Sugar.

### Upload Asset files using Sugar.

### Create the Candy Machine and NFT collection.

### Start the project.


License

This project is licensed under the MIT License.
