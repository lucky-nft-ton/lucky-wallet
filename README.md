### Attention to the jury of The Open League Hackathon! / Вниманию жюри The Open League Hackathon !

The project consists of two repositories:
TMA: https://github.com/lucky-nft-ton/lucky-wallet-tma
Smart contracts: https://github.com/lucky-nft-ton/lucky-wallet

In order to fully use the application, you must have at least one container on your TON wallet. You can create it inside the application (cost about 2,4 TON) or write https://t.me/x1y1x3 and we will send you a container for testing.

Проект состоит из двух репозиториев:
ТМА: https://github.com/lucky-nft-ton/lucky-wallet-tma
Смарт-контракты: https://github.com/lucky-nft-ton/lucky-wallet

Для того чтобы полноценно использовать приложение, необходимо наличие хотя бы одного контейнера на вашем TON кошельке. Вы можете создать его внутри приложения (стоимость около 2,4 TON) или написать https://t.me/x1y1x3 и мы пришлём вам контейнер для проведения тестирования.

# Lucky Wallet
Smart NFT Container for your NFTs & Jettons

## Description

Lucky Wallet is your personal and secure smart container for storing and collecting TON, NFTs, and Jettons. Asset management on Lucky Wallet is done through a specially created Mini App. The smart contract code is verified, and the source code of the contracts is available open-source in the GitHub repository. The smart container is represented as an NFT, and accordingly, it can be transferred/sold to a new owner like a regular NFT. Only the current owner of the NFT has access to the assets inside the container. Use cases of Lucky Wallet:

- Sale/transfer of assets as a "package" - you can place the desired amount of NFTs and/or Jettons in the container and then sell or transfer it to a new owner as a regular NFT.

- The smart container serves as a cost-effective and secure alternative for using escrows in OTC (peer-to-peer/direct) deals with Jettons. The seller places the desired amount of Jettons in the container and lists it as an NFT for sale through NFT Sale or any other NFT marketplace service without commissions and marketplace royalties (in future versions of the application, this functionality will be implemented within the app). At this point, the prospective buyer can verify that the required amount of Jettons is inside the container, and the seller does not have access to them, as the smart contract for NFT sale is the current owner. The buyer makes the payment as in a regular NFT purchase - the seller receives the payment, and the buyer gets access to the container's assets.

- Relative "anonymity" and additional protection for your assets: even if your seed phrase is compromised, the perpetrator needs to know for certain that you have a container (similar to cold storage).

- Mass collection of donations, transactions, drops, etc. No need to create dozens of new wallets for different purposes - use the container. There is also the possibility of generating a "beautiful" ending of the container's address. Unlike generating endings of regular wallets by third parties, where the seed phrase is compromised immediately, only you have access to the container.

- Investment asset. The cost of creating a Lucky Wallet is not fixed and increases in an arithmetic progression with a step of 0.005 TON for each new container created. The initial cost of creating the first container was 0.21 TON (with a referral discount of 0.1 TON). After creating the container, you can list it for sale at a fixed price, for example, on Getgems.

- Monetization of your audience. Currently, creating containers without a referral link is not available. There is a so-called "invitation system" where you can create a new container only using an invitation. The referral reward is fixed and amounts to 0.1 TON. If you already have a container, you will have the opportunity to create your referral link - the cost of creating the link is 0.5 TON. Having your own referral link is economically viable when creating at least 5 containers for yourself (your own purchases are counted). The referral payout occurs at the moment of container creation through a special smart contract.

## Links
Telegram Mini App: https://t.me/Lucky_wallet_bot/App?startapp=buy_EQBSJFjmxQaroq--g52UqojwSJJwA6JSqeYhJcfRrNwEqhiX

NFT Collection: https://getgems.io/collection/EQBpqnrjhql5jbMLvKocqKFL0_fMQOwCtDQlDCFOiG98WT0C

Presentation video: https://youtu.be/FmPvABqFyX0

Telegram channel (RU): https://t.me/nft_crossing

### Генерация кастомного адреса (с заданным окончанием)

1. Выполнить установку:
`npm i`

2. Выполнить билд контрактов:
`npm run 'build bank'` и `npm run 'build sell'`

3. Внести в файл ./some/generateAddr.ts необходимые окончания искомых адресов и запустить поиск
`npm run wallet-generate`

4. Найденный index адреса внести файл ./scripts/mintLuckyWallet.ts (проверить что адрес свободен и установить текущую стоимость минта - сейчас скрипт минта эти данные не проверяет) и запустить минт
`npm start` 
Далее следовать инструкциям
