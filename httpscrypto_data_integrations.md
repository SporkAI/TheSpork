# Crypto Data Integrations

## CoinGecko API Integration

- **Purpose:** Pull prices, market caps, volumes, and metrics for numerous tokens.
- **Endpoints:** `/simple/price`, `/coins/markets`
- **Normalization and Caching:** Ensure consistent formats, cache frequent queries, and reduce latency.

[CoinGecko API Docs](https://www.coingecko.com/en/api/documentation)

## Dexscreener API Integration

- **Purpose:** Gather DEX liquidity, pairs, and volumes.
- **Normalization:** Uniform data schema, caching, and rate-limit handling.

[Dexscreener API Docs](https://docs.dexscreener.com/)

## Data Normalization and Caching

- **Normalization:** Standardize fields, units, and timestamps.
- **Caching:** Store recent data for performance gains and fewer API calls.
