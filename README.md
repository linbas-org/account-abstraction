# Account Abstraction with the thirdweb Connect SDK

A reference implementation repository by linbas-org demonstrating account abstraction features using the [Connect SDK](https://portal.thidweb.com/connect).

Key features demonstrated:

- Gasless transactions
- Session keys
- Batch transactions

## Live demo

[Try the live demo](https://account-abstraction.linbas.org)

## Local Development Setup

### 1. Configure Client ID

First, you'll need to set up your client ID to use the thirdweb SDK.

Follow the [Creating a client](https://portal.thirdweb.com/typescript/v5/client) guide to obtain your client ID.

Update the `clientId` in `src/constants.ts`:

```ts
const clientId = "YOUR_CLIENT_ID";
```

### 2. Install Dependencies

```bash
yarn install
```

### 3. Start Development Server

```bash
yarn dev
```

## Documentation & Resources

- [thirdweb Connect Documentation](https://portal.thirdweb.com/connect)
- [Connect SDK Reference](https://portal.thirdweb.com/typescript/v5)
- [thirdweb Dashboard](https://thirdweb.com/dashboard)

## Support

For questions and support:
- Join our Discord: [https://discord.gg/linbas](https://discord.gg/linbas)
- Visit our website: [https://linbas.org](https://linbas.org)

## License

MIT License - see LICENSE file for details.
