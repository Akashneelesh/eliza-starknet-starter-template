# Eliza Starknet Starter Template

###

## Clone the repository
```bash
git clone https://github.com/Akashneelesh/eliza-starknet-starter-template.git
cd eliza-starknet-starter-template
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
And you should be to see an interface something like this and click on chat

<img width="1141" alt="Screenshot 2025-01-22 at 17 49 56" src="https://github.com/user-attachments/assets/d94a1a02-7e46-41ac-ba21-746f3565b6bf" />

### Transfer Action 

Now let's do a transfer action - to do that you will have to mention the type of token, the amount and finally the recievers address 

<img width="914" alt="Screenshot 2025-01-22 at 02 06 54" src="https://github.com/user-attachments/assets/1cc31570-9d83-435c-aa96-587dd86165c1" />

Thats pretty much it !!

You can go ahead with integrating this with various other usecases and also build your own actions under the plugin-starknet directory and get it integrated onto your protocol.
