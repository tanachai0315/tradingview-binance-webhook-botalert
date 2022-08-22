# TradingView Binance Webhook botalert

## วิธีใช้
1. install nodejs
2. install yarn
3. install ts-node
4. clone project

> git clone https://github.com/cryptothedev/tradingview-binance-webhook.git

> cd tradingview-binance-webhook

5. rename .env.example to .env
6. ตั้งค่าให้เรียบร้อย
7. run server

> ts-node src/index.ts

#open order 

- ssh root@[ip]              [login เข้า server]
- ใส่ password

- cd tradingview-binance-webhook/         [เข้าไปยัง folder ของ code]
- git pull                                                         [อัพเดทตัวบอท]
- sudo kill -9 $(sudo lsof -t -i:80)               [ปิดบอท]
- ts-node src/index.ts &                             [รันบอท]

URL:
http://[ip_address]/tradingview/[token_value]

คำสั่ง

{{ticker}}_short_50_true_false

{{ticker}}_long_50_true_false

{{ticker}}_[side]_[amount_usd]_[set_tp]_[set_sl]

#แปลความหมาย long/short   20       true/false  true/false
