# iridium block explorer (IRD)

This is the iridium block explorer, network status and pool lists.

The online version is available here : https://explorer.ird.cash

Spawn a local webserver or use docker : 

```
docker run -p 8082:80 -v ird-explorer:/usr/share/nginx/html:ro --name ird-explorer nginx:latest
```

Then open http://localhost:8082

**To develop locally : You have to allow CORS (Cross origin ressource sharing) in your browser**
 * Safari : Show development menu in menubar and disable multi origin restrictions
 * Chrome : https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi


![New block explorer](https://cdn.discordapp.com/attachments/403614252415451156/430861467278114836/bx.png)

## task list

* homepage
  * [x] network stats
  * [x] total emission with percentage
  * [x] total transactions
  * [x] show tx in mempool
  * [ ] tx in mempool detail
  * [x] show last found blocks
  * [x] price in usd/eur/btc
  * [ ] small difficulty graph for last 31 blocks
  * [x] search field for blk or tx
  * [ ] search by payment ID
  * [x] add nodes status/versions
  * [ ] remove url variable

* blockchain
  * [x] search field
  * [ ] search by payment ID
  * [x] last 31 blocks list
  * [x] load more
  * [ ] next/previous page
  
* block detail
  * [x] show block detail
  * [ ] modal window
  * [ ] next/previous block
  
* tx detail
  * [x] show tx detail
  * [ ] modal window
  
* pools
  * [x] pools list
  * [x] overall stats
  * [x] country flags
  * [x] country hover link
  * [ ] order by hashrate/miners...
  * [ ] map of pools (geoip)

* stats
  * [ ] Difficulty graph
  * [ ] emission graph vs theorical
  * [ ] tx graphs
  * [ ] "Zawy" look graph
  
* world map
 
