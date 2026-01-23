# Tender API Documentation

Official API documentation for Tender - A cryptocurrency payment gateway platform that enables businesses to accept crypto payments across multiple blockchain networks.

## What This Documentation Covers

This documentation provides comprehensive guides and references for integrating with the Tender API:

- **Getting Started Guides** - Account setup, API credentials, and quick start tutorials
- **Authentication** - HMAC-SHA256 signature-based authentication implementation
- **API Reference** - Complete endpoint documentation with request/response examples
  - Agents & Businesses - Create and manage sub-businesses
  - Payment APIs - Initiate and validate cryptocurrency payments
  - System APIs - Fetch supported chains, currencies, and exchange rates
  - Webhooks - Real-time event notifications for transactions
- **Definitions** - Key terms and concepts
- **SDK Documentation** - JavaScript/TypeScript SDK guides

## Key Features

- Support for multiple blockchains (Ethereum, Avalanche, Polygon, Solana, Bitcoin, TRON, Aptos, and more)
- Cryptocurrency payment initiation and validation
- Real-time webhook notifications
- Agent/sub-business management
- Live exchange rate data
- Test and production environments

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing Changes

Changes pushed to the default branch are automatically deployed to production. Make sure to test changes locally before committing.

## Documentation Structure

```
docs/
├── api-reference/          # API endpoint documentation
│   ├── endpoint/          # Individual endpoint files
│   ├── authentication.mdx # Authentication guide
│   ├── introduction.mdx   # API overview
│   └── errors.mdx         # Error handling
├── get-started/           # Getting started guides
│   ├── api-credentials.mdx
│   ├── webhooks.mdx
│   └── definitions.mdx
├── sdk/                   # SDK documentation
├── openapi.json          # OpenAPI specification
└── docs.json             # Mintlify configuration
```

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Tender Dashboard](https://merchant.tender.cash) - Access your API credentials
- [Tender Website](https://tender.cash) - Learn more about Tender
- [Support](mailto:support@tender.cash) - Get help from our team
- [Mintlify Documentation](https://mintlify.com/docs) - Documentation platform guide
