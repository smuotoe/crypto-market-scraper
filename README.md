# crypto-market

This tool is used to grab latest data on the BTC_USD, BTC_ETH, ETH_BTC, ETH_USD, etc pairs and output them to a CSV file

### How it works
* For any pair top sell order `top_sell_order("cur1_cur2")`
  * e.g. For ETH/BTC top sell order `top_sell_order("eth_btc")`
* For any pair top buy order `top_buy_order("cur1_cur2")`
  * e.g. For BTC/USD top buy order `top_buy_order("btc_usd")`
* To output all the values to a CSV file `final_file()`
* To output values on each pair to respective CSV files, use `final_file(every.out = TRUE)`


 `
