# Change Log

## [v1.2.0]
* Use _float_ instead of _integer_ for timestamp related information (_tickers_, _openOrders_, _closedOrders_)
* Add order type (_buy_ or _sell_) in _trades_ API
* Fix authentication using _ApiKey_ header
* Support for Binance recvWindow parameter in config.json (to account for clock skew)
* Bittrex module changed from _node.bittrex.api_ to _node-bittrex-api_ module (version 0.7.6)
* Poloniex module updated to version 1.6.2
* Minor UI navigation changes
