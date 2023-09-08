# my_nft_market_place
# NFT Marketplace Projesi

Bu proje, bir NFT (Non-Fungible Token) pazar yeri oluşturmak için kullanılan komutları ve adımları içerir. Aşağıda, projenin nasıl kurulacağı ve çalıştırılacağı hakkında temel bilgiler bulunmaktadır.

## Gereksinimler

- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Sugar-v3](https://github.com/metaplex-foundation/sugar/releases)
- [Phantom Cüzdan](https://phantom.app/)

## Kurulum

1. Solana CLI'yi yükleyin:

   ```bash
   sh -c "$(curl -sSfL https://release.solana.com/v1.14.11/install)"

    Sugar-v3'ü indirin:

    bash

wget https://github.com/metaplex-foundation/sugar/releases/download/sugar-cmv3-alpha.3/sugar-ubuntu-latest
mv sugar-ubuntu-latest sugar
chmod +x sugar

## Wallet'ları oluşturun:


''' shell
solana-keygen new --outfile ./owner.json
solana-keygen new --outfile ./creator.json
''''

## Solana yapılandırmasını ayarlayın:



solana config set --keypair $PWD/owner.json
solana config set --url https://rpc.ankr.com/solana_devnet

## SOL jetonlarını airdrop yapın:



    solana airdrop 2 <owner_pub_key>
    solana airdrop 2 <creator_pub_key>
    
## Wallet'ları Phantom'a ekleyin.

## Assets (varlıklar) dosyalarını indirin ve açın.

## Sugar için bir yapılandırma dosyası oluşturun.

## Assets dosyalarını Sugar kullanarak yükleyin.
## Candy Machine ve koleksiyon NFT'sini oluşturun.
## Projeyi başlatın.



## Projenin nasıl kullanılacağına dair ayrıntılı bilgiler için Dökümantasyon sayfasını inceleyin.
Katkıda Bulunma

Eğer bu projeye katkıda bulunmak isterseniz, lütfen Katkıda Bulunma Rehberine göz atın.
Lisans

Bu proje MIT Lisansı ile lisanslanmıştır.

