# Universal Resolver Matrix Documentation

The **Universal Resolver Matrix (URM)** is a comprehensive framework for implementing universal name resolution across diverse namespaces and ecosystems. It provides a systematic approach to mapping resolution pathways using four core dimensions: Trust Model, Proof System, Rules & Lifecycle, and Verification Path.

Built on Ethereum Name Service (ENS) infrastructure, the URM creates a unified identity resolution system that bridges traditional DNS, blockchain ecosystems, and modern authentication methods into a single, coherent framework.

## Documentation Structure

This documentation covers the complete Universal Resolver Matrix framework:

### 📖 Overview
- **Universal Resolver Matrix**: Core framework introduction and architecture
- **Resolution Patterns**: DNSSEC, EVM, Non-EVM, and WebAuthn implementations

### 🔧 Technical Specifications
- **DNSSEC Specification**: Trustless DNS→ENS resolution via DNSSEC P-256 signatures
- **EVM Specification**: ENSIP-19 multichain primary names across EVM ecosystems
- **Non-EVM Specification**: Extended ENSIP-19 support for non-EVM blockchains
- **WebAuthn Specification**: Passkey-based ENS name control and authentication

### 🔗 API Reference
Complete API documentation for integration and implementation

## Core Resolution Profiles

The URM implements four distinct resolution profiles:

1. **DNSSEC Onchain Resolution** - Trustless DNS→ENS resolution via DNSSEC P-256 signatures validated onchain
2. **EVM Resolution** - ENSIP-19 multichain primary names across EVM ecosystems
3. **Non-EVM Resolution** - Extends ENSIP-19 to non-EVM blockchains (Cosmos, Solana, etc.)
4. **WebAuthn Resolution** - Passkey-based ENS name control and authentication

## Development

### Prerequisites
- Node.js (v16 or later)
- npm or yarn

### Local Development

To preview documentation changes locally:

```bash
npm install
npm run dev
```

View your local preview at `http://localhost:3000`.

### Building

To build the documentation for production:

```bash
npm run build
```

## Deployment

This documentation is automatically deployed when changes are pushed to the main branch. The deployment process handles building and publishing the documentation site.

## Contributing

### Documentation Updates
1. Make your changes to the `.mdx` files
2. Test locally with `mint dev`
3. Commit and push to the main branch
4. Changes are automatically deployed

### Framework Development
The Universal Resolver Matrix framework is developed at [eureka.etcetera](https://github.com/eurekaetcetera). See the main repository for implementation details.

## Need Help?

### Troubleshooting

- **Dev environment not running**: Run `mint update` to ensure you have the latest CLI version
- **404 errors**: Ensure you're running from a directory with a valid `docs.json`
- **Build failures**: Check that all required dependencies are installed

### Resources

- [ENS Documentation](https://docs.ens.domains)
- [ENSIP Specifications](https://docs.ens.domains/ensip/)
- [Universal Resolver Matrix Research](https://github.com/eurekaetcetera)

## License

This documentation is part of the Universal Resolver Matrix research project. See the main repository for licensing information.
