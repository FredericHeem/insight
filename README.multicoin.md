Insight multi crypto
===================

This fork allows to use *insight* with other cryptocurrencies such as Litecoin, Dogecoin and Darkcoin.


To run the dogecoin testnet insight frontend:

  $ npm run dogecoin

The *config* directory is the place to look at to customize or add a new crypto. 
 
On insight-api:

  $ source env/env-dogecoin-testnet.sh
  
  $ npm start

Then open a browser at the following address:

* http://localhost:3001/explorer/bitcoin/
* http://localhost:3003/explorer/litecoin/
* http://localhost:3005/explorer/dogecoin/
* http://localhost:3007/explorer/darkcoin/ 


