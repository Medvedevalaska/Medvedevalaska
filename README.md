# binance-withdraw-ccxt

1. Скачивай оба файла, в файл wallets.txt добавляешь адреса кошельков, которые хочешь пополнить.
2. Берешь api key и api secret в binance, не забудь добавить свой ip адрес при создании ключей, иначе не даст выводить.
3. Значения ключей передаешь в переменные API_KEY и API_SECRET.
4. В перменную symbolWithdraw передаешь монету, которую хочешь вывести.
5. В network сеть.

time.sleep можешь убрать, но с ним более безопасно от будущего бритья.
кол-во монет для вывода меняешь в переменной amount_to_withdrawal. можешь выводить не рандомное кол-во, но это хорошая практика для попадания под бритье в будущем.

Канал : https://t.me/hodlmodeth. 
Чат для вопросов : https://t.me/code_hodlmodeth.
