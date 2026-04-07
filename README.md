# GX Exchange Stats

GX Exchange Stats is the internal analytics and metrics backend for the GX Exchange platform. It aggregates trading data across the GX Chain network and computes platform-wide statistics including volume, user activity, liquidity, funding rates, and PnL distributions.

## Overview

- Collects and processes trading activity data from the GX Chain L1
- Computes aggregate metrics such as total volume, user counts, open interest, and liquidation data
- Serves computed metrics through a REST API for consumption by dashboards and internal tools
- Supports time-series queries with filtering by date range and asset

## API

The stats API exposes endpoints for retrieving platform metrics including cumulative volume, daily trade counts, user PnL, liquidation summaries, funding rates, open interest, and liquidity data.

## Requirements

- Python 3.10+
- PostgreSQL

## License

Proprietary. All rights reserved.
