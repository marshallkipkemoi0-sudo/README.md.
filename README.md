# README.md.
BTCUSD Market Learning MCP

A read-only MCP service for exploring Bitcoin market data and learning market structure concepts.

Initial features

Retrieve historical candle data from a clearly identified data source.

Summarize candle ranges and basic market structure.

Report timestamps, missing candles, and stale data.

Provide educational market analysis without placing trades.

Data source

TradingView is a charting platform, not automatically a server-side market-data API. The data provider must be selected explicitly. Its BTCUSD feed may differ from a broker's BTCUSD price.

Safety and scope

Read-only operation.

No order execution or account credentials.

Educational analysis, not personalized financial advice.

No guarantees of profitability.

Development roadmap

Add a market-data adapter.

Build and test read-only MCP tools.

Add descriptive market-structure analysis.

Deploy securely over HTTPS.

Connect through a supported ChatGPT MCP integration.