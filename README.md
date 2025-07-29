# Kaspa Builders Directory

A complete platform to reward and showcase contributors to the Kaspa ecosystem.

## Features

- 🔐 **Wallet Integration** - Connect Kaspa wallets for voting and donations
- 🗳️ **Voting System** - Community-driven builder recognition
- 💰 **KAS Donations** - Direct support for builders
- 🪙 **KRC-20 Rewards** - Automated token distribution
- 🤖 **GitHub Scraping** - Automatic builder discovery
- 📊 **Admin Dashboard** - Complete management interface

## Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/kaspa-builders-directory.git
cd kaspa-builders-directory
```

2. **Install dependencies**
```bash
npm install
```

3. **Setup environment**
```bash
cp .env.example .env
# Edit .env with your values
```

4. **Run development server**
```bash
npm run dev
```

5. **Open browser**
```
http://localhost:3000
```

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Node.js, Express
- **Database**: PostgreSQL (coming soon)
- **Cache**: Redis (coming soon)
- **Blockchain**: Kaspa WASM SDK
- **Smart Contracts**: Kasplex KRC-20

## Project Structure

```
kaspa-builders-directory/
├── index.html          # Main frontend
├── admin.html          # Admin dashboard
├── src/
│   ├── server.js       # Express server
│   ├── routes/         # API routes
│   ├── services/       # Business logic
│   └── middleware/     # Express middleware
├── public/             # Static assets
├── docs/               # Documentation
└── package.json        # Dependencies
```

## Deployment

See [deployment guide](docs/deployment.md) for production setup.

## Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md).

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Support

- Discord: [Kaspa Community](https://discord.gg/kaspa)
- Twitter: [@KaspaBuilders](https://twitter.com/kaspabuilders)
- Email: support@kaspa-builders.org
