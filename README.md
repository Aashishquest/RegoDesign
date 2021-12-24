# RegoSwap Interface

[![Styled With Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)

An open source interface for RegoSwap -- a protocol for decentralized exchange of Ethereum tokens.

- Website: [regoex.com](https://regoex.com/)
- Interface: [regoswapbsctestnet.netlify.app](https://regoswapbsctestnet.netlify.app/)
- Docs: [sushiswap.gitbook.io](https://sushiswap.gitbook.io)
- Twitter: [@Regoexch](https://twitter.com/regoexch)
- Reddit: [/r/SushiSwap](https://www.reddit.com/r/SushiSwap)
- Discord: []](https://discord.com/channels/921397558050447370/921397560592187435)

## Accessing the RegoSwap Interface

To access the Regoswap Interface, use an IPFS gateway link from the
[latest release](https://github.com/sushiswap/sushiswap-interface/releases/latest),
or visit [app.sushi.com](https://app.sushi.com).

## Listing a token

Please see the
[quest-regoswap-default-token-list](https://github.com/sushiswap/default-token-list)
repository.

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

Note that the interface only works on networks where both
[(Uni|Rego)swap V2](https://github.com/sushiswap/sushiswap/tree/master/contracts/uniswapv2) and
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Contributions

**Please open all pull requests against the `master` branch.**
CI checks will run against all PRs.
