# Awesome Onchain Applications

A curated list of onchain applications built using Bitquery's blockchain data APIs. These applications demonstrate the power of real-time blockchain data for building innovative solutions across DeFi, NFTs, trading, analytics, and more.

## Table of Contents

- [Trading & DeFi](#trading--defi)
- [NFT Applications](#nft-applications)
- [Analytics & Dashboards](#analytics--dashboards)
- [Bots & Automation](#bots--automation)
- [Monitoring & Tracking](#monitoring--tracking)
- [MEV & Arbitrage](#mev--arbitrage)
- [Data Visualization](#data-visualization)
- [Developer Tools](#developer-tools)
- [Investigation & Compliance](#investigation--compliance)

## Trading & DeFi



### Polymarket Trade Tracker
CLI tooling for inspecting `OrderFilled` events on the Polymarket CTF Exchange using Bitquery’s GraphQL stream; track trader activity, assets, and price history.

- **Features**:
  - Watch `OrderFilled` events in real-time directly from Bitquery’s GraphQL stream
  - Track individual traders, total volume, unique assets, and recent fills
  - Inspect a specific asset’s trade history and derive indicative prices
  - Generate leaderboard-style tables for most active traders/assets (configurable depth)
- **GitHub**: [https://github.com/Divyn/Polymarket-trade-Tracker-cli](https://github.com/Divyn/Polymarket-trade-Tracker-cli)


### Solana Arbitrage Dashboard

A Next.js dashboard that displays arbitrage opportunities for WSOL/USDC pair on Solana by monitoring DEX exchange rates in real-time.

- **Tech Stack**: Next.js, React, Axios, Tailwind CSS
- **Features**: Real-time arbitrage detection, DEX comparison, execute functionality
- **GitHub**: [https://github.com/0xeKshitij/solana-arbitrage](https://github.com/0xeKshitij/solana-arbitrage)

### Copy Trading Bot

A Solana copy trading bot that replicates trades executed by a specified account. Fetches trading data using Bitquery API and stores trade information.

- **Tech Stack**: Python, Pandas
- **Features**: Real-time trade replication, trade logging to Excel
- **GitHub**: [https://github.com/Kshitij0O7/copy-trading-bot](https://github.com/Kshitij0O7/copy-trading-bot)

### Price Change Signal Bot

A bot that monitors price changes and sends signals when specific conditions are met.

- **GitHub**: [https://github.com/bitquery/Price-Change-Signal-Telegram-Bot](https://github.com/bitquery/Price-Change-Signal-Telegram-Bot)

### Add Liquidity Signal Bot

A bot that detects and signals when liquidity is added to pools.

- **GitHub**: [https://github.com/Akshat-cs/Add-Liquidity-Signal-Bot](https://github.com/Akshat-cs/Add-Liquidity-Signal-Bot)

### Uniswap Liquidity Finder for Market Makers
Analyze Uniswap v3 WETH/USDT liquidity, bucket positions into price bands, and highlight the most capitalized ranges to help market makers optimize where to add or remove liquidity.

- **GitHub**: [https://github.com/Divyn/uniswap-v3-liquidity-edge-market-maker](https://github.com/Divyn/uniswap-v3-liquidity-edge-market-maker)

### Automated Trading Ethereum Volume Surge Bot

An automated trading bot that monitors Ethereum volume surges and executes trades based on predefined conditions.

- **GitHub**: [https://github.com/bitquery/volume-surge-trading-bot](https://github.com/bitquery/volume-surge-trading-bot)

### Solana OHLC Calculator

Calculator for OHLC (Open, High, Low, Close) data on Solana blockchain.

- **GitHub**: [https://github.com/Akshat-cs/OHLC-Calculator-Solana](https://github.com/Akshat-cs/OHLC-Calculator-Solana)



### Streaming Moonshot Prices

Real-time price streaming application for Moonshot tokens.

- **GitHub**: [https://github.com/Divyn/streaming-moonshot-prices](https://github.com/Divyn/streaming-moonshot-prices)

### Profit & Loss Calculator

A JavaScript-based profit and loss calculator using Bitquery's DEXTrades API to calculate realized PnL for crypto trading.

- **Tech Stack**: JavaScript, Node.js
- **Features**: Weighted average buy price calculation, realized PnL computation

### TradingView Integration

Integration with TradingView charts for displaying real-time and historical OHLC data.

- **Tech Stack**: JavaScript, TradingView Charting Library
- **Features**: Custom datafeed, real-time subscriptions, historical data
- **GitHub**: [https://github.com/bitquery/tradingview-subscription-realtime](https://github.com/bitquery/tradingview-subscription-realtime)

### TradingView React Example

React implementation using TradingView's lightweight-charts library for displaying blockchain trading data.

- **Tech Stack**: React, TradingView Lightweight Charts
- **Features**: Interactive charts, real-time data updates
- **GitHub**: [https://github.com/bitquery/tradingview-react-v2-example](https://github.com/bitquery/tradingview-react-v2-example)

## NFT Applications

### NFT Analytics Dashboard

A Python-based NFT analytics dashboard using Streamlit that connects to Bitquery API to retrieve and display NFT transaction data on Ethereum.

- **Tech Stack**: Python, Streamlit, Pandas
- **Features**: NFT transaction tracking, marketplace analysis, daily metrics charts

### NFT Creator Portfolio

A React-based portfolio application for NFT creators to showcase their work and track NFT data.

- **Tech Stack**: React, Bootstrap, Framer Motion
- **Features**: NFT portfolio display, animated UI, routing
- **GitHub**: [https://github.com/bitquery/nft-creator-portfolio](https://github.com/bitquery/nft-creator-portfolio)

### NFT Scanner

A multi-chain NFT scanner that scans NFTs across various blockchains for a given address using Python.

- **Tech Stack**: Python, Requests
- **Features**: Multi-chain support, NFT balance tracking, metadata retrieval

## Analytics & Dashboards

### Wash Trading Detector

A Solana wash trading detection system that fetches on-chain DEX trades, labels potential wash trades using rule-based methods, trains an XGBoost model, and deploys an interactive Streamlit dashboard.

- **Tech Stack**: Python, XGBoost, Streamlit, Scikit-learn
- **Features**: ML-based wash trade detection, real-time visualization, risk metrics calculation
- **GitHub**: [https://github.com/Kshitij0O7/wash-trading-detector](https://github.com/Kshitij0O7/wash-trading-detector)

### Token Holder Heatmap

Visualization application for displaying token holder distribution and activity.

### Top 10 Ethereum Tokens

Application for tracking and displaying the top 10 Ethereum tokens by various metrics.

- **GitHub**: [https://github.com/Akshat-cs/Top-10-Ethereum-Tokens-live](https://github.com/Akshat-cs/Top-10-Ethereum-Tokens-live)

### How to Filter Anomaly Prices

Guide for building applications that filter and detect anomalous price movements.

### DEX Rabbit

A comprehensive DEX analytics platform for Solana with multiple components:

- **Tech Stack**: Various
- **Features**:
  - DEX Markets analysis
  - Token tracking
  - Pool monitoring
  - Pair analytics
  - Trader insights
  - PumpFun integration
  - Bids tracking

## Bots & Automation

### Solana Sniper Bot

A Solana sniper bot that listens for specific on-chain instructions and performs token swaps using Bitquery real-time subscriptions and Jupiter Swap API.

- **Tech Stack**: Node.js, Solana Web3.js, Jupiter API
- **Features**: Real-time instruction monitoring, automatic token swaps

### Base Sniper Bot

Sniper bot implementation for Base blockchain.

- **GitHub**: [https://github.com/Akshat-cs/Base-sniper-bot](https://github.com/Akshat-cs/Base-sniper-bot)

### Arbitrum Sniper Bot

Sniper bot implementation for Arbitrum blockchain.

- **GitHub**: [https://github.com/Akshat-cs/Arbitrum-sniper-bot](https://github.com/Akshat-cs/Arbitrum-sniper-bot)

### Telegram Bot

A Telegram bot that fetches blockchain data in real-time using WebSocket connections to Bitquery and sends updates to Telegram chat.

- **Tech Stack**: Python, Telegram Bot API, WebSockets
- **Features**: Real-time blockchain data streaming, message handling
- **GitHub**: [https://github.com/divyasshree-BQ/telegram-bot](https://github.com/divyasshree-BQ/telegram-bot)

### Discord Bot

A Discord bot that fetches price data using the DEXTrades API and responds to commands in a Discord server.

- **Tech Stack**: Node.js, Discord.js, Axios
- **Features**: Price queries, command handling

## Monitoring & Tracking

### Real-Time Balance Tracker

A JavaScript/Node.js application for monitoring wallet balances in real-time using Bitquery's Balance Updates API and WebSocket connections.

- **Tech Stack**: JavaScript, Node.js, HTML, CSS
- **Features**: Real-time balance calculation, WebSocket streaming, intuitive UI
- **GitHub**: [https://github.com/Kshitij0O7/real-time-balance](https://github.com/Kshitij0O7/real-time-balance)

### Track Millions of Solana Wallets

Application for tracking and monitoring millions of Solana wallets at scale.

- **GitHub**: [https://github.com/bitquery/solana-wallet-tracker](https://github.com/bitquery/solana-wallet-tracker)

### Monitoring Solana at Scale

Guide for managing and monitoring hundreds of Solana addresses efficiently.

### Monitoring Solana Blockchain Real-Time

Real-time monitoring application for Solana blockchain activities.

- **GitHub**: [https://gist.github.com/divyasshree-BQ/84bc875bf1c3c3e9088653d5c9b5d7eb](https://gist.github.com/divyasshree-BQ/84bc875bf1c3c3e9088653d5c9b5d7eb)

### Binance Exchange Wallet Monitoring

Application for monitoring Binance exchange wallets and their activities.

- **GitHub**: [https://github.com/bitquery/binance-exchange-wallets-monitoring](https://github.com/bitquery/binance-exchange-wallets-monitoring)

### Mempool Transaction Fee

Application for monitoring and analyzing transaction fees in the mempool.

## MEV & Arbitrage

### Sandwich Detection

A PHP-based application that detects sandwich attack opportunities on Ethereum by monitoring mempool for large DEX trades.

- **Tech Stack**: PHP, HTTP_Request2
- **Features**: Real-time MEV opportunity detection, large trade monitoring

## Data Visualization

### Crypto Price API Integration

Integration with Bitquery's Crypto Price API for real-time and historical price data.

## Developer Tools

### MCP (Model Context Protocol)

Integration with Model Context Protocol for AI/LLM applications.

### Building dApps

Comprehensive guide for building decentralized applications using Bitquery Streaming API.

- **Use Cases**:
  - Decentralized exchanges (DEXs)
  - Wallets and portfolio trackers
  - Trading bots and algorithmic trading platforms
  - NFT Analytics Platforms
  - DeFi lending platforms
  - Gaming dApps

## Investigation & Compliance

### Tornado Cash Transaction Match Finder
A de-mixing and attribution tool for Tornado Cash transactions. This tool matches deposits to withdrawals, detects behavioral patterns, and identifies network connections for investigators.

- **GitHub**: [https://github.com/Divyn/tornado-cash-intelligent-demixer](https://github.com/Divyn/tornado-cash-intelligent-demixer)


### Crypto Reward Tax Calculator

A tax calculator application for crypto rewards and staking income.

- **URL**: https://docs.bitquery.io/crypto-reward-tax-calculator

### PumpFun Token Sniffer

Token discovery and analysis tool for PumpFun platform.

- **URL**: https://docs.bitquery.io/pumpfun-token-sniffer


---

**Built with [Bitquery](https://bitquery.io/) - The blockchain data platform for traders, investigators & developers**
