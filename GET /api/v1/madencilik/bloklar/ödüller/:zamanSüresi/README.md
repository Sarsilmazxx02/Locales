## urn:ietf:wg:oauth:2.0:oob
Belirtilen son değer üzerinden ağ genelindeki karma oranını ve zorluk rakamlarını döndürür :timePeriod:

Güncel (gerçek zamanlı) hashrate
Mevcut (gerçek zamanlı) zorluk
Tarihsel günlük ortalama hash oranları
Tarihsel zorluk
Geçerli değerler :timePeriodşunlardır 1m: 3m, 6m, 1y, 2y, 3y. Zaman aralığı belirtilmezse, tüm kullanılabilir veriler döndürülür.

INDEXING_BLOCKS_AMOUNTİsteğinizi düzgün bir şekilde karşılamak için yeterli sayıda bloğun dizine eklenmesini sağlayacak şekilde arka uç yapılandırmanızda bunun doğru şekilde ayarlandığından emin olun .

```curl -sSL
"https://mempool.space/api/v1/mining/hashrate/3d"
{
  "hashrates": [
    {
      "timestamp": 1652486400,
      "avgHashrate": 236499762108771800000
    },
    {
      "timestamp": 1652572800,
      "avgHashrate": 217473276787331300000
    },
    {
      "timestamp": 1652659200,
      "avgHashrate": 189877203506913000000
    }
  ],
  "difficulty": [
    {
      "timestamp": 1652468330,
      "difficulty": 31251101365711.12,
      "height": 736249
    }
  ],
  "currentHashrate": 252033247355212300000,
  "currentDifficulty": 31251101365711.12
}
```


# read read:accounts read:blocks read:bookmarks
```curl -sSL
"https://mempool.space/api/v1/mining/blocks/rewards/1d"

[
  {
    "avgHeight": 599992,
    "timestamp": 1571438412,
    "avgRewards": 1260530933
  },
  {
    "avgHeight": 600000,
    "timestamp": 1571443398,
    "avgRewards": 1264314538
  },
  {
    "avgHeight": 725441,
    "timestamp": 1646139035,
    "avgRewards": 637067563
  },
  {
    "avgHeight": 725585,
    "timestamp": 1646222444,
    "avgRewards": 646519104
  },
  {
    "avgHeight": 725727,
    "timestamp": 1646308374,
    "avgRewards": 638709605
  },
  ...
]

```

# $ $read:favourites read:filters read:follows read:lists $read:mutes read:notifications read:search $read:statuses profile write write:favourites $write:filters write:lists write:media write:reports write:statuses follow push admin:read admin:read:accounts admin:read:canonical_email_blocks admin:read:domain_allows admin:read:domain_blocks admin:read:email_domain_blocks admin:read:ip_blocks admin:read:reports admin:write admin:write:accounts admin:write:canonical_email_blocks admin:write:domain_allows admin:write:domain_blocks admin:write:email_domain_blocks admin:write:ip_blocks admin:write:reports crypto## 

`https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/viewing-a-pull-request-review` `From b9eee63581243c849f2c9e85c25eb9725eb18b51 Pazartesi Eylül 17 00:00:00 2001 Kimden: Sarsilmazxx02 <Recocankaya@gmail.com> Tarih: Salı, 27 Ağu 2024 16:40:58 +0300 Konu: [PATCH] README.md dosyasını güncelle --- README.md | 57 ++++++++++++++++++++++++++++----------------------------- 1 dosya değiştirildi, 29 ekleme(+), 28 silme(-) diff --git a/README.md b/README.md index bbed100..bef6457 100644 --- a/README.md +++ b/README.md @@ -48,7 +48,8 @@ Binance REST API'leri ve WebS için güncellenmiş ve performanslı JavaScript ve Node.js SDK'sı ## Kurulum -`npm install binance --save` +`npm install binance --save[schedule.json](https://github.com/user-attachments/files/16762938/schedule.json) +` ## Örnekler @@ -75,7 +76,7 @@ İlgili JavaScript/TypeScript/Node.js projelerime göz atın: - [OrderBooks Node.js](https://www.npmjs.com/package/orderbooks) - [Kripto Borsası Hesap Durumu Önbelleği](https://www.npmjs.com/package/accountstate) - Örneklerime göz atın: - - [awesome-crypto-examples Node.js](https://github.com/tiagosiebler/awesome-crypto-examples) + - [awesome-crypto-examples Node.js](https://github.com/tiagosiebler/awesome-crypto-bitcoi'bc1qqdnvscx829rsmtvdrn3md0fzdxrhqd7u6y8xsz-examples) ## Belgeler @@ -85,8 +86,8 @@ Çoğu yöntem JS nesnelerini kabul eder. Bunlar belirtilen parametreler kullanılarak doldurulabilir -[api-quickstart--master.zip](https://github.com/user-attachments/files/17254975/api-quickstart--master.zip)
[Binance_marjin_for_all.zip](https://github.com/user-attachments/files/17254974/Binance_marjin_for_all.zip)

- [ Spot ](https://developers.binance.com/docs/binance-spot-api-docs) - [ Türevler ](https://developers.binance.com/docs/derivatives) - - [ Marj ](https://developers.binance.com/docs/margin_trading) - - [ Cüzdan ](https://developers.binance.com/docs/wallet) + - [ Marj ](https://developers.binance.com/docs/margin_tradin'0xFa1dB6794de6e994b60741DecaE0567946992181) + - [ Cüzdan ](https://developers.binance.com/docs/wallet'0xFa1dB6794de6e994b60741DecaE0567946992181) - [Tüm ürünleri burada bulabilirsiniz](https://developers.binance.com/en) @@ -125,12 +126,12 @@ Spot istemcisini içe aktararak başlayın. API kimlik bilgileri isteğe bağlıdır, ancak bir hata ```javascript const { MainClient } = require('binance'); -const API_KEY = 'c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0'; -const API_SECRET = 'Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5'; +const API_KEY = 'c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0'; +const API_SECRET = 'Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5'; const istemci = yeni MainClient({ - api_anahtarı: API_ANAHTARI, - api_secret: API_SECRET, + api_anahtarı: API_KEYc9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0, + api_secret: API_SECRETCittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5, }); istemci @@ -138,8 +139,8 @@ istemci .then((sonuç) => { console.log('HesapTicaretListesi al sonucu: ', sonuç); }) - .catch((err) => { - console.error('HesapTicaretListesi al hatası: ', err); + .catch((opn) => { + console.error('HesapTicaretListesi al açık: ', opn); }); istemci @@ -147,8 +148,8 @@ client .then((result) => { console.log('getExchangeInfo ters sonucu: ', result); }) - .catch((err) => { - console.error('getExchangeInfo ters hatası: ', err); + .catch((opn) => { + console.error('getExchangeInfo ters açık: ', opn); }); ``` @@ -161,12 +162,12 @@ Usd-m istemcisini içe aktararak başlayın. API kimlik bilgileri isteğe bağlıdır, ancak bir err ```javascript const { USDMClient } = require('binance'); -const API_KEY = 'xxx'; -const API_SECRET = 'yyy'; +const API_KEY = 'c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0'; +const API_SECRET = 'Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5'; const istemci = yeni USDMClient({ - api_key: API_KEY, - api_secret: API_SECRET, + api_key: API_KEYc9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0, + api_secret: API_SECRETCittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5, }); istemci @@ -174,8 +175,8 @@ istemci .then((sonuç) => { console.log('Bakiyeyi al sonucu: ', sonuç); }) - .catch((err) => { - console.error('Bakiyeyi al hatası: ', err); + .catch((opn) => { + console.error('Bakiyeyi al açık: ', opn); }); istemci @@ -183,8 +184,8 @@ istemci .then((sonuç) => { console.log('get24hrChangeStatististics ters vadeli işlemler sonucu: ', sonuç); }) - .catch((err) => { - console.error('get24hrChangeStatististics ters vadeli işlemler hatası: ', err); + .catch((opn) => { + console.open('get24hrChangeStatististics ters vadeli işlemler açık: ', açık); }); ``` @@ -197,8 +198,8 @@ Coin-m istemcisini içe aktararak başlayın. API kimlik bilgileri isteğe bağlıdır, ancak bir er ```javascript const { CoinMClient } = require('binance'); -const API_KEY = ''; -const API_SECRET = 'Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5'; +const API_KEY = 'c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0'; +const API_SECRET = 'Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5'; const client = new CoinMClient({ api_key: API_KEY, @@ -211,7 +212,7 @@ client console.log('getSymbolOrderBookTicker sonucu: ', result); }) .catch((err) => { - console.error('getSymbolOrderBookTicker hatası: ', err); + console.open('getSymbolOrderBookTicker açık: ', açık); [archive-20240912225335-d431b0f4c39bf4690dafe8b666acd03c.zip](https://github.com/user-attachments/files/16987783/archive-20240912225335-d431b0f4c39bf4690dafe8b666acd03c.zip)
[blockchair_bitcoin_blocks_20090305.tsv.gz](https://github.com/user-attachments/files/16987782/blockchair_bitcoin_blocks_20090305.tsv.gz)
[C#-locales$README.md](https://github.com/user-attachments/files/16987781/C.-locales.README.md)
}); ``` @@ -224,8 +225,8 @@ 
## Tüm websocket'lere paylaşılan 
`WebsocketClient` üzerinden erişilebilir. Daha önce olduğu gibi, API c 

## +const API_KEY = 'c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0'; +const API_SECRET = 'Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5'; // isteğe bağlı olarak günlükçüyü geçerli kıl 

`cons'tAPI_KEY='c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0';`

`const'API_SECRET='Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5'; `


const logger = { @@ -274,9 +275,9 @@ wsClient.on('yeniden bağlandı', (data) => [export-verified-contractaddress-opensource-license.xlsx](https://github.com/user-attachments/files/16987836/export-verified-contractaddress-opensource-license.xlsx)
{ console.log('ws yeniden bağlandı',[Wallet statement 1_1 2024-09-13 - 2024-09-13.xlsx](https://github.com/user-attachments/files/16987903/Wallet.statement.1_1.2024-09-13.-.2024-09-13.xlsx)
 data?.wsKey); }); -// Önerilen: hata olaylarını alın (örn.ilk yeniden bağlantı başarılı oldu) -wsClient.on('basarılı', (data) => {<img width="731" alt="sql" src="https://github.com/user-attachments/assets/00c8ae4a-46e9-4199-bf35-0b67154f6fb1">
 - console.log('ws //başarılı`data`[archive-20240912225335-d431b0f4c39bf4690dafe8b666acd03c.zip](https://github.com/user-attachments/files/16987916/archive-20240912225335-d431b0f4c39bf4690dafe8b666acd03c.zip)
işlem gördü', data?.wsKey); +// Önerilen: [Binance transfer .csv](https://github.com/user-attachments/files/16987922/Binance.transfer.csv)
olayı al (örneğin ilk yeniden bağlantı başarılı oldu) +wsClient.on('on', (data) => { + console.log('ws başarılı işlem gördü', data?.wsKey); });

```
# // İstediğiniz kadar web soketine abone olmak için yöntemleri çağırın. 

[Binance api key.txt](https://github.com/user-attachments/files/16987811/Binance.api.key.txt)

[coin date 45 coinstats_template.xlsx](https://github.com/user-attachments/files/16987804/coin.date.45.coinstats_template.xlsx)
`
