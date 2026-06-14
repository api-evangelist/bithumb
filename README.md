# Bithumb

Bithumb is South Korea's leading cryptocurrency exchange platform (No.1 가상자산 플랫폼), offering REST and WebSocket APIs for spot trading across KRW, BTC, and USDT markets. The platform supports 396+ cryptocurrencies with endpoints covering market data, order management, account management, deposit and withdrawal operations, and real-time streaming.

## APIs

- **REST API** - Public market data and authenticated private endpoints for trading and account operations
- **WebSocket API** - Real-time streaming for tickers, order books, trade executions, and personal order updates

## Key Features

- Spot trading in KRW (Korean Won), BTC, and USDT base markets
- 396+ cryptocurrency trading pairs
- Public endpoints: ticker, orderbook, trade history, candlestick data (minute/hour/day/week/month)
- Private endpoints: order placement/cancellation, account balances, deposit/withdrawal management
- Bulk order operations (up to 20 orders) and bulk cancellation (up to 30 orders)
- TWAP (Time-Weighted Average Price) order support
- JWT-based authentication for private endpoints
- Real-time WebSocket streaming with heartbeat support
- Travel Rule compliance for cryptocurrency withdrawals
- Investment alert system

## Authentication

Public endpoints require no authentication. Private endpoints require JWT authentication tokens generated via the Bithumb developer portal.

## Rate Limits

- Order creation/cancellation: 10 requests per second per API key
- Public market data: Per-IP limits enforced (specific values managed by operations)

## Fees

- Maker fee: 0.04%
- Taker fee: 0.25%
- Six-tier membership discount system based on 30-day trading volume
- KRW withdrawal: 1,000 KRW flat fee
- BTC withdrawal: 0.001 BTC
- Deposits: Free

## Links

- [Developer Portal](https://apidocs.bithumb.com)
- [Documentation](https://apidocs.bithumb.com/docs)
- [Changelog](https://apidocs.bithumb.com/changelog)
- [GitHub (Bithumb Pro API Docs)](https://github.com/bithumb-pro/bithumb.pro-official-api-docs)
- [Main Website](https://www.bithumb.com)
