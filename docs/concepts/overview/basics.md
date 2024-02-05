---
title: Basics
heroImage: /images/backgrounds/red.png
order: 10
---

# Basics

::: info
All docs on this site refer to Balancer V3.
:::

## What is Balancer?

Balancer is a decentralized automated market maker (AMM) protocol built on Ethereum that represents a flexible building block for programmable liquidity.

By separating the AMM curve logic and math from the core swapping functionality, Balancer becomes an extensible AMM that can incorporate any number of swap curves and pool types. This includes:

- Traditional 50/50 $x*y=k$ weighted pools
- Custom weights like 80/20 for controlled exposure
- Stable swap curves
- Nested pools (ex: [Boosted Pools](/concepts/pools/boosted))
- Pools with changing weights (ex: [Liquidity Bootstrapping Pools](/concepts/pools/liquidity-bootstrapping))
- Concentrated liquidity pools
- Managed pools that allow customizable parameters
- Custom AMMs to be built on top (ex: Gyroscope, Xave)

All of the aggregate liquidity is then easily accessible for swappers, aggregators, and arbitrageurs. The Balancer [Vault](/concepts/vault) optimizes batching and path logic so that gas costs and capital requirements remain extremely low. Each individual pool and project built on top benefits from the global liquidity within Balancer that brings deep liquidity for base assets and opens up swap paths.

## Balancer V3

Balancer V3 addresses the high complexity of the V2 system by decreasing complexity, while maintaining flexibility. This comes with being more opinionated for the main protocol interactions. A separate Router component is introduced that functions as the overall entrypoint to the Balancer system.

## Who uses Balancer?

Balancer is an incredibly useful tool for a diverse set of actors in the Defi space.

Swappers can swap between any two ERC20 tokens. This can be done through the [Balancer Dapp](https://app.balancer.fi/#/ethereum/swap) or aggregators like [1inch](https://app.1inch.io), [Matcha](https://www.matcha.xyz), or [Paraswap](https://app.paraswap.io).

Liquidity Providers (LPs) can add liquidity to pools to earn swap fees, liquidity incentives, and other forms of yield

- Passive LPs can utilize boosted pools to earn on top of their already compounding Aave tokens

Arbitrageurs can swap against pools using things like batch swaps and flash loans

BAL Token holders can lock their token into veBAL and participate in the governance of evolving the Balancer protocol

## Helpful Articles to Learn More

- [What are automated market makers?](https://chain.link/education-hub/what-is-an-automated-market-maker-amm)
- [What is Balancer? The Complete Guide](https://medium.com/balancer-protocol/what-is-balancer-the-complete-guide-762ee230a9d4)
