# viemcn.web3hacker.world

We translate the [viem Docs](https://github.com/wagmi-dev/viem) into Chinese here.

It will auto sync the docs to the `content/en` folder, then we make manual translate into the `content/zh` folder.

## Setup

```bash [init projects]
git clone git@github.com:Web3Hacker-World/viemcn.web3hacker.world.git
take _github && git clone --depth=1 git@github.com:wagmi-dev/viem.git 
cd ../viemcn.web3hacker.world
pnpm i --shamefully-hoist
```

```bash [sync docs]
pnpm sync
```

```bash [run the docs site local]
pnpm dev
```
