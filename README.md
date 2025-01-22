# Eliza Starknet Starter Template

###

## Clone the repository
```bash
git clone https://github.com/Akashneelesh/eliza-starknet-starter-template.git
cd eliza-starknet-starter-template.git
```

## Duplicate the .env.example template

```bash
cp .env.example .env
```

\* Fill out the .env file with your own values.

### Add login credentials and keys to .env
```
STARKNET_ADDRESS=0x00
STARKNET_PRIVATE_KEY=0x00
STARKNET_RPC_URL=https://starknet-mainnet.public.blastapi.io/rpc/v0_7
...
ANTHROPIC_API_KEY="sk-xx-xx-xxx"

```

### Installing dependencies on the plugin-starknet and building
```bash
cd plugin-starknet
pnpm i && pnpm build
```

### Installing dependencies on the root
```bash
cd plugin-starknet
pnpm i 
pnpm add zod node-cache typescript
```

### Building the project
```bash
pnpm build && pnpm start
```

### A client to interact with our character
Hence we will be cloning the main eliza repository
```bash
git clone https://github.com/elizaOS/eliza.git
```

## Install dependencies

```bash
pnpm i 
```

### Starting the client 
```bash
pnpm start:client
```

Ones everything is done right you should see a localhost:5174 url, open that up in your browser.
And you should be to see an interface something like this
