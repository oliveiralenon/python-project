import requests
cotacoes = requests.get("https://economia.awesomeapi.com.br/last/USD-BRL,EUR-BRL,BTC-BRL").json()

(dolar) = cotacoes['USDBRL']['bid']
(euro) = cotacoes['EURBRL']['bid']
btc = cotacoes['BTCBRL']['bid']


print(f'Dólar: R${float(dolar):.2f}\nEuro: R${float(euro):.2f}\nBitcoin: R${btc.replace(".","")}')
