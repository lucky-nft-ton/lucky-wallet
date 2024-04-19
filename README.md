# Lucky Wallet
TON smart contract

Lucky Wallet - безопасный смарт-контейнер для ваших TON, NFT и Jetton.

## Генерация кастомного адреса (с заданным окончанием)

1. Выполнить установку:
`npm i`

2. Выполнить билд контрактов:
`npm run 'build bank'` и `npm run 'build sell'`

3. Внести в файл ./some/generateAddr.ts необходимые окончания искомых адресов и запустить поиск
`npm run wallet-generate`

4. Найденный index адреса внести файл ./scripts/mintLuckyWallet.ts (проверить что адрес свободен и установить текущую стоимость минта - сейчас скрипт минта эти данные не проверяет) и запустить минт
`npm start` 
Далее следовать инструкциям


## Ссылки
Telegram Mini App: https://t.me/Lucky_wallet_bot/App?startapp=buy_EQBSJFjmxQaroq--g52UqojwSJJwA6JSqeYhJcfRrNwEqhiX

NFT Collection: https://getgems.io/collection/EQBpqnrjhql5jbMLvKocqKFL0_fMQOwCtDQlDCFOiG98WT0C