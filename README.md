# the-namecn.web3hacker.world

We translate the [the-name Docs](https://github.com/Web3Hacker-World) into Chinese here.

It will auto sync the docs to the `content/en` folder, then we make manual translate into the `content/zh` folder.

## Setup

```bash [init projects]
git clone git@github.com:Web3Hacker-World/the-namecn.web3hacker.world.git
take _github && git clone --depth=1 git@github.com:your-source/repo.git 
cd ../the-namecn.web3hacker.world
pnpm i --shamefully-hoist
```

```bash [sync docs]
pnpm sync
```

```bash [run the docs site local]
pnpm dev
```
