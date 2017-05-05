<div style="width: 100%; height: 326px;" id="sosobtc_market"></div>
<script src="//static2.sosobtc.com/public/assets/plugin/sosobtc_plugin.js"></script>
<script type="text/javascript">
    (function () {
        SOSOBTC('Market').init({
            id: 'sosobtc_market',
            btc: ['bitstamp', 'btce', 'huobi', 'okcoin', 'chbtc', 'okcoinfutures_week'],
            ltc: ['btce', 'huobi', 'okcoin', 'chbtc'],
            alt: ['ppc', 'doge', 'pts'],
            bter: ['doge'],
            others: ['eth_yunbi'],
            row: ['price', 'buy', 'sell', 'high', 'low', 'vol']
        });
    })();
</script>
