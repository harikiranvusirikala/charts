# Charts

A collection of real-time cryptocurrency trading charts powered by TradingView widgets, deployed on GitHub Pages.

## 🚀 Live Demo

View the live charts here: **[https://harikiranvusirikala.github.io/charts/](https://harikiranvusirikala.github.io/charts/)**

### Available Views

- **[Daily View](https://harikiranvusirikala.github.io/charts/crypto/1.html)** - Multiple timeframes (1D, 1M, 3M, 12M, 60M, All)
- **[5-Day View](https://harikiranvusirikala.github.io/charts/crypto/5.html)** - Focused 5-day chart view

## 📊 Featured Cryptocurrencies

The charts track the following cryptocurrencies:

- **BTC** (Bitcoin) - BINANCE:BTCUSD
- **ETH** (Ethereum) - BINANCE:ETHUSD
- **SOL** (Solana) - BINANCE:SOLUSD
- **SUI** (Sui) - BINANCE:SUIUSD
- **APT** (Aptos) - BINANCE:APTUSD
## 🎯 Custom Symbols via URL

You can now customize which cryptocurrencies to display by passing symbols through URL parameters:

### Usage

Add a `symbols` query parameter with comma-separated trading pairs:

```
d.html?symbols=BINANCE:BTCUSD|1D,BINANCE:ETHUSD|1D,COINBASE:SOLUSD|1D
```

### Examples

**Day View with custom symbols:**
```
https://harikiranvusirikala.github.io/charts/crypto/d.html?symbols=BINANCE:BTCUSD|1D,BINANCE:ETHUSD|1D
```

**5-Day View with custom symbols:**
```
https://harikiranvusirikala.github.io/charts/crypto/5d.html?symbols=BINANCE:BTCUSD|5D,COINBASE:APTUSD|5D
```

### Supported Formats

- **Binance:** `BINANCE:XXXUSD|1D` or `BINANCE:XXXUSD|5D`
- **Coinbase:** `COINBASE:XXXUSD|1D` or `COINBASE:XXXUSD|5D`
- **Other exchanges:** Follow TradingView's symbol format

**Note:** Use `|1D` for day view and `|5D` for 5-day view to match the page's timeframe.

## ✨ Features

- 📈 Real-time price data from Binance and Coinbase
- 🎨 Dark theme UI with consistent styling
- 📱 Mobile-responsive design
- 📊 Volume indicators
- 🔄 Auto-updating charts
- ⚡ Multiple timeframe options
- 🔗 **Dynamic symbol loading via URL parameters**

## 🛠️ Technology

- **TradingView Widget API** - Embedded chart widgets
- **GitHub Pages** - Static hosting
- **Pure HTML/CSS** - Lightweight and fast

## 📝 License

MIT License - see [LICENSE](LICENSE) file for details

## 👤 Author

**Hari Kiran Vusirikala**

---

*Last updated: October 18, 2025*