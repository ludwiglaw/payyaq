<div style="width: 100%; height: 500px; " id="sosobtc_market"></div>
<script src="https://www.sosobtc.com/public/assets/plugin/sosobtc_plugin.js"></script>
<script type="text/javascript">
    (function () {
        SOSOBTC('Market').init({
            id: 'sosobtc_market',
            btc: ['okcoinfutures_quarter','okcoin','huobi','btcchina','coinbase','bitstamp','bitfinex','okcoincom','okcoinfutures_week'],
            ltc: ['okcoin','okcoincom','bitfinex','bitstamp'],
            others: ['eth_yunbi','eos_yunbi','ans_yunbi'],
            row: ['price', 'buy', 'sell', 'high', 'low', 'vol'],
            td_height: '30px',
            
        });
    })();
    
</script>
