---
title: Markets
menu:
  main:
    name: Markets
    weight: 5
layout: page
---

{{< rawhtml >}}
<!-- TradingView Widget BEGIN -->
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-market-quotes.js" async>
  {
  "width": "100%",
  "height": "1200",
  "symbolsGroups": [
    {
      "originalName": "INDICES",
      "symbols": [
        {
          "displayName": "S&P 500",
          "name": "OANDA:SPX500USD"
        },
        {
          "displayName": "Nasdaq 100",
          "name": "OANDA:NAS100USD"
        },
        {
          "displayName": "Dow 30",
          "name": "FOREXCOM:DJI"
        },
        {
          "displayName": "Nikkei 225",
          "name": "INDEX:NKY"
        },
        {
          "displayName": "DAX Index",
          "name": "INDEX:DEU30"
        },
        {
          "displayName": "FTSE 100",
          "name": "OANDA:UK100GBP"
        }
      ],
      "name": "Indices"
    },
    {
      "originalName": "COMMODITIES",
      "symbols": [
        {
          "displayName": "E-Mini S&P",
          "name": "CME_MINI:ES1!"
        },
        {
          "displayName": "Euro",
          "name": "CME:6E1!"
        },
        {
          "displayName": "Gold",
          "name": "COMEX:GC1!"
        },
        {
          "displayName": "Crude Oil",
          "name": "NYMEX:CL1!"
        },
        {
          "displayName": "Natural Gas",
          "name": "NYMEX:NG1!"
        },
        {
          "displayName": "Corn",
          "name": "CBOT:ZC1!"
        }
      ],
      "name": "Commodities"
    },
    {
      "originalName": "BONDS",
      "symbols": [
        {
          "displayName": "Eurodollar",
          "name": "CME:GE1!"
        },
        {
          "displayName": "T-Bond",
          "name": "CBOT:ZB1!"
        },
        {
          "displayName": "Ultra T-Bond",
          "name": "CBOT:UB1!"
        },
        {
          "displayName": "Euro Bund",
          "name": "EUREX:FGBL1!"
        },
        {
          "displayName": "Euro BTP",
          "name": "EUREX:FBTP1!"
        },
        {
          "displayName": "Euro BOBL",
          "name": "EUREX:FGBM1!"
        }
      ],
      "name": "Bonds"
    },
    {
      "originalName": "FOREX",
      "symbols": [
        {
          "name": "FX:EURUSD"
        },
        {
          "name": "FX:GBPUSD"
        },
        {
          "name": "FX:USDJPY"
        },
        {
          "name": "FX:USDCHF"
        },
        {
          "name": "FX:AUDUSD"
        },
        {
          "name": "FX:USDCAD"
        }
      ],
      "name": "Forex"
    },
    {
      "name": "CRYPTOCURRENCIES",
      "symbols": [
        {
          "name": "COINBASE:BTCUSD",
          "displayName": "Bitcoin"
        },
        {
          "name": "KRAKEN:ETHUSD",
          "displayName": "Ethereum"
        },
        {
          "name": "HUOBI:XRPUSDT",
          "displayName": "Ripple"
        }
      ]
    }
  ],
  "locale": "en"
}
  </script>
</div>
<!-- TradingView Widget END -->
{{< /rawhtml >}}
