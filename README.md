# Noble NFT Orderbook

TypeScript service that supports orderbook and marketplace workflows for the Noble NFT Marketplace. It includes an HTTP API, background publishers and consumers, Prisma integration, and deployment configuration.

## Architecture

- `src/services/api-web/` — API service
- `src/services/publishers/` — background producers
- `src/services/consumers/` — event-processing consumers
- `prisma/` — database schema and Prisma configuration

## Development

```bash
yarn install
yarn build
yarn dev
```

Run `yarn test`, `yarn lint`, and `yarn typecheck` before deployment. Configure database and third-party service credentials through environment variables; do not commit them.

## Status

Confirm external service compatibility and operational configuration before running this service in a production marketplace.

