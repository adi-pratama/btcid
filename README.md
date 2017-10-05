# btcid
Python wrapper for bitcoin.co.id API

Download and extract vipbtc folder inside your Python directory program,
for example:
https://s1.postimg.org/8nst9w2h3j/Screenshot_125.png


Gunakan python versi 3

```sh
import vipbtc
```

Public API:
```sh
vipbtc.getTicker()
vipbtc.getDepth()
vipbtc.getTradeHistory()
```

Trade API:
```sh
key = "API key anda"
secret = "Secret key anda"

akun = vipbtc.TradeAPI(key, secret)

akun.getInfo()
akun.transHistory()
akun.trade(ttype, amount, price)
akun.tradeHistory()
akun.openOrders()
akun.cancelOrder(ttype, order_id)
```
