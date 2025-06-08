# Invictus Trading Terminal

Professional DeFi trading suite for Solana with automated strategies, yield optimization, and risk management.

## Features

- 🎯 Multiple Trading Strategies (Ladder, Grid, DCA, Momentum, Mean Reversion)
- 🌱 Automatic Yield Farming on Idle Capital  
- 📊 Real-time Analytics & Risk Monitoring
- 🔐 Non-custodial & Secure
- ⚡ Execute at Candle Close for Better Signals

## Tech Stack

- **Frontend**: HTML5, Vanilla JS (migrating to React)
- **Smart Contracts**: Anchor Framework (Rust)
- **Backend**: Node.js, TypeScript
- **Database**: PostgreSQL, Redis
- **Blockchain**: Solana

## Getting Started

### Prerequisites
- Node.js 16+
- Rust & Anchor CLI
- Solana CLI
- Docker & Docker Compose

### Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/invictus-trading.git
cd invictus-trading

# Install dependencies
npm install

# Start local validator
npm run localnet

# Deploy programs
npm run deploy:local

# Start development server
npm run dev
